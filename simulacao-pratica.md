# Laboratório Prático — Simulação de Gerenciamento EC2

## 1. Objetivo

Este laboratório tem como objetivo demonstrar o funcionamento do ciclo de vida de uma instância Amazon EC2 por meio de um cenário simulado.

A atividade permite compreender as principais operações de gerenciamento sem precisar criar recursos reais na AWS.

## 2. Cenário proposto

Imagine que uma empresa precisa de um servidor virtual para hospedar uma aplicação web.

O administrador de infraestrutura será responsável por acompanhar o funcionamento desse servidor e executar operações de gerenciamento.

## 3. Configuração hipotética da instância

| Configuração | Valor |
|---|---|
| Nome | servidor-web-teste |
| Serviço | Amazon EC2 |
| Sistema operacional | Amazon Linux |
| Tipo | t3.micro |
| Estado inicial | Running |
| Finalidade | Hospedagem de aplicação web |

**Observação:** os valores acima representam um cenário hipotético de estudo, não uma instância criada na AWS.

## 4. Etapas da simulação

### Etapa 1 — Inicialização

O administrador inicia a instância.

Estado esperado: Running.

### Etapa 2 — Verificação

O administrador verifica se a instância está em execução e disponível.

### Etapa 3 — Parada

Após finalizar os testes, o administrador executa a operação Stop.

Estado esperado: Stopped.

### Etapa 4 — Reinicialização da atividade

Quando necessário, o administrador executa Start.

Estado esperado: Running.

### Etapa 5 — Encerramento definitivo

Ao finalizar o uso do ambiente, o administrador pode executar Terminate, após verificar se não existem dados importantes que precisam ser preservados.

Estado esperado: Terminated.

## 5. Resultado esperado

A simulação demonstra como administrar uma instância EC2 durante diferentes momentos do seu ciclo de vida.

As operações permitem controlar o funcionamento dos servidores virtuais e compreender a importância de cada estado.

## 6. Aprendizados

Durante esta atividade foram estudados:

- Inicialização de instâncias.
- Parada temporária.
- Reinicialização.
- Encerramento definitivo.
- Estados de funcionamento.
- Cuidados com armazenamento e custos.

## 7. Evidência da atividade

A atividade foi realizada como simulação teórica e documentada no GitHub.

Não foram criadas instâncias reais ou utilizados recursos pagos da AWS.

## 8. Conclusão

O laboratório permitiu compreender as principais operações de gerenciamento do Amazon EC2 e a importância de administrar corretamente os recursos de computação em nuvem.
