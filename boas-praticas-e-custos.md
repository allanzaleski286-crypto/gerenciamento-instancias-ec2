# Boas Práticas e Controle de Custos na AWS

## 1. Introdução

A utilização de serviços em nuvem exige planejamento, segurança e controle financeiro.

Na AWS, o gerenciamento adequado dos recursos ajuda a evitar desperdícios e manter uma infraestrutura eficiente.

## 2. Boas práticas no gerenciamento de instâncias EC2

Algumas práticas importantes são:

- Utilizar somente os recursos necessários.
- Escolher tipos de instâncias adequados à aplicação.
- Desligar instâncias que não estão sendo utilizadas.
- Monitorar o consumo dos recursos.
- Manter os sistemas operacionais atualizados.
- Realizar backups de dados importantes.
- Aplicar configurações adequadas de segurança.

## 3. Controle de custos

Os serviços da AWS possuem diferentes modelos de cobrança.

No Amazon EC2, os custos podem depender de fatores como:

- Tipo de instância.
- Tempo de execução.
- Região utilizada.
- Armazenamento associado.
- Transferência de dados.
- Recursos adicionais contratados.

## 4. Atenção ao desligamento das instâncias

Parar uma instância EC2 pode interromper a cobrança pelo uso computacional sob demanda, mas isso não significa que todos os custos deixam de existir.

Por exemplo:

- Volumes EBS podem continuar gerando cobranças.
- Snapshots armazenados podem gerar custos.
- Endereços IPv4 públicos podem ter cobrança.
- Outros recursos associados podem continuar ativos.

Por isso, é importante verificar todos os recursos utilizados.

## 5. Ferramentas para acompanhamento financeiro

A AWS disponibiliza ferramentas para ajudar no controle de custos, como:

- AWS Cost Explorer: permite analisar os custos e o consumo.
- AWS Budgets: permite configurar orçamentos e alertas.
- AWS Pricing Calculator: auxilia na estimativa de custos dos serviços.

## 6. Estratégias para evitar desperdícios

1. Identificar recursos que não estão sendo utilizados.
2. Desligar instâncias quando não forem necessárias.
3. Escolher configurações adequadas à demanda.
4. Monitorar os gastos regularmente.
5. Excluir recursos desnecessários com cuidado.
6. Configurar alertas de orçamento.

## 7. Simulação de cenário

Imagine uma empresa que utiliza uma instância EC2 para hospedar um ambiente de testes.

Após finalizar os testes, a equipe decide parar a instância para evitar custos desnecessários de computação.

Entretanto, a equipe também verifica os volumes EBS e outros recursos associados, pois eles podem continuar gerando cobranças.

Essa prática demonstra a importância de acompanhar toda a infraestrutura.

## 8. Conclusão

O controle de custos é uma parte fundamental da computação em nuvem.

O uso consciente dos recursos, o monitoramento financeiro e o planejamento ajudam a manter ambientes eficientes e econômicos.

Neste laboratório, os conceitos foram estudados e documentados sem contratação ou utilização de recursos pagos na AWS.
