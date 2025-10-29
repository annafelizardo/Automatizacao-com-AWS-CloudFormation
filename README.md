# Automatizacao-com-AWS-CloudFormation
Laboratório do projeto Santander Code Girls 2025 - DIO. 


**Automatização com AWS CloudFormation**

Você pode usar o CloudFormation para lançar uma **Amazon Forecast pipeline** e gerar previsões a partir de uma base de dados. Nesse caso, o AWS CloudFormation:
- Disponibiliza o template **Improving Forecast Accuracy with Machine Learning Solution**;
- Disponibiliza o template **NYC Taxi Datasets**;
- Inicia de forma automática o pipeline de previsão de táxis de NYC no ForeCast.

O AWS CloudFormation possui **target time-series**, **related time-series**, e itens **metadata demonstration datasets**. Essa mesma stack de automação pode ser usada posteriormente para gerar previsões com conjuntos de dados próprios. 

**Implantando um AWS CloudFormation modelo para automação do Forecast**

Para implantar o template do CloudFormation usando o conjunto de dados de táxi de NY, você precisa:
1. Aceitar os padrões e escolher **Next**.
2. Fornecer um email para notificações e escolher **Next**.
3. Aceitar os padrões e escolher **Next**.
4. Em **Capabilities**, marque ambas as caixas de seleção para permitir a criação de recursos **AWS IAM** e stacks. Selecione **Create Stack**.

Dessa forma você implementou um template AWS CloudFormation no Forecast. Você pode, posteriormente, limpar esse template e usar seus próprios conjuntos de dados. 



