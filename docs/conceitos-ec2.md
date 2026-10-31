# Conceitos fundamentais do Amazon EC2

## 1. O que é Amazon EC2?

O Amazon Elastic Compute Cloud (Amazon EC2) é um serviço da Amazon Web Services (AWS) que permite criar e utilizar servidores virtuais na nuvem.

Esses servidores são chamados de instâncias EC2.

Com esse serviço, podemos executar aplicações, hospedar sites, armazenar e processar dados e realizar diversas tarefas computacionais.

## 2. O que é uma instância EC2?

Uma instância EC2 é um servidor virtual que funciona na infraestrutura da AWS.

Podemos escolher características como:

- Sistema operacional.
- Quantidade de memória RAM.
- Capacidade de processamento.
- Armazenamento.
- Configurações de rede.

## 3. AMI (Amazon Machine Image)

AMI é uma imagem utilizada como modelo para iniciar uma instância EC2.

Ela contém as informações necessárias para configurar o sistema operacional e outros componentes da máquina virtual.

## 4. Tipos de instâncias

A AWS oferece diferentes famílias de instâncias, cada uma adequada a determinadas necessidades.

Exemplos:

- Uso geral: equilíbrio entre processamento, memória e rede.
- Otimizadas para computação: maior capacidade de processamento.
- Otimizadas para memória: aplicações que precisam de muita RAM.
- Otimizadas para armazenamento: aplicações com grande necessidade de acesso a dados.

## 5. Par de chaves (Key Pair)

O Key Pair é utilizado para permitir autenticação segura no acesso às instâncias EC2.

Ele possui uma chave pública e uma chave privada.

A chave privada deve ser protegida e nunca compartilhada.

## 6. Security Groups

Security Groups funcionam como firewalls virtuais.

Eles controlam o tráfego de entrada e saída das instâncias, permitindo configurar quais conexões podem ser realizadas.

## 7. Estados de uma instância

Os principais estados de uma instância EC2 são:

- Pending: instância sendo iniciada.
- Running: instância em execução.
- Stopping: instância sendo desligada.
- Stopped: instância desligada.
- Shutting-down: instância sendo encerrada definitivamente.
- Terminated: instância encerrada.

## 8. Conclusão

O Amazon EC2 é um dos principais serviços de computação em nuvem da AWS.

Compreender seus conceitos fundamentais é essencial para aprender a criar, configurar, gerenciar e proteger servidores virtuais na nuvem.

Este conteúdo foi desenvolvido como parte do laboratório prático de gerenciamento de instâncias EC2 da DIO.
