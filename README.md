# Projeto para o Bootcamp Dio Decola Tech 2025

### Guia para Configuração de Pesquisa com Azure AI Search

Neste guia, há um passo a passo de como configurar uma pesquisa usando o Azure AI Search, criando as bases para mineração de conhecimento que facilita a busca por insights a partir da extração de dados. Para informações mais detalhadas, consulte o [artigo oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).

## Recursos Necessários

Para criar a solução, você precisará de:

- **Azure AI Search**: para gerenciar indexação e consultas.
- **Azure AI Services**: para enriquecer os dados com insights gerados por IA.
- **Conta de armazenamento**: para armazenar documentos e coleções de arquivos.

**Importante**: O recurso de **Azure AI Search** e o recurso **Azure AI Services** devem estar na mesma região.

## Passo a Passo

### 1. Criar o Recurso de Azure AI Search

1. **Acesse o portal do Azure**.
2. Clique em **+ Criar um recurso** e procure por **Azure AI Search**.
3. Preencha as configurações:
   - **Assinatura**: Sua assinatura do Azure.
   - **Grupo de Recursos**: Selecione ou crie um novo grupo de recursos.
   - **Nome do serviço**: Escolha um nome único.
   - **Região**: Escolha uma região disponível (recomenda-se "East US 2").
   - **Nível de Preço**: Básico.
4. Clique em **Revisar + Criar** e, após a validação, clique em **Criar**.
5. Após a conclusão, vá para o **Recurso** de Azure AI Search e adicione índices, importe dados e faça buscas.

### 2. Criar o Recurso de Azure AI Services

1. No portal, clique em **+ Criar um recurso** e busque por **Azure AI Services**.
2. Configure com:
   - **Assinatura**: A mesma assinatura utilizada para o Azure AI Search.
   - **Grupo de Recursos**: O mesmo grupo de recursos.
   - **Região**: A mesma região do Azure AI Search.
   - **Nível de Preço**: Standard S0.
3. Clique em **Revisar + Criar** e, após a validação, clique em **Criar**.

### 3. Criar uma Conta de Armazenamento

1. No portal, clique em **+ Criar um recurso** e procure por **Armazenamento de Conta**.
2. Preencha as configurações:
   - **Assinatura**: Sua assinatura do Azure.
   - **Grupo de Recursos**: O mesmo grupo de recursos.
   - **Nome da Conta**: Nome único.
   - **Região**: A mesma região do Azure AI Search.
   - **Desempenho**: Padrão.
   - **Redundância**: Armazenamento localmente redundante (LRS).
3. Clique em **Revisar + Criar** e, após a validação, clique em **Criar**.

## Insights e Possibilidades de Ferramentas

- **Insights**: A utilização de IA no enriquecimento de dados permite a extração de informações valiosas, como localização, frases-chave e sentimentos, oferecendo uma visão mais profunda sobre as avaliações dos clientes.
- **Ferramentas Beneficiadas**: Ferramentas de análise de dados e BI podem se beneficiar dessas informações, integrando-as para criar relatórios dinâmicos e insights acionáveis.

## Aprendizados Adquiridos

- O Azure AI Search automatiza a extração e enriquecimento de dados, usando inteligência artificial para analisar, identificar entidades e reconhecer objetos, melhorando a precisão da pesquisa.
- Facilita a indexação e pesquisa de dados em diversos formatos e fontes, como documentos e imagens, tornando a informação mais acessível e organizada.
- Ao automatizar processos, o Azure AI Search economiza tempo e recursos, reduzindo o custo total de implementação de soluções de busca.
