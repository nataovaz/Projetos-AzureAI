# Resumo do Laboratório: Aprendizado Automatizado de Máquina com Azure Machine Learning

## Introdução
Este laboratório demonstra a utilização do recurso de Aprendizado de Máquina Automatizado (AutoML) no Azure Machine Learning. O objetivo é treinar, avaliar, implantar e testar um modelo de machine learning usando dados históricos de aluguel de bicicletas.

## Duração
O exercício completo é estimado para ser concluído em aproximadamente 30 minutos.

## Etapas do Laboratório

### 1. Configuração do Ambiente
- **Criação de um Workspace de Machine Learning no Azure**:
  - Acesso ao portal do Azure e criação de um recurso de Machine Learning.
  - Seleção de assinatura, grupo de recursos, nome e região para o workspace.
  - Nota sobre contas de armazenamento, cofres de chaves e insights de aplicativos associados.

### 2. Treinamento de Modelo com AutoML
- **Utilização do AutoML para treinar um modelo de previsão**:
  - Criação de um novo trabalho de AutoML com configurações específicas.
  - Escolha do tipo de tarefa como Regressão e uso do conjunto de dados `bike-rentals`.
  - Configuração de métricas, algoritmos permitidos e limites para o treinamento.

### 3. Revisão do Melhor Modelo
- **Análise do modelo mais eficiente treinado pelo AutoML**:
  - Observação das métricas e gráficos de desempenho, como resíduos e valores previstos vs. reais.

### 4. Implantação e Teste do Modelo
- **Implantação do modelo como um serviço web**:
  - Uso de uma Instância de Container do Azure com autenticação.
- **Teste do serviço implantado**:
  - Execução de um teste com dados de entrada específicos e revisão dos resultados preditos.


### Imagens e Validação
![Validacao1](images/AzureML-1.png.png)

![Validacao2](images/AzureML-2.png.png)
