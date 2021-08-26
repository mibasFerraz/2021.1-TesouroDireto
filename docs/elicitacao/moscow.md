# <center> MosCoW


## Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 20.08.2021 | 0.1 | Criação do documento | Lucas Melo, Dafne, Lucas Lima<br>Dafne Moretti|
| 21.08.2021 | 0.2 | Correção item 18 tabela | Nilvan Peres |
| 25.08.2021 | 0.3 | Adição de links para as técnicas que deram origem aos requisitos | João Pedro Chaves |

## Participantes

* Lucas Melo 
* Dafne Moretti
* Lucas Lima
## Metodologia

<p align="justify">&emsp;
  MoSCoW é  um método que auxilia na determinação de um sistema de prioridades. Essa técnica está ligada às metodologias ágeis e define a importância e importância dos requisitos de um sistema ou projeto.
O nome dessa técnica é dada devido as possíveis classificações de prioridade, sendo elas:
</p>




* Must: tarefas que vão agregar valor ao produto final e são indispensáveis;
* Should: os requisitos que recebem essa prioridade são aqueles que são importantes mas não são vitais para o sistema;
* Could: são requisitos que seriam desejáveis, porém não são estrategicamente essenciais;
* Would/Want/Won't : requisitos menos críticos que possuem menor retorno sobre o investimento quando comparado a outros.


## Resultados

### Proporções de Must, Should, Could e Would
| Prioridade | Quantidade de Requisitos |
| -- | -- |
| Must | 27 |
| Should | 10 |
| Could | 6 |
| Would | 9 |

<p align = "center"><img src="../../assets/moscow.png" width="700">Figura 01 - Gráfico de pizza representando as proporções de requisitos classificados como Must, Should, Could e Would</p><br>

