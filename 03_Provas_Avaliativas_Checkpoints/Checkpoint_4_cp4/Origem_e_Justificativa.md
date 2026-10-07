# Origem e Justificativa do Problema

**Disciplina:** Internet das Coisas & Telecomunicações
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Dimensionar a arquitetura de ingestão de dados em nuvem para processamento de telemetria de 50.000 nós sensores transmitindo mensagens JSON de 128 bytes a cada 10 segundos. Dimensionar a capacidade do Message Broker (AWS IoT Core / Azure IoT Hub / EMQX), o particionamento do banco de séries temporais (InfluxDB / TimescaleDB) e a largura de banda de entrada requerida.

### Formulação Formal
$$\text{Taxa Mensagens} = \frac{N_{\text{dispositivos}}}{T_{\text{envio}}}, \quad \text{Throughput (MB/s)} = \frac{\text{Taxa Mensagens} \cdot \text{Tamanho (bytes)}}{10^6}$$
