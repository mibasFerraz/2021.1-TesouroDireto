# <center> Casos de Uso


### Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 26.08.2021 | 0.1 | Criação do documento | João Pedro Chaves |
| 26.08.2021 | 0.2 | Adição dos Casos de Uso | João Pedro Chaves |
### Participantes

* João Pedro Chaves


### Metodologia
<div align="justify"> Explicar como foi feito o doc.
</div><br>

### Resultados
<div align="justify">

</div><br>

#### Conhecer o Tesouro Direto
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário escolhe conhecer o Tesouro Direto | -- |
| Normal | 2 | Usuário do Aplicativo | Usuário escolhe obter informações sobre motivos para investir | RF03 |
| Normal | 3 | Usuário do Aplicativo | O aplicativo mostra informações e motivos para o usuário investir | -- |
| Alternativo | 2a | Usuário do Aplicativo | Usuário escolhe obter informações sobre como investir | RF04 |

#### Simular seu Investimento 
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário escolhe simular investimento sem fazer login. | RF01 |
| Normal | 2 | Usuário do Aplicativo | Usuário escolhe a opção "não sei que título escolher" | -- |
| Normal | 3 | Usuário do Aplicativo | Usuário seleciona qual o sonho dele | RF20 |
| Normal | 4 | Usuário do Aplicativo | Usuário seleciona em quanto tempo quer realizar seu sonho | RF02 |
| Normal | 5 | Usuário do Aplicativo | Usuário seleciona a preferência "Saber quanto vou ganhar" | -- |
| Normal | 6 | Usuário do Aplicativo | Apresentar os títulos mais indicados para o usuário | R26, R29 |
| Normal | 7 | Usuário do Aplicativo | Usuário seleciona simular investimento em um dos títulos apresentados | -- |
| Normal | 8 | Usuário do Aplicativo | Usuário seleciona opção de simulação: "Quanto quer resgatar no futuro" | RF06 |
| Normal | 9 | Usuário do Aplicativo | Usuário informa o valor que deseja resgatar  | RF07 |
| Normal | 10 | Usuário do Aplicativo | Usuário seleciona a opção de como aplicar: "Aportes mensais" | RF08 |
| Normal | 11 | Usuário do Aplicativo | Usuário informa valor dos aportes mensais | RF09 |
| Normal | 12 | Usuário do Aplicativo | Aplicativo apresenta gráfico de rentabilidade líquida do investimento | RF11 |
| Normal | 13 | Usuário do Aplicativo | Aplicativo apresenta gráfico de evolução do patrimônio bruto | RF12 |
| Normal | 14 | Usuário do Aplicativo | Usuário seleciona ver mais detalhes sobre os gráficos | RF13 |
| Normal | 15 | Usuário do Aplicativo | Usuário seleciona alterar parâmetros dos gráficos | RF14, RF24 |
| Normal | 16 | Usuário do Aplicativo | Usuário seleciona investir após a simulação | RF15 |
| Normal | 17 | Usuário do Aplicativo | Simulação é adicionada ao carrinho | RF15 |
| Alternativo | 2a | Usuário do Aplicativo | Usuário escolhe título para simulação | RF05 |
| Alternativo | 5a | Usuário do Aplicativo | Usuário seleciona a preferência "Preservar poder de compra" | -- |
| Alternativo | 8a | Usuário do Aplicativo | Usuário seleciona opção de simulação: "Quanto quer investir hoje" e informa o valor do aporte a aplicação mensal| RF06, RF10 |
| Alternativo | 10a | Usuário do Aplicativo | Usuário seleciona a opção de como aplicar: "Aportes mensais" | RF08 |

#### Resgatar Investimento
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário faz login com CPF e senha | RF35, RF36 |
| Normal | 2 | Usuário do Aplicativo | Usuário escolhe resgatar investimento | RF44 |
| Normal | 3 | Usuário do Aplicativo | Usuário escolhe qual investimento resgatar | RF45 |
| Normal | 4 | Usuário do Aplicativo | Usuário escolhe qual valor deseja resgatar | RF46 |
| Normal | 5 | Usuário do Aplicativo | Usuário informa quando deseja resgatar | RF47 |
| Normal | 6 | Usuário do Aplicativo | Usuário revisa e confirma seu pedido de resgate | RF48 |
| Normal | 7 | Usuário do Aplicativo | Usuário recebe o valor do resgate | RF30 |

#### Fazer Investimento 
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário faz login com CPF e senha | RF35, RF36 |
| Normal | 2 | Usuário do Aplicativo | Usuário navega pelo menu principal e seleciona investir | RF38, RF28 |
| Normal | 3 | Usuário do Aplicativo | Usuário acessa diferentes opções de investimentos e os compara | RF21, RF18 |
| Normal | 4 | Usuário do Aplicativo | Usuário escolhe um investimento | -- |
| Normal | 5 | Usuário do Aplicativo | Usuário informa o valor que deseja investir | RF39 |
| Normal | 6 | Usuário do Aplicativo | Usuário informa quando deseja que a operação ocorra | RF42, RF23 |
| Normal | 7 | Usuário do Aplicativo | Usuário adiciona mais títulos aos investimentos | RF40 |
| Alternativo | 7a | Usuário do Aplicativo | Usuário revisa seus investimentos | RF43 |

#### Acompanhar Investimento 
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário faz login com CPF e senha | RF35, RF36 |
| Normal | 2 | Usuário do Aplicativo | Usuário seleciona "Meu Tesouro - Posição" | -- |
| Normal | 3 | Usuário do Aplicativo | Usuário acompanha rendimento do seu investimento pelo extrato | RF32, RF22 |
| Alternativo | 3a | Usuário do Aplicativo | Usuário altera nome de um investimento | RF50 |
| Alternativo | 3b | Usuário do Aplicativo | Usuário acompanha sua rentabilidade líquida | RF19 |
| Alternativo | 3c | Usuário do Aplicativo | Usuário consulta quando foram feitos seus investimentos | RF49 |

#### Cadastrar usuário
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário seleciona a opção de se cadastrar no aplicativo | -- |
| Normal | 2 | Usuário do Aplicativo | Usuário tem acesso a uma lista de corretoras e bancos para entrar em contato e solicitar o cadastro no aplicativo | RF34 |
| Normal | 3 | Usuário do Aplicativo | Usuário recebe uma senha de acesso e deve trocar a senha | -- |

#### Simular Investimento 
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo |  |  |
| Normal | 2 | Usuário do Aplicativo |  |  |
| Normal | 3 | Usuário do Aplicativo |  |  |
| Normal | 4 | Usuário do Aplicativo |  |  |
| Normal | 5 | Usuário do Aplicativo |  |  |
| Normal | 6 | Usuário do Aplicativo |  |  |
| Normal | 7 | Usuário do Aplicativo |  |  |
| Normal | 8 | Usuário do Aplicativo |  |  |
| Normal | 9 | Usuário do Aplicativo |  |  |
| Normal | 10 | Usuário do Aplicativo |  |  |


|Identificação | Requisito | Técnica | Prioridade |
| -- | -- | -- | -- |
| RF25 | O aplicativo deveria auxiliar o investidor a informar seu perfil. | Análise de Protocolo | Would |
|  RF33  |   O usuário deve poder ver as notificações do app  | Observação participativa | Could |
|  RF37  |  O usuário deve poder recuperar a sua senha  | Observação participativa  | Must |
|  RF51 |  O usuário deve poder falar com o sac do tesouro direto  | Observação participativa  | Would |
|  RF52  |  O usuário deve poder ver as informações sobre o app  | Observação participativa | Would |

## Referências

> REFERENCIAS