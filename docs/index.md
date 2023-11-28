<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
**SmartSlice**
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Análise de requisitos funcionais e não-funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de Componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Ciro Campos de Carvalho - 32345275
* Eduardo Hiroyuki Tamaributi - 32331762
* Julia Kovacs Takamura - 32371489
* Luiz Henrique de Sousa Fabiano - 32354924
* Weikai Xia - 32330790


# Descrição do projeto

O demandante Pizza-Express tem perdido 30% da venda para seu conconrrente devido ao problema com a logística da entrega.
-> Entrada da ordem de serviço -> Processamento do pedido->preparação do pedido-> Entrega(30mins)

Com patrocino da empresa Papa-léguas Delivery, o objetivo é : lojas de pizza sem espaço de varejo , o qual deverá ser localizada mais próximo do cliente, receber a ordem da central, processar e entregar a ordem dentro de 10 ou 15 minutos da entrada do pedido.


# Análise de requisitos funcionais e não-funcionais

·       Sistema 1 (central)<br>
Requisito funcionais: Receber a ordem de pedidos; Processar o pedido(analisar localização do cliente), distribuir pedidos para lojas;<br>
Requisito não funcionais: estável; Seguro;<br>
·       Sistema 2 (local)<br>
Requisitos funcionais: receber pedido da central; Suportar comunicação entre loja e Cliente ;<br>
Requisito não funcionais: estável; Seguro;

# Diagrama de casos de uso

![](https://imgur.com/qdl8z3i.png)

# Descrição dos casos de uso

![](https://imgur.com/Wi0OP0s.png)<br>
![](https://imgur.com/9RR1D0w.png)<br>
![](https://imgur.com/0UcTTu4.png)<br>
![](https://imgur.com/b7QWes7.png)

# Diagrama de sequencia

![](https://imgur.com/lr5pfTY.png)

# Diagrama de classes

![](https://imgur.com/HJC0IDg.png)

# Diagrama de Componentes

![](https://imgur.com/S0OILaw.png)

# Decisões de arquitetura

1. Sistema de Software para Atendimento do Pedido e Localização da Fábrica de Pizzas:<br>
a. Central de Pedidos:
Uma aplicação web responsiva para receber pedidos de clientes.
Backend para gerenciar pedidos, processar pagamentos e integrar com o sistema de localização.
Banco de dados para armazenar informações do cliente, histórico de pedidos e preferências.<br>
b. Sistema de Localização:
Uso de API de geolocalização para identificar a localização do cliente em tempo real.
Integração com mapas para determinar a loja mais próxima com base na localização do cliente.

2. Sistema de Software para Suportar Operações da Fábrica de Pizzas:<br>
a. Gestão de Pedidos e Produção:
Um sistema de gestão de pedidos para receber pedidos da central.
Integração com o sistema de produção para iniciar a preparação da pizza assim que o pedido é confirmado.<br>
b. Rastreamento de Inventário:
Sistema para rastrear o inventário de ingredientes em tempo real.
Alertas automáticos para reabastecimento de ingredientes.<br>
c. Integração com Entrega:
Integração com o sistema de entrega para garantir que a pizza esteja pronta quando o entregador chegar.
Rastreamento da localização do entregador para coordenar a entrega.<br>
d. Monitoramento e Análise:
Ferramentas para monitorar o desempenho das operações, tempos de preparação e entrega.
Capacidade de análise de dados para identificar áreas de melhoria.<br>
e. Backup e Recuperação:
Implementação de um sistema de backup regular para garantir a recuperação rápida em caso de falhas no sistema.

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
