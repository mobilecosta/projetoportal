# projetoportal
Projeto SINAF - Integração Portal

# Sistema interno faz o orçamento

# CRIAR - Portal de Vendas para recepção do orçamento

# CRIAR - Preparação de docto e transmissão

Se o cliente não for da seguradora, fazemos um orçamento e passamos para o cliente aprovar.
O cliente, segurado ou não, aprovando o orçamento. Hoje, abrimos o Protheus e preenchemos o pedido de venda para que desse pedido seja gerada uma RPS e posteriormente o envio da RPS para a prefeitura gerando a NFSE

O que preciso é que essa parte manual, realizada pela equipe de atendimento ao cliente, seja automatizada e que ele não precise entrar no Protheus para gerar e imprimir a RPS.

Sequencia

## 1 - Api para receber os dados do pedido de venda
## 2 - Job para processar a tabela, e gerar o pedido de venda
## 3 - Criar um JOB, que vai ler os pedidos de venda gerado e gerar o docto de saida
## 4 - CRiar um JOB que vai processar os doctos de saida gerados na etapa 3, e transmitir para a prefeitura
## 5 - Notificar o sistema de origem
