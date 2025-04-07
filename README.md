# resumo-do-lab -SLA (Service Level Agreement) - Tempos de Inatividade Permitidos

Este documento apresenta os diferentes níveis de SLA e os respectivos tempos de inatividade tolerados por semana, mês e ano.

| SLA (%)    | Por Semana       | Por Mês         | Por Ano         |
|------------|------------------|------------------|------------------|
| **99.0%**  | 1,68 horas        | 7,2 horas        | 3,65 dias        |
| **99.9%**  | 10,1 minutos      | 43,2 minutos     | 8,76 horas       |
| **99.95%** | 5 minutos         | 21,6 minutos     | 4,38 horas       |
| **99.99%** | 1,01 minuto       | 4,32 minutos     | 52,56 minutos    |
| **99.999%**| 6 segundos        | 25,9 segundos    | 5,26 minutos     |

## O que é SLA?

SLA (Service Level Agreement) é um acordo de nível de serviço que define a disponibilidade mínima esperada de um sistema, serviço ou aplicação. Ele é geralmente expresso em porcentagem e reflete a confiabilidade que o fornecedor se compromete a oferecer.

## Interpretação dos Níveis

- **99.0%**: Mais adequado para serviços menos críticos, com até 3,65 dias de inatividade por ano.
- **99.9% (three nines)**: Bom para sistemas importantes, com menos de 9 horas de inatividade anuais.
- **99.95%**: Nível comum em serviços profissionais.
- **99.99% (four nines)**: Alta disponibilidade, indicado para serviços de missão crítica.
- **99.999% (five nines)**: Padrão de excelência, usado em serviços onde a interrupção deve ser praticamente inexistente.

## Uso

Essa tabela pode ser usada como referência para definir SLAs em contratos, apresentações técnicas ou avaliações de desempenho de sistemas.

---

> 📌 **Nota:** Quanto maior o SLA, maior o custo e a complexidade para manter a infraestrutura. A escolha deve sempre considerar o impacto do tempo de inatividade no negócio.

