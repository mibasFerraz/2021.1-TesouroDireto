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
