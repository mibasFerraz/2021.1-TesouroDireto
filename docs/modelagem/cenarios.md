# <center> Cenários


### Histórico de Versão<br>

| Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 25.08.2021 | 0.1 | Criação do documento | Peniel Zannoukou |
| 27.08.2021 | 0.2 | Correção sugeridas no Pull Request| Peniel Zannoukou|

## Participantes

* Peniel Zannoukou

<br><br>

## Resumo
<div align="justify">&emsp;&emsp; Um cenário nada mais é do que uma história curta ou uma descrição de como um evento (ou eventos futuros) pode impactar as operações de uma empresa. Cenários são criados tanto para o ambiente interno quanto para o externo (ou seja, para todos os riscos corporativos que impactam uma organização).Os cenários são exemplos da vida real em que o sistema é ou será utilizado.
</div>
<div align="justify">&emsp;&emsp; Os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações do usuário com o sistema. Cada cenário cobre um pequeno número de interações possíveis.
</div>
<div align="justify">&emsp;&emsp; Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em variados níveis de detalhamento sobre o sistema. O objetivo desse documento é registrar todos os cenários criados.
</div>
<br><br>

</div><br>


### Metodologia
<div align="justify">&emsp;&emsp; Ele descreve uma situação de uso do sistema. Utilizaremos a tabela a seguir como modelo para os cenários.
Inclui informações como Nome do Cenário, Ator(es), Pré-condição, Fluxo normal, Fluxos alternativos e Pós-condição. Também é o espaço real ou virtual.
</div><br>

| Título | Título do Cenário |
| -- | -- |
| Objetivo | Objetivo/meta do cenarios |
| Contexto | pré-condição:<br>pós-condição: |
| Atore | Atores envolvidos |
| Recursos | Recursos envolvidos |
| Episódios | Detalhes do cenários |
| Restrições | Descrição da retrição | 
| Exceção | Descrição da exceção |
<br><br>

## CENÁRIOS
### C01 - Cadastrar usuário utilizando email
| Título | Cadastrar usuário utilizando email |
| -- | -- |
| Objetivo | Criar perfil para o usuário no Tesouro Direto utilizando email |
| Contexto | pré-condição: Possuir email válido<br>pós-condição: É criado um perfil para o novo usuário |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário não cadastrado acessa o aplicativo do Tesouro Direto<br>2. O usuário não cadastrado seleciona seu objetivo no aplicativo (Simular,Investir...)<br>3. O usuário não cadastrado deverá informa seu antecedência criminal.<br>4. O usuário não cadastrado seleciona sua corretora<br>5. O usuário não cadastrado seleciona a linguagem do app<br>6. O usuário não cadastrado insere nome, email e senha e seleciona o botão "Create user"<br>7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C02 - Cadastrar usuário utilizando Google
| Título | Cadastrar usuário utilizando Google |
| -- | -- |
| Objetivo | Criar perfil para o usuário no Tesouro Direto utilizando Google |
| Contexto | pré-condição: Possuir email válido<br>pós-condição: É criado um perfil para o novo usuário |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário não cadastrado acessa o aplicativo do Tesouro Direto<br>2. O usuário não cadastrado seleciona seu objetivo no aplicativo (Simular,Investir...)<br>3. O usuário não cadastrado deverá informa seu antecedência criminal.<br>4. O usuário não cadastrado seleciona sua corretora<br>5. O usuário não cadastrado seleciona a linguagem do app<br>6. O usuário não cadastrado insere nome, email e senha e seleciona o botão "Create user"<br>7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C03 - Modificar Nome
| Título | Modificar Nome |
| -- | -- |
| Objetivo | Modificar o nome dentro do app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Nome alterado |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as configurações da conta<br>3. O usuário seleciona o campo nome e faz a alteração<br>4. O usuário salva a alteração ao clicar no botão "Save Changes" |
| Restrições | Nomes que são maiores que o tamanho configurado | 
| Exceção | O usuário fechar o aplicativo antes de terminar a ação<br>A internet parar de funcionar no meio da ação |
<br><br>

### C04 - Excluir conta
| Título | Excluir conta |
| -- | -- |
| Objetivo | Excluir a conta cadastrada no app |
| Contexto | pré-condição:Usuário logado no Tesouro Direto<br>pós-condição:Conta excluída e usuário redirecionado para a tela inicial |
| Atore | Usuário |
| Recursos | Acesso à internet |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as configurações da conta<br>3. O usuário seleciona o botão de deletar conta<br>4. O usuário confirma o email<br>5. O usuário seleciona novamente o botão para confirmar |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C05 - Visualizar funcionalidade
| Título | Visualizar funcionalidade |
| -- | -- |
| Objetivo | Poder ver as opções que se encontra no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ver opções das funcionalidades |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções da conta<br>3. O usuário seleciona o botão de funcionalides<br>4. O usuário clicar<br>5. O usuário verá as funcionalidades |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C06 -  Escolher Simular
| Título |  Escolher Simular |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ver opções de simulação |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de simular<br>4. O usuário clicar<br>5. O usuário verá como fazer a simulação |
| Restrições | - | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C07 - Escolher Invesrir
| Título | Escolher Invesrir |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app por exemplo investir |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ver nas funcionalidade o ponto de investir. |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de funcionalidade<br>4. O usuário clicar no botão investir<br>5. O usuário opções de investimento<br>6. O usuário verá como fazer seu investimento |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C08 - Escolher Resgatar
| Título | Escolher Resgatar |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ver nas funcionalidade o ponto de resgatar. |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa sua plataforma de investimentos.<br>2. O usuário acessa as opções do app<br>3. Verifique quais títulos do Tesouro Direto estão sob a sua custódia e os valores equivalentes<br>4. O usuário seleciona o botão de funcionalidade<br>5. O usuário clicar no botão resgatar<br>6. Agora o usuário tem a opção de resgatar o valor integral ou uma parte dele<br>7. O usuário efetuará o resgate imformando seus dados cadastrado no sistema. |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C09 - Escolher Título
| Título | Escolher Título |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ir nas funcionalidades e clicar no ponto de investir. |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios |  1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de funcionalidade<br>4. O usuário clicar no botão título.<br>5. O usuário poderá escolher seu título entre as opções disponível. |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C10 - Escolher Corretoras ou Banco
| Título | Escolher Corretoras ou Banco |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ir nas funcionalidades e clicar no ponto de investir. |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o app Tesouro Direto Já sabendo sua corretos ou banco<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de funcionalidade<br>4. O usuário clicar no botão da opção que deseja realizar.<br>5. O usuário escolher corretora. |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C11 -  Vizualizar Posição
| Título |  Vizualizar Posição |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ir nas funcionalidades |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de funcionalidade<br>4. O usuário clicar no botão posição<br>5. O usuário vizualizar sua posição. |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C12 - Visualizar Saldo Investimento
| Título | Visualizar Saldo Investimento |
| -- | -- |
| Objetivo | Poder ver dentre as opções o que deseja no app |
| Contexto | pré-condição: Usuário logado no Tesouro Direto<br>pós-condição: Ir nas funcionalidades e clicar no ponto de investir. |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios | 1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa as opções do app<br>3. O usuário seleciona o botão de funcionalidade<br>4. O usuário clicar no botão posição<br>5. O usuário clicar depois em vizualizar saldo investimento.<br>6. Assim usuário poderá vizualizar saldo. |
| Restrições | Fluxo intuitivo | 
| Exceção | Email inválido<br>Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

### C13 - Alterar/Escolher a linguagem do app
| Título | Alterar/Escolher a linguagem do app |
| -- | -- |
| Objetivo | O usuário alterara linguagem do app(Inglês, francês, espanhol,etc) |
| Contexto | pré-condição: Usuário logado<br>pós-condição: Ir nas funcionalidades e clicar em linguagem |
| Atore | Usuário |
| Recursos | Acesso à internet<br>App intalado<br>Acesso ao site |
| Episódios |  1. O usuário acessa o Tesouro Direto<br>2. O usuário acessa a aba de configurações do App<br>3. O usuário seleciona a configuração desejada<br>4. O usuário seleciona a linguagem desejada. |
| Restrições | Fluxo intuitivo | 
| Exceção | Usuário fechar aplicativo antes de terminar a ação<br>Internet parar de funcionar durante a ação |
<br><br>

## Referências
<div align="justify">&emsp;&emsp; Os seguintes documentos de Cenarios serviram como referência durante a elaboração desse documento:
</div><br>

> SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;<br><br>
> BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.<br><br>
> <a href="https://requisitos-de-software.github.io/2020.1-iFut/modelagem/cenarios/cenariosTotais/">Documento do cenario do grupo iFut</a>