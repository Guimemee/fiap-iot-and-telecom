# Origem e Justificativa do Problema

**Disciplina:** Internet das Coisas & Telecomunicações
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Calcular o orçamento de enlace (Link Budget) e o alcance máximo de comunicação para um enlace de rádio LoRa na frequência de 915 MHz no espaço livre utilizando a Equação de Friis. O transmissor possui potência Pt = +14 dBm e ganho de antena Gt = +2 dBi; o receptor possui ganho Gr = +3 dBi e sensibilidade de recepção Pr_min = -137 dBm. Considerar margem de desvanecimento (Fade Margin) de 15 dB e perdas em conectores/cabos de 2 dB.

### Formulação Formal
$$P_{rx} = P_{tx} + G_{tx} + G_{rx} - \text{FSPL} - L_{\text{outros}}, \quad \text{FSPL}(\text{dB}) = 20\log_{10}(d) + 20\log_{10}(f) + 32,44$$
