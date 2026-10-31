# Segurança de Instâncias EC2 na AWS

## 1. Introdução

A segurança é fundamental para proteger instâncias Amazon EC2 contra acessos não autorizados.

## 2. Key Pair

O Key Pair é utilizado na autenticação de acesso às instâncias.

É composto por:
- Chave pública.
- Chave privada.

A chave privada deve ser mantida em segurança e nunca compartilhada.

## 3. Security Groups

Security Groups são firewalls virtuais que controlam o tráfego de entrada e saída das instâncias.

## 4. Principais portas

| Porta | Serviço |
|---|---|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 3389 | RDP |

## 5. Princípio do menor privilégio

Cada usuário ou serviço deve possuir somente as permissões necessárias para realizar suas atividades.

## 6. Boas práticas

- Proteger chaves privadas.
- Restringir endereços IP de acesso.
- Liberar somente portas necessárias.
- Manter sistemas atualizados.
- Monitorar acessos.
- Utilizar permissões adequadas no IAM.

## 7. Conclusão

O uso correto de Key Pairs, Security Groups e permissões contribui para manter as instâncias EC2 protegidas.
