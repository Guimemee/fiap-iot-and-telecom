# Origem e Justificativa do Problema

**Disciplina:** Internet das Coisas & Telecomunicações
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Analisar o impacto computacional, overhead de memória RAM/Flash e tempo de conexão do aperto de mão (Handshake) criptográfico utilizando TLS 1.3 sobre TCP e DTLS 1.2 sobre UDP em um microcontrolador de 32 bits rodando mbedTLS com e sem suporte a acelerador criptográfico de hardware (Hardware Cryptographic Accelerator).

### Formulação Formal
$$t_{\text{handshake}} = t_{\text{rede}} \cdot \text{RTT} + t_{\text{cripto}}, \quad \text{Aceleração Hardware} \approx 6\text{ a }10\times$$
