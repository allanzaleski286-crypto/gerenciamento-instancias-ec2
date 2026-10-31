# Gerenciamento de Instâncias EC2

## 1. Introdução

O gerenciamento de instâncias EC2 é uma atividade importante dentro da AWS. Ele permite controlar o funcionamento dos servidores virtuais de acordo com a necessidade de cada aplicação.

## 2. Inicialização de uma instância (Start)

A inicialização permite colocar uma instância que está parada em funcionamento.

Quando uma instância passa para o estado Running, ela fica disponível para executar aplicações e serviços.

## 3. Parada de uma instância (Stop)

A parada interrompe temporariamente o funcionamento de uma instância.

A instância permanece disponível na conta AWS e pode ser iniciada novamente.

**Atenção:** o armazenamento EBS continua podendo gerar cobranças mesmo quando a instância está parada.

## 4. Reinicialização (Reboot)

A reinicialização desliga e inicia novamente o sistema operacional da instância.

É semelhante a reiniciar um computador convencional.

## 5. Encerramento definitivo (Terminate)

O encerramento definitivo remove a instância e ela não poderá ser iniciada novamente.

Dependendo das configurações, os volumes de armazenamento associados também poderão ser excluídos.

Essa operação exige atenção, pois pode causar perda de dados.

## 6. Comparação das operações

| Operação | Resultado |
|---|---|
| Start | Inicia a instância |
| Stop | Para temporariamente |
| Reboot | Reinicia a instância |
| Terminate | Encerra definitivamente |

## 7. Boas práticas

- Verificar o estado da instância antes de realizar operações.
- Evitar manter recursos ligados sem necessidade.
- Fazer backups de informações importantes.
- Utilizar permissões adequadas.
- Monitorar os custos dos recursos utilizados.
- Confirmar antes de executar operações definitivas.

## 8. Simulação prática

Para compreender o gerenciamento de instâncias, foi elaborado o seguinte cenário teórico:

1. Uma instância EC2 é criada.
2. A instância passa para o estado Running.
3. O administrador realiza uma operação de Stop.
4. A instância passa para o estado Stopped.
5. Posteriormente, o administrador executa Start.
6. A instância retorna ao estado Running.

Esta simulação demonstra o ciclo básico de gerenciamento de uma instância.

**Observação:** as operações foram estudadas e documentadas teoricamente, sem criação de recursos reais na AWS.

## 9. Conclusão

O gerenciamento correto de instâncias EC2 permite controlar recursos computacionais, melhorar a organização da infraestrutura e evitar custos desnecessários.

Conhecer as diferenças entre Start, Stop, Reboot e Terminate é fundamental para administrar ambientes na nuvem com segurança.
