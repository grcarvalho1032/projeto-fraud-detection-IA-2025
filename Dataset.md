O dataset é muito grande para caber no repositório, então coloquei aqui o link para o ele no kaggle.
Link para o Dataset: https://www.kaggle.com/datasets/ealaxi/paysim1
---
## Dataset
Este dataset é uma representação sintética de transações financeiras em um serviço de dinheiro móvel. Ele foi gerado pelo simulador PaySim, que utiliza dados agregados de registros financeiros reais, de um serviço de pagamentos operando em um país africano. O objetivo do dataset é fornecer uma base para estudos de detecção de fraudes em transações digitais.

### Características do Dataset

O conjunto de dados contém transações simuladas ao longo de 30 dias e inclui os seguintes atributos:

- step: Unidade de tempo simulada (1 step = 1 hora).
- type: Tipo de transação (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- amount: Valor da transação.
- nameOrig: Identificador do cliente que iniciou a transação.
- oldbalanceOrg: Saldo inicial do remetente antes da transação.
- newbalanceOrig: Saldo final do remetente após a transação.
- nameDest: Identificador do destinatário da transação.
- oldbalanceDest: Saldo inicial do destinatário antes da transação (não aplicável para comerciantes).
- newbalanceDest: Saldo final do destinatário após a transação (não aplicável para comerciantes).
- isFraud: Indica se a transação é fraudulenta (1 = fraude, 0 = legítima).

O objetivo principal deste dataset é permitir a análises e desenvolvimento de modelos de machine learning para detectar fraudes em transações financeiras.

### Referênia
Este dataset foi gerado como parte do projeto de pesquisa "Scalable resource-efficient systems for big data analytics", financiado pela Knowledge Foundation (Suécia, grant: 20140032).

Citação acadêmica:

E. A. Lopez-Rojas, A. Elmir, and S. Axelsson. "PaySim: A financial mobile money simulator for fraud detection". In: The 28th European Modeling and Simulation Symposium-EMSS, Larnaca, Cyprus. 2016.

