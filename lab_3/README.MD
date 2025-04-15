# Azure Vision Studio - Detecção de Faces

Descrição Geral

Este README descreve o uso do **Azure Vision Studio** para detecção de rostos humanos em imagens, com base na criação e configuração de recursos de Cognitive Services.

---

## 🔹 Etapa 1: Criação do Recurso Azure AI

**Ação:**

- Acessar o portal [Azure Portal](https://portal.azure.com)
- Ir em **"Create a resource" > Azure AI services**
- Preencher:
  - Subscription: Azure subscription 1
  - Resource Group: existente ou novo
  - Region: East US
  - Nome do recurso: `iaimagem`
  - Pricing tier: `Standard S0`
- Confirmar os termos de uso e clicar em **Create**

**Resultado:** Serviço Cognitive Services provisionado com sucesso

---

### 🔹 Etapa 2: Selecionar o Recurso no Vision Studio

**Ação:**

- Acessar [Vision Studio](https://portal.vision.cognitive.azure.com/)
- Selecionar o recurso `iaimagem`
- Clicar em **"Select as default resource"**

**Objetivo:** Associar o recurso criado às ferramentas de visão computacional disponíveis no estúdio

---

### 🔹 Etapa 3: Detecção de Rostos em Imagens

**Ferramenta:** `Detect faces in an image`

**Funcionalidade:**

- Detecta localização de rostos humanos em imagens
- Retorna atributos como:
  - Pose facial
  - Uso de máscara
  - Marcos faciais (olhos, nariz, boca)
  - Emoção estimada

**Testes:**

- É possível:

  - Fazer upload de arquivo
  - Capturar foto com a câmera
  - Usar imagens de exemplo

**Saída:**

- Visualização gráfica dos rostos detectados
- Detalhes em aba JSON com todos os dados brutos retornados

---

Próximos Passos

- Integrar a funcionalidade em aplicações reais usando:
  - [REST API](https://learn.microsoft.com/en-us/azure/cognitive-services/face/)
  - [Face SDK](https://learn.microsoft.com/en-us/azure/cognitive-services/face/sdk)
- Consultar [código de exemplo](https://github.com/Azure-Samples/cognitive-services-REST-api-samples)


