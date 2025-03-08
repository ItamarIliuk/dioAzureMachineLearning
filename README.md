# dioAzureMachineLearning

```markdown
# Resumo do Tutorial de Machine Learning no Azure

Este repositório apresenta um resumo em português, estruturado em formato Markdown, do tutorial “Lab 01 - Machine Learning” publicado pela Microsoft Learning. Aqui, você encontrará um passo a passo que orienta desde a criação do ambiente até a limpeza dos recursos no Azure Machine Learning e no Azure Portal.

---

## Introdução

O tutorial tem como objetivo introduzir os conceitos básicos de Machine Learning utilizando a plataforma Azure Machine Learning. Por meio deste guia, o usuário aprenderá a:
- Criar e configurar um workspace no Azure Machine Learning.
- Provisão de recursos computacionais para treinamento do modelo.
- Preparar e explorar dados.
- Treinar e avaliar um modelo de Machine Learning.
- Liberar (cleanup) os recursos utilizados, evitando cobranças desnecessárias.

---

## Pré-Requisitos

Antes de iniciar o tutorial, é importante que você possua:
- Uma conta ativa na plataforma Azure.
- Acesso ao [Azure Portal](https://portal.azure.com) e ao [Azure Machine Learning Studio](https://ml.azure.com).
- Conhecimento básico em Python e conceitos fundamentais de Machine Learning.
- Familiaridade com o uso do Jupyter Notebook ou outra ferramenta similar para executar scripts.

---

## Passo a Passo

### 1. Criação do Workspace
- **Acesso ao Azure:** Entre no Azure Portal e localize o serviço Azure Machine Learning.
- **Criação do Workspace:** Siga as instruções para criar um novo workspace, configurando a região, a assinatura e os demais parâmetros necessários.

### 2. Configuração do Ambiente de Computação
- **Provisionamento de Compute:** Dentro do workspace, crie um recurso de computação (compute cluster ou compute instance) que servirá como ambiente de execução para os scripts e notebooks.
- **Configuração do Ambiente:** Configure as propriedades do compute, como número de nós e tamanho dos VMs.

### 3. Preparação dos Dados e do Projeto
- **Upload dos Dados:** Importe os datasets necessários para o treinamento do modelo.
- **Organização do Projeto:** Estruture seu ambiente de trabalho, contendo scripts, notebooks e demais arquivos do projeto.

### 4. Desenvolvimento e Treinamento do Modelo
- **Execução dos Notebooks:** Utilize os notebooks fornecidos ou crie seus scripts para a preparação dos dados e definição do modelo.
- **Treinamento:** Execute os processos de treinamento e monitore as métricas e logs para avaliar a performance do modelo.
- **Ajustes e Re-treinamento:** Se necessário, ajuste hiperparâmetros e re-treine o modelo até atingir os resultados desejados.

### 5. Avaliação dos Resultados
- **Validação:** Analise as métricas obtidas (como acurácia, precisão, recall, etc.) e valide o modelo.
- **Visualizações:** Utilize gráficos e relatórios para melhor compreensão dos resultados apresentados pelo modelo.

### 6. Deploy (Opcional)
- **Implementação:** Caso o objetivo seja expor o modelo para uso em produção, siga as orientações do tutorial para fazer o deploy via API, disponibilizando-o para teste e consumo.

### 7. Liberação de Recursos
Para evitar custos adicionais após a conclusão do laboratório, é fundamental liberar os recursos provisionados:
- **Desprovisionar Compute:** Delete o compute cluster ou compute instance que foi utilizado.
- **Excluir o Workspace:** Caso não pretenda utilizar novamente o ambiente, remova o workspace criado no Azure Machine Learning.
- **Revisar Recursos no Azure Portal:** Verifique e remova quaisquer outros recursos relacionados (armazenamento, redes, etc.) para garantir que não haja cobranças extras.

---

## Pontos Importantes para Atingir o Resultado Final

- **Planejamento Inicial:** Configure corretamente o workspace e os recursos de compute logo no início para evitar retrabalhos.
- **Documentação e Monitoramento:** Acompanhe as métricas e logs durante o treinamento para identificar rapidamente erros ou possíveis melhorias.
- **Iteratividade:** Não hesite em ajustar e re-treinar o modelo com base nos resultados obtidos, explorando diferentes técnicas e hiperparâmetros.
- **Limpeza de Recursos:** Após a conclusão do laboratório, lembre-se de liberar todos os recursos criados para evitar custos não previstos.

---

## Conclusão

Este tutorial fornece uma visão prática da implementação de um projeto de Machine Learning na plataforma Azure. Ao seguir este passo a passo, você aprenderá desde a criação do ambiente até a avaliação e deploy do modelo, culminando na importância da limpeza dos recursos através do Azure Machine Learning e do Azure Portal.

Sinta-se à vontade para contribuir com melhorias ou compartilhar suas experiências. Bom trabalho e bons estudos!

---
```
