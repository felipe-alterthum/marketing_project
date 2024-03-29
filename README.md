**Descrição do projeto**

Você se saiu muito bem no curso do TripleTen e recebeu uma oferta de estágio no departamento analítico da Y.Afisha. Sua primeira tarefa é ajudar a empresa a otimizar suas despesas com marketing.

Você tem:
1) Logs do servidor com dados sobre os acessos a Y.Afisha de janeiro de 2017 até dezembro de 2018
2) Arquivo de despejo com todos os pedidos feitos durante o período
3) Estatísticas de despesas com marketing

Você vai analisar:

- Como as pessoas usam o produto
- Quando elas começam a comprar
- Quanto dinheiro cada cliente traz para a empresa
- Quando as despesas serão cobertas

Instruções para completar o projeto:

Passo 1. Carregue os dados e prepare-os para a análise
Armazene os dados sobre os acessos, pedidos e despesas em variáveis. Otimize os dados para a análise. Certifique-se de que cada coluna contém o tipo correto de dados.
Caminhos de arquivo:
/visits_log_us.csv
/orders_log_us.csv
/costs_us.csv

Passo 2. Faça relatórios e calcule as métricas:
2.1) Produto
 
Quantas pessoas usam-no cada dia, semana e mês?
Quantas sessões ocorrem por dia? (um usuário pode realizar várias sessões).
Que comprimento tem cada sessão?
Com que frequência os usuários voltam?

2.2) Vendas
 
Quando as pessoas começam a comprar? (Na análise de KPIs, nós geralmente estamos interessados em saber o período de tempo entre o registro e a conversão - quando o usuário se torna um cliente. Por exemplo, se o registro e a primeira compra de um usuário ocorrem no mesmo dia, ele pode encaixar na categoria de Conversão 0d. Se a compra é realizada no dia seguinte, isso será a Conversão 1d. Você pode usar qualquer abordagem que permita comparar as conversões de diferentes coortes, para que você possa determinar qual coorte ou canal de marketing tem a maior eficiência)
Quantos pedidos os clientes fazem durante um determinado período de tempo?
Qual é o volume médio de uma compra?
Quanto dinheiro eles trazem para a empresa (LTV)?

2.3) Marketing
 
Quanto dinheiro foi gasto? No total/por origem/ao longo do tempo
Quanto custou a aquisição de clientes para cada origem?
Os investimentos valeram a pena? (ROI)
Construa gráficos para ver como essas métricas diferem para vários dispositivos e diferentes origens de anúncios e como elas mudam com o tempo. 
Passo 3. Escreva uma conclusão: recomende aos especialistas de marketing quanto dinheiro e onde seria melhor investir.
Quais origens/plataformas você recomendaria? Fundamente sua escolha: em quais métricas você se concentrou? Por quê? Que conclusões você tirou ao encontrar os valores das métricas?

**Descrição dos dados**

A tabela visits (os logs do servidor com dados sobre os acessos ao site):
Uid — identificador unívoco do usuário
Device — dispositivo do usuário
Start Ts — data e hora do início da sessão
End Ts — data e hora do final da sessão
Source Id — identificador da origem do anúncio através do qual o usuário chegou
Todas as datas nesta tabela estão no formato YYYY-MM-DD.

A tabela orders (dados sobre os pedidos):
Uid — identificador unívoco do usuário que faz um pedido
Buy Ts — data e hora do pedido
Revenue — a receita da Y.Afisha com o pedido

A tabela costs (dados sobre as despesas com marketing):
source_id — identificador da origem de anúncio
dt — data
costs — despesas com esta origem de anúncio neste dia
Como meu projeto será avaliado?
Seu projeto será avaliado com base nos seguintes critérios. Leia-os cuidadosamente antes de iniciar o projeto.
