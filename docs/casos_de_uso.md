# <center> Casos de Uso


## Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 26.08.2021 | 0.1 | Criação do documento | João Pedro Chaves |
| 26.08.2021 | 0.2 | Adição dos Casos de Uso | João Pedro Chaves |
| 27.08.2021 | 0.3 | Adição da Metodologia | João Pedro Chaves |

## Participantes

* João Pedro Chaves


## Metodologia
<div align="justify">&emsp;&emsp; Casos de Uso são documentos textuais escritos do ponto de vista de um ator que tem a necessidade ou desejo de utilizar o sistema com um objetivo. As ações dos atores são divididos em passos, que podem ser divididos em dois fluxos: normal e extensões/alternativo. O fluxo normal é composto pelos passos necessários para alcançar o sucesso da operação, já o fluxo alternativo é composto pelas alternativas de execução e erros.(Valente, 2020) 
</div>
<div align="justify">&emsp;&emsp; É necessário que o Caso de Uso tenha um título composto por um verbo no infinitivo como primeira palavra e que o documento seja escrito em linguagem simples e direta para que o entendimento sobre o documento seja facilitado.(Valente, 2020) 
</div>

## Resultados
<div align="justify"> Os Casos de Uso produzidos foram os seguintes:
</div>





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

#### Cadastrar usuário
| Fluxo | Passo | Ator | Ação | RF |
| -- | -- | -- | -- | -- |
| Normal | 1 | Usuário do Aplicativo | Usuário seleciona a opção de se cadastrar no aplicativo | -- |
| Normal | 2 | Usuário do Aplicativo | Usuário tem acesso a uma lista de corretoras e bancos para entrar em contato e solicitar o cadastro no aplicativo | RF34 |
| Normal | 3 | Usuário do Aplicativo | Usuário recebe uma senha de acesso e deve trocar a senha | -- |

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

## Referências

> VALENTE, Marco Túlio. **Engenharia de Software Moderna**: Princípios e Práticas para Desenvolvimento de Software com Produtividade, 2020.