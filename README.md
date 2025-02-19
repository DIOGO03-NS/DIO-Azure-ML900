# Guia: Utilizando o Azure Machine Learning para Processar seus Dados

## 📌 Introdução
Azure Machine Learning (Azure ML) é uma plataforma da Microsoft que permite treinar, implantar e gerenciar modelos de machine learning na nuvem. Este guia apresenta um passo a passo para carregar e processar dados dentro do Azure ML.

---

## 🏗️ Passo a Passo

### 1️⃣ Criando um Workspace no Azure ML

1. Acesse o portal do [Azure](https://portal.azure.com/).
2. No menu lateral, pesquise por **Machine Learning** e clique na opção correspondente.
3. Clique em **+ Criar** e preencha os seguintes campos:
   - **Nome do workspace**: Escolha um nome único.
   - **Grupo de Recursos**: Selecione um existente ou crie um novo.
   - **Região**: Escolha a mais próxima para otimizar latência.
4. Clique em **Revisar + Criar** e finalize o processo.

### 2️⃣ Configurando o Ambiente

1. No portal do Azure ML, vá até **Ambientes de Computação**.
2. Escolha uma opção:
   - **Máquina Virtual**: Ideal para desenvolvimento interativo.
   - **Cluster de Treinamento**: Recomendado para grandes volumes de dados.
3. Configure os recursos (CPU/GPU) conforme a necessidade.

### 3️⃣ Carregando seus Dados

1. No menu lateral, vá até **Armazenamento de Dados**.
2. Clique em **Criar** e escolha um dos métodos:
   - **Upload Manual**: Enviar arquivos diretamente.
   - **Azure Blob Storage**: Conectar a um armazenamento externo.
   - **Conexão com Data Lake**: Para grandes volumes de dados.
3. Após o upload, confirme se os dados estão disponíveis na aba **Datasets**.
---

## 🎯 Conclusão
Seguindo esses passos, você conseguirá utilizar o Azure ML para armazenar, processar e treinar modelos com seus dados de forma eficiente. 🚀