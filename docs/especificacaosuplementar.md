# <center> Especificação Suplementar


### Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 27.08.2021 | 0.1 | Criação do documento | Dafne Moretti|

### Participantes

* Dafne Moretti

### __Introdução__
<div align="justify"> 
    Os requisitos não funcionais do aplicativo do Tesouro Direto estão descritos neste documento.
    Em sua construção, foi utilizado o FURPS+ a fim de descrever as categorias principais de requisitos, sendo elas usabilidade, confiabilidade, desempenho, suportabilidade e requisitos de licenciamento.
</div>

### __Finalidade__
Atuando juntamente com os casos de uso na tarefa de capturar todos os requisitos do sistema, o objetivo desse documento é definir os requisitos não funcionais do aplicativo Tesouro Direto.


### __Escopo__
O aplicativo do Tesouro Direto existe a fim de acelerar e facilitar o investimento no Tesouro Direto, com funcionalidades como simular e resgatar. 


### __Definições, Acrônimos e Abreviações__
Consultar <a href="../../modelagem/lexico/#lexicos">Léxicos</a>

### __Funcionalidades__
Podem ser encontradas nos casos de uso.

### __Usabilidade__
Se refere à facilidade do usuário em realizar as tarefas desejadas.

* __Interface intuitiva e aprendizado rápido__

Ao abrir o aplicativo do Tesouro Direto é possível perceber uma interface fácil de utilizar, com um botão para conhecer o Tesouro, um para simular abaixo e um para entrar no aplicativo. À esquerda é possível visualizar um botão que abre uma gama de opções que o usuário pode escolher utilizar. (RNF 16)

* __Facilidade de recordação, uso e ícones padronizados__

Percebe-se abrindo o aplicativo do Tesouro Direto que existem inúmeros ícones padronizados socialmente representando as funcionalidades e as telas. A representação da tela de início por exemplo, é uma casa e a representação das consultas é uma lupa. Essas decisões ativam a memória dos usuários para outros sistemas que ele já utilizara. (RNF 16) (RNF31)

* __Eficiência e linguagem do aplicativo__

A linguagem utilizada no aplicativo é simples, direta e não muito técnica, o que permite que usuários de diferentes idades e realidades possam utilizá-lo e fiquem satisfeitos com o sistema. (RNF 16)

### __Performance__
Quão rápido é o aplicativo do Tesouro Direto?

* __Armazenamento e lentidão nos processos do aplicativo__

Para baixar o aplicativo, são necessários disponíveis 105,7 (MB) Megabytes nos dispositivos da Apple e 67M nos dispositivos Android.

* __Rapidez no tempo de resposta__

O tempo de resposta do usuário deve ser pequeno para que ele fique satisfeito com o desempenho do aplicativo. ( RNF31 ) 

### __Confiabilidade__
Analisa a confiabilidade do Tesouro Direto, ou seja, diz respeito à segurança e a manutenibilidade do aplicativo.

* __Tratamento de dados__

Os dados atualizados fornecidos pelo usuário ao aplicativo do Tesouro Direto são tratados pela Administradora B3 conforme previsto na Declaração de Proteção de Dados.

* __Clareza de identificação do fornecedor__

Antes de fazer o download do aplicativo, o usuário deve conseguir ver o vendedor do aplicativo do Tesouro Direto, que é o Governo do Brasil.

* __Confiabilidade das estatísticas__

Conforme a Lei de Sigilo Bancário (Lei Complementar nº 105/2001) todas as estatísticas relacionadas ao aplicativo do tesouro nacional são transferidas anonimamente.

* __Transparência na política de privacidade__

Antes de fazer o download do aplicativo, o usuário deve conseguir visualizar quais dos seus dados serão utilizados e para que fins.

### __Suportabilidade__
Caracterizada pela portabilidade e adaptabilidade do aplicativo do Tesouro Direto. Por exemplo, as plataformas que ele oferece suporte.

* __Pré-requisitos para utilização do aplicativo__

O usuário vai ser capaz de usar o aplicativo do Tesouro Direto de todos os locais, precisando apenas de internet. (RNF 17)

* __Dispositivos compatíveis__

O aplicativo deve ser compatível com iPhone (IOS 10.0 ou posterior), iPod touch (IOS 10.0 ou posterior) e Mac (macOS 11.0 ou posterior), Mac com chip M1 da Apple. E seu download deve ser feito através da App Store.

### __Restrições de Design__

* __Suporte a idiomas__

O aplicativo do Tesouro Direto é um aplicativo nacional e, portanto, não há a possibilidade de se alterar o idioma.

* __Navegabilidade__

No aplicativo, ao apertar no botão à esquerda, abrem inúmeras abas que facilitam a navegação entre as telas.

### __Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line__
Ao entrar no aplicativo, é possível encontrar um botão "Fale Conosco" que direciona o usuário para o site do Tesouro Direto onde é possível tirar dúvidas, requisitar ajuda ou ler perguntas feitas por outros usuários.

### __Componentes Adquiridos__

* __Bibliotecas__

Durante o desenvolvimento do aplicativo foram utilizadas bibliotecas visando facilitar o processo.

* __Servidor__

O aplicativo necessita de um servidor para funcionar.

* __Infra-estrutura__

É importante dar suporte aos colaboradores no desenvolvimento do aplicativo do Tesouro Direto.


### __Interfaces do Usuário__
Onde são determinadas as interfaces que o aplicativo suporta.

* __Interface do Usuário__

Após o download do aplicativo o usuário consegue ter acesso a interface principal.

* __Interface de Software__

O aplicativo Tesouro Direto disponibiliza interface para sistemas Android e IOS.

* __Interface de Hardware__

É necessária comunicação com o servidor e acesso à internet.

### __Requisitos de Licenciamento__
Todos os usuários precisam concordar com os Termos de Uso do aplicativo do Tesouro Direto.

### __Observações Legais, de Copyright e Outras__
Os usuários do Tesouro Direto devem respeitar a lei de direitos autorais. O copyright do Tesouro Direto é da Secretaria do Tesouro Nacional. 2018 Secretaria do Tesouro Nacional.

### __Padrões Aplicáveis__
Alguns padrões que devem ser seguidos pelo Tesouro Direto são ISO 6166.

## Referências

> [1] - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13;