# projeto-pratico-a1-1

# projeto-pratico

Nesta atividade, você deverá demonstrar suas habilidades práticas com o Git, abrangendo desde a criação de um repositório até a aplicação de conceitos de versionamento semântico. A atividade envolverá a criação de um repositório, manipulação de branches, criação de pull requests, submissão de alterações e a criação de tags com base no versionamento semântico.

Instruções:

1) Criação de um Repositório no GitHub:

    Acesse o GitHub e crie um novo repositório público com o nome projeto-pratico.
    Ao criar o repositório, marque a opção para adicionar um README.md.

    * Criado diretamente pelo Github.

2) Clonar o Repositório Localmente:

    No seu ambiente local, abra o terminal ou o prompt de comando e faça o clone o repositório recém-criado.

        $ git clone git@github.com:guilherme-g7/projeto-pratico.git

3) Criação de uma branch:

    Navegue até o diretório do repositório clonado e crie uma nova branch para adicionar uma funcionalidade ao projeto. Nomeie a branch como feature/{seu-identificador}:

        $ git branch feature/351651
        $ git checkout feature/351651

4) Faça alteracoes e comite:

    Abra o arquivo README.md no editor de sua preferência e adicione uma descrição sobre a funcionalidade que será implementada.
    Após fazer as alterações, adicione o arquivo alterado à área de stage e faça o commit.

        $ git status
        $ git add .
        $ git commit -m "Alterado README.md com a descrição do projeto prático porposto no dia 27/08/2024, no componente curricular GERÊNCIA DE CONFIGURAÇÃO DE SOFTWARE"
        $ git status

5) Envie as alterações para o repositório remoto:

    Faça o envio da branch com as alterações para o reposiório remoto.

        $ git push origin feature/351651

6) Crie um pull request:

    Acesse o repositório no GitHub e crie um Pull Request para mesclar a branch feature/{seu-identificador} na branch main.
    OBS.: Adicione uma descrição clara no Pull Request, explicando as mudanças feitas.

    * PR feito pelo Github e apreovado no dia 27/08/2024

7) Aceite o Pull Request:

    Após criar o Pull Request, faça a revisão e, se tudo estiver correto, aceite-o para que as mudanças sejam integradas na branch main.


8) Submeta uma Nova Alteração e Crie uma Tag:

    Volte para a branch main no seu ambiente local.
    Traga/receba as últimas alterações da branch main do repositório remoto.
    Crie uma nova tag seguindo as práticas de versionamento semântico. Por exemplo, para indicar a primeira versão do projeto:

        $ git checkout main
        $ git pull
        $ git tag -a v1.0.0 -m "Versão 1.0.0 para projeto do componente curricular GERÊNCIA DE CONFIGURAÇÃO DE SOFTWARE"

9) Envie a tag para o Repositorio:

    Envie a tag criada para o repositório remoto.

        $ git push origin --tags

10) Explorando o Conceito de Versionamento Semântico:

    No arquivo README.md, adicione uma seção que explique o conceito de versionamento semântico e como ele é aplicado no controle de versões do software.

    Versionamento semântico - 1.0.0

    Primeiro dígito é o MAJOR informa a compatibilidade entre versões, alterado se as mudanças torne incompatíveis as versões.
    Segundo dígito é o MINOR informa a versão da funcionalidade, alterado se o software ou biblioteca sofre uma mudança e é adicionado uma nova funcionalidade.
    Terceiro dígito PATCH informa a versão de correção de bugs, alterado se o software passa por alguma alteração provido de um bug. 

    Essa técnica de versionamento semântico traz uma comunicação mais clara entre os softwares tornando a integração com as dependências do projeto mais simples.
    É globalmente aceita pela comunidade, então um desenvolvedor do outro lado do mundo entenderá o sistema de versionamento usado no projeto.


Instruções finais:
    Comite as mudanças e envie-as para o repositório remoto.

Entrega:
    Submeta o link para o repositório GitHub onde a atividade foi realizada. O repositório deve conter todos os passos solicitados, incluindo os commits, pull requests, e tags.

