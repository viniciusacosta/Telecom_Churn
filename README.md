# Telecom_Churn

Este repositório trata-se de um projeto de machine learning para prever quais clientes irão cancelar suas assinaturas com uma empresa de telecomunicações.

## **Introdução**

A taxa de Churn, é a taxa na qual os clientes param de fazer negócios com uma empresa. É mais comumente expresso como a porcentagem de assinantes de serviços que descontinuam suas assinaturas dentro de um determinado período de tempo. É também a taxa na qual os funcionários deixam seus empregos dentro de um determinado período. Para uma empresa expandir sua clientela, sua taxa de crescimento (medida pelo número de novos clientes) deve exceder sua taxa de churn.

Uma alta taxa de churn pode afetar negativamente os lucros e impedir o crescimento de uma empresa. A taxa de churn é um fator importantissímo no setor de telecomunicações. Visto que, por conta da competição entre as empresas, é bastante cômodo para os clientes a transferência de um fornecedor para outro.

A taxa de cancelamento não inclui apenas quando os clientes mudam de operadora, mas também quando os clientes simplismente encerram o serviço. Essa medida é mais valiosa em negócios baseados em assinantes, nos quais as taxas de assinatura compreendem a maior parte das receitas. O que é considerado uma taxa de churn boa ou ruim pode variar de setor para setor

Prever este tipo de comportamento é vital para empresas de telecomunicações possam manter seus clientes. Tendo em vista o fato de ser muito mais custoso conseguir novos usuários do que manter os antigos. Por este motivo, grandes corporações visam cada vez mais novos métodos de prever este tipo de comportamento.

## **Objetivo**
O objetivo deste projeto é utilizar a linguagem Python, para criar um modelo de aprendizagem de máquina que possa prever se um cliente irá ou não cancelar seu plano em uma Operadora de Telecomunicações, a partir de características como: 
  - Informações demógraficas.
  - Informações das contas.
  - Informações dos serviços contratados.

Este tipo de estudo/projeto oferece a empresa a capacidade de basear suas decisões e planejamento estratégico a partir de dados, com o intuito de diminuir as taxas de Churn, e consequentemente melhorarando a satisfação dos clientes e as receitas da empresa.

## **Dataset**

O dataset usado neste projeto está disponível na plataforma do Kaggle: 

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Com 19 colunas de variáveis independentes que indicam as características de clientes de uma empresa fictícia de telecomunicações. A coluna **Churn** indica se o cliente finalizou ou não suas relações com a empresa a no mínimo um mês. A classe **No** inclue os clientes no qual continuam utilizando os serviços da companhia no último mês, já a classe **Yes** contém os clientes que decidiram finalizar suas relaçoes com a empresa.

Cada linha do dataset representa um cliente, sendo cada coluna as informações sobre este cliente.

**As features deste dataset aprensentam informações sobre:**

- **Serviços para os quais cada cliente se inscreveu:**
  - PhoneService - Possui serviço de telefonia? (Yes, No)
  - MultipleLines - Possui múltiplas linhas? (No phone service, No, Yes)
  - InternetServices - Possui serviço de internet? (DSL, Fiber optic, No)
  - OnlineSecurity - Possui serviço de segurança online? (No internet service, No, Yes)
  - OnlineBackup - Possui serviço de backup online? (No internet service, No, Yes)
  - DeviceProtection - Possui serviço de proteção para seu aparelho? (No internet service, No, Yes)
  - TechSupport - Possui serviço técnico? (No internet service, No, Yes)
  - StreamingTV - Possui serviço de Streaming na TV? (No internet service, No, Yes)
  - StreamingMovies - Possui serviço de Streaming de filmes? (No internet service, No, Yes)

- **Informações da conta do cliente – há quanto tempo eles são clientes:**
  - Tenure - Quantidade de meses no qual o cliente permaneceu com a empresa (Variável Númerica)
  - Contract - Tipo de contrato do cliente (Month-to-Month, One year, Two year).
  - PaperlessBilling - Cliente recebe sua fatura online? (Yes, No)
  - PaymentMethod - Metódo de pagamento (Electronic check, Mailed check, Bank transfer (automatic), Credit Card (automatic)).
  - MontlyCharges - Valor cobrado mensalmente (Variável Númerica).
  - TotalCharges: Valor total cobrado (Variável Númerica)

- **Informaçoes demográficas sobre os clientes:**
  - Gender - Sexo do cliente (Female, Male)
  - SeniorCitizen - O cliente é idoso? ( 0, 1)
  - Partner - Possui parceiros? (Yes, No) 
  - Dependents - Possui dependentes? (Yes, No)


- **Clientes que encerraram seus contratos a pelo menos um mês:**
  - Churn - O cliente encerrou sua conta? (Yes, No)