### Lista de requisitos e suas prioridades
|Identificação | Requisito | Técnica | Prioridade |
| -- | -- | -- | -- |
| RF01 | O usuário poderá simular investimento sem fazer login. | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Could |
| RF02 | O usuário deve poder simular um investimento para atingir suas metas.| [Questionário](https://requisitos-de-software.github.io/2021.1-TesouroDireto/questionario/) e [Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/) e [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Should |
| RF03 | O usuário poderá obter informações sobre motivos para investir. | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Would |
| RF04 | O usuário poderá obter informações sobre como investir. | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Must |
| RF05 | O usuário poderá escolher um título para a simulação | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) e [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/)| Could |
| RF06 | O usuário deverá selecionar um tipo de simulação entre as opções: "Quanto quer resgatar no futuro" e "Quanto quer investir hoje"| [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) e [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Would |
| RF07 | O usuário deverá informar o valor que deseja resgatar ao selecionar a opção "Quanto quer resgatar no futuro" | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Would |
| RF08 | O usuário deverá selecionar o como deseja aplicar: "aplicação única" ou "aportes mensais" | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Should ||
| RF09 | O usuário deverá informar o valor do aporte caso selecione "aportes mensais" | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Must |
| RF10 | O usuário deverá informar o valor do aporte e da aplicação mensal após escolher a opção "Quanto quer investir hoje" | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Must |
| RF11 | O usuário poderá ver um gráfico de rentabilidade líquida do investimento. | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Should |
| RF12 | O usuário poderá ver um gráfico de evolução do patrimônio bruto | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Could ||
| RF13 | O usuário poderá ver mais detalhes sobre os gráficos | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Would |
| RF14 | O usuário poderá alterar os parâmetros utilizados para montagem dos gráficos | [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Would |
| RF15 | O usuário poderá selecionar investir após a simulação para que a simulação seja adicionada ao carrinho |  [Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/) | Should |
| RNF16 | Deve ter uma interface fácil e intuitiva, para que qualquer pessoa de qualquer idade consiga realizar investimentos. | [Elicitação de Personas](https://requisitos-de-software.github.io/2021.1-TesouroDireto/personas/) | Must |
| RNF17 | A pessoa física usuária do aplicativo deve poder utilizar o aplicativo dos mais variados lugares, precisando apenas de internet. | [Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/) | Must |
|RF18 | A pessoa física usuária do aplicativo deve ser capaz de comparar os títulos a fim de decidir o melhor título público para sua situação. | [Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/) | Must |
| RF19|  A pessoa física usuária do aplicativo deve visualizar estatisticamente sua rentabilidade líquida. | [Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/) | Could|
| RF20 | A pessoa física usuária do aplicativo deve poder estabelecer sonhos e metas e analisar se está perto ou não de conseguí-las. | [Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/) e [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
| RF21 | O aplicativo deve fornecer diferentes opções de investimentos, para satisfazer diferentes perfis de investidores | [Elicitação de Personas](https://requisitos-de-software.github.io/2021.1-TesouroDireto/personas/) | Must |
| RF22 | O aplicativo deve ter uma sessão para acompanhamento do capital alocado em algum investimento, e da quantia disponível em conta |  [Elicitação de Personas](https://requisitos-de-software.github.io/2021.1-TesouroDireto/personas/) | Must |
| RF23 |O aplicativo deve permitir que o investidor utilize seu capital para comprar titulos públicos | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Must |
| RF24 | O aplicativo deve possuir uma ferramenta, que permite o usuário simular aplicações com diferentes cenários. | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Should |
| RF25 | O aplicativo deveria auxiliar o investidor a informar seu perfil. | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Would |
| RF26 |O aplicativo deveria informar ao usuário(investidor) os tipos de investimento. | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Must |
| RF27 | O aplicativo deve garantir a segurança dos dados do usuário(investidor).  | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) e [Análise de Discurso](https://requisitos-de-software.github.io/2021.1-TesouroDireto/analisediscurso/) | Must |
| RF28 | O aplicativo deve ter algumas funcionalidades tais como: investir,resgatar,simular, visualizar sua posição.  | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Must |
| RF29 | O aplicativo deve auxiliar o investidor a escolher o título. | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Should|
| RF30 | O aplicativo deve permitir a comunicação entre o Banco Central e o Governo. | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/) | Could |
| RNF31 | O aplicativo deve ser simples de usar, para que os usuários utilizem suas funcionalidades.|  [Questionário](https://requisitos-de-software.github.io/2021.1-TesouroDireto/questionario/) e  [Análise de Protocolo](https://requisitos-de-software.github.io/2021.1-TesouroDireto/elicitacao/analise_protocolo/)  | Should |
| RF32 | O usuário deve poder visualizar seu extrato para acompanhar seu rendimento.| [Questionário](https://requisitos-de-software.github.io/2021.1-TesouroDireto/questionario/) e  [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF33  |   O usuário deve poder ver as notificações do app  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Could ||
|  RF34 |  O usuário deve poder se cadastrar com sua corretora  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must 
| RF35|  O usuário deve poder realizar o login  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF36  |  O usuário deve poder ver a senha que digitou  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Should|
|  RF37  |  O usuário deve poder recuperar a sua senha  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF38  |  O usuário deve poder navegar no menu principal  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Should |
|  RF39  |  O usuário deve poder investir em algum título  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF40  |  O usuário deve poder adicionar um ou mais títulos  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF41  |  O usuário deve poder escolher o valor que deseja investir  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF42  |  O usuário deve poder escolher quando deseja realizar a operação  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF43  |  O usuário deve poder revisar seu investimento  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF44  |  O usuário deve poder resgatar seu dinheiro investido  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF45  |  O usuário deve poder escolher qual investimento deseja resgatar  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF46  |  O usuário deve poder escolher o valor que deseja resgatar  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF47  |  O usuário deve poder escolher quando deseja resgatar  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF48  |  O usuário deve poder revisar o seu pedido de resgate  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Must |
|  RF49  |  O usuário deve poder ver quando ele investiu seu dinheiro  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Should |
|  RF50  |  O usuário deve poder dar o nome, meta (quantidade de dinheiro) e selecionar seus títulos  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Would |
|  RF51 |  O usuário deve poder falar com o sac do tesouro direto  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Would |
|  RF52  |  O usuário deve poder ver as informações sobre o app  | [Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/) | Would |
<div align="justify">


[Observação participativa](https://requisitos-de-software.github.io/2021.1-TesouroDireto/observacao_participativa/)


[Introspecção](https://requisitos-de-software.github.io/2021.1-TesouroDireto/introspeccao/)

[Storytelling](https://requisitos-de-software.github.io/2021.1-TesouroDireto/storytelling/)

[[Elicitação de Personas](https://requisitos-de-software.github.io/2021.1-TesouroDireto/personas/)](https://requisitos-de-software.github.io/2021.1-TesouroDireto/personas/)

[Análise de Discurso](https://requisitos-de-software.github.io/2021.1-TesouroDireto/analisediscurso/)

</div><br>


## Referências

> [1] - Método MosCoW. Voitto - BR, 01 ago. 2021. Disponível em <a href=https://www.voitto.com.br/blog/artigo/metodo-moscow target="_blank">https://www.voitto.com.br/blog/artigo/metodo-moscow</a>. Acesso em 20 de ago. 2021
