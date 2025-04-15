# 🧠 Desafio DIO - Machine Learning em Nuvem (Microsoft Azure)

## Descrição Geral

Este projeto documenta o passo a passo da execução de um experimento de *Machine Learning Automatizado (AutoML)* na plataforma **Microsoft Azure**, como parte do desafio do Bootcamp da DIO.

---

## 🔹 Etapa 1: Instalação do Machine Learning via Marketplace da Azure

**Ação:**

- Acesso ao portal [https://portal.azure.com](https://portal.azure.com)
- Pesquisa e instalação do recurso **Machine Learning** no marketplace
- Criação do workspace: nome, região, grupo de recursos e revisão final

**Status:** Finalizado com sucesso

---

### 🔹 Etapa 2: Criação de Experimento com AutoML

**Ação:**

- Acesso ao [Azure ML Studio](https://ml.azure.com)
- Criação de novo experimento AutoML
- Escolha do dataset, definição da tarefa como *Regressão*

**Status:** Configuração inicial completada

---

### 🔹 Etapa 3: Importação dos Dados e Escolha do Dataset

**Dataset utilizado:** `alugueldebicicletas3`

- Importado via disco local
- Tipo: Tabela
- Criado em: 09/04/2025 20:20h
- Tarefa selecionada: **Regressão**

**Status:** Dataset pronto para uso no experimento

---

### 🔹 Etapa 4: Configurações de Tarefa

**Coluna de destino (target):** `rentals` (Integer)

**Limites definidos:**

- Avaliações máximas: `3`
- Avaliações simultâneas: `3`
- Nós máximos: `3`
- Limite de métrica: `0.085`
- Tempo limite de experimento: `15 min`
- Tempo limite por iteração: `15 min`
- Encerramento antecipado: **Habilitado**

**Validação:**

- Tipo: Divisão de treinamento (Train Validation Split)
- Percentual reservado: `10%`

**Status:** Tarefa configurada corretamente

---

### 🔹 Etapa 5: Computação

**Tipo de computação:** Sem servidor  
**Tipo de máquina virtual:** CPU (Dedicada)  
**Modelo:** `Standard_DS3_v2`

- 4 núcleos, 14GB RAM, 28GB armazenamento
  - Custo: `$0.29/h`  
**Instâncias:** `1`

**Status:** Computação configurada com sucesso

---

### 🔹 Etapa 6: Envio do Trabalho

**Ação:**

- Finalização de configurações
- Envio do trabalho para execução no Azure

**Resultado esperado:**

- Treinamento automático de vários modelos de regressão
- Seleção automática do melhor modelo baseado na métrica definida

**Status:** Envio realizado com sucesso

---

## Considerações Finais

O Azure ML Studio oferece uma plataforma robusta para experimentos automatizados de machine learning, permitindo realizar tarefas de regressão de forma rápida e controlada. Com poucos cliques, é possível treinar, validar e escolher o melhor modelo com base em dados reais.

---
S