# Cenários
<div class="line"></div>

## Histórico de Versão

<table class="table table-striped border">
    <thead>
        <th>Data</th> 
        <th>Versão </th> 
        <th>Descrição</th> 
        <th>Autor(es)</th>
    </thead>
    <tbody>
        <tr>
            <td> 25.08.2021 </td>
            <td>  0.1   </td>
            <td> Criação do documento</td>
            <td> Peniel Zannoukou </td>
        </tr>
    </tbody>
</table>
<br>

## Resumo

Um cenário nada mais é do que uma história curta ou uma descrição de como um evento (ou eventos futuros) pode impactar as operações de uma empresa. Cenários são criados tanto para o ambiente interno quanto para o externo (ou seja, para todos os riscos corporativos que impactam uma organização).Os cenários são exemplos da vida real em que o sistema é ou será utilizado. Os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações do usuário com o sistema. Cada cenário cobre um pequeno número de interações possíveis. Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em variados níveis de detalhamento sobre o sistema. O objetivo desse documento é registrar todos os cenários criados.

## Metodologia

Ele descreve uma situação de uso do sistema. Utilizaremos a tabela a seguir como modelo para os cenários.
Inclui informações como Nome do Cenário, Ator(es), Pré-condição, Fluxo normal, Fluxos alternativos e Pós-condição. Também é o espaço real ou virtual.

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Título do Cenário</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Objetivo/meta do cenarios</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:
                pós-condição:
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Atores envolvidos</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Recursos envolvidos</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>Detalhes do cenários</td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Descrição da retrição</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>Descrição da exceção</td>
        </tr>
    </tbody>
</table>
<br>

# CENÁRIOS

## C01 - Cadastrar usuário utilizando email

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Cadastrar usuário utilizando email</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Criar perfil para o usuário no Tesouro Direto utilizando email</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>Pré-condição: Possuir email válido
                Pós-condição: É criado um perfil para o novo usuário
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso à internet
                App intalado
                Acesso ao site</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário não cadastrado acessa o aplicativo do Tesouro Direto
            2. O usuário não cadastrado seleciona seu objetivo no aplicativo (Simular,Investir...)
            3. O usuário não cadastrado deverá informa seu antecedência criminal.
            4. O usuário não cadastrado seleciona sua corretora
            5. O usuário não cadastrado seleciona a linguagem do app
            6. O usuário não cadastrado insere nome, email e senha e seleciona o botão "Create user"
            7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo</td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            Email inválido
            Usuário fechar aplicativo antes de terminar a ação
            Internet parar de funcionar durante a ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C02 - Cadastrar usuário utilizando Google

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Cadastrar usuário utilizando Google</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>
                Criar perfil para o usuário no Plant Jammer utilizando email
            </td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Possuir email válido
                pós-condição:É criado um perfil para o novo usuário
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso à internet
                App intalado</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
             1. O usuário não cadastrado acessa o aplicativo do Tesouro Direto
            2. O usuário não cadastrado seleciona seu objetivo no aplicativo (Simular,Investir...)
            3. O usuário não cadastrado deverá informa seu antecedência criminal.
            4. O usuário não cadastrado seleciona sua corretora
            5. O usuário não cadastrado seleciona a linguagem do app
            6. O usuário não cadastrado insere nome, email e senha e seleciona o botão "Create user"
            7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>Email inválido Usuário fechar aplicativo antes de terminar a ação Internet parar de funcionar durante a ação</td>
        </tr>
    </tbody>
</table>
<br>

## C03 - Modificar Nome

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Modificar Nome</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Modificar o nome dentro do app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição: Usuário logado no Tesouro Direto
                pós-condição:  Nome alterado
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso à internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as configurações da conta
            3. O usuário seleciona o campo nome e faz a alteração
            4. O usuário salva a alteração ao clicar no botão "Save Changes"
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>
            Nomes que são maiores que o tamanho configurado
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C04 - Excluir conta

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Excluir conta</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Excluir a conta cadastrada no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Conta excluída e usuário redirecionado para a tela inicial
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso à internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as configurações da conta
            3. O usuário seleciona o botão de deletar conta
            4. O usuário confirma o email
            5. O usuário seleciona novamente o botão para confirmar</td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Sem acesso a internet não será possivél realizar ação.</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            Email inválido Usuário fechar aplicativo antes de terminar a ação Internet parar de funcionar durante a ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C05 - Visualizar funcionalidade

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Visualizar funcionalidade</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>
            Poder ver as opções que se encontra no app
            </td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
            pré-condição: Usuário logado no Tesouro Direto
            pós-condição: Ver opções das funcionalidades
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso à internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções da conta
            3. O usuário seleciona o botão de funcionalides 
            4. O usuário clicar
            5. O usuário verá as funcionalidades
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação</td>
        </tr>
    </tbody>
</table>
<br>

## C06 - Escolher Simular

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Escolher Simular</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver opções de simulação
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de simular 
            4. O usuário clicar
            5. O usuário verá como fazer a simulação
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C07 - Escolher Invesrir

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Escolher Invesrir</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver nas funcionalidade o ponto de investir.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de funcionalidade
            4. O usuário clicar no botão investir 
            5. O usuário opções de investimento 
            6. O usuário verá como fazer seu investimento
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo Intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C08 - Escolher Resgatar

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Escolher Resgatar</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver nas funcionalidade o ponto de resgatar.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de funcionalidade
            4. O usuário clicar no botão resgatar 
            5. O usuário efetuará o resgate imformando seus dados cadastrado no sistema.
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo Intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C09 - Escolher Título

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Escolher Título</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver nas funcionalidade o ponto de investir.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de funcionalidade
            4. O usuário clicar no botão título. 
            5. O usuário poderá escolher seu título entre as opções disponível.
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo Intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C10 - Escolher Corretoras ou Banco

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Escolher Corretoras ou Banco</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver nas funcionalidade o ponto de investir.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o app Tesouro Direto Já sabendo sua corretos ou banco
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de funcionalidade
            4. O usuário clicar no botão da opção que deseja realizar.
            5. O usuário escolher corretora.
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo Intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>

## C11 - Vizualizar Posição

<table class="table table-striped border">
    <thead>
        <th>Título</th> 
        <th>Vizualizar Posição</th> 
    </thead>
    <tbody>
        <tr>
            <td>Objetivo</td>
            <td>Poder ver dentre as opções o que deseja no app</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>pré-condição:Usuário logado no Tesouro Direto
                pós-condição:Ver nas funcionalidade o ponto de investir.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Acesso a internet</td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>
            1. O usuário acessa o Tesouro Direto
            2. O usuário acessa as opções do app
            3. O usuário seleciona o botão de funcionalidade
            4. O usuário clicar no botão posição 
            5. O usuário vizualizar sua posição.
            </td>
        </tr>
        <tr>
            <td>Restrições</td>
            <td>Fluxo Intuitivo</td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>
            O usuário fechar o aplicativo antes de terminar a ação
            A internet parar de funcionar no meio da ação
            </td>
        </tr>
    </tbody>
</table>
<br>