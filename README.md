# DIO desafio Git/Github 🔥🔥
Projeto sobre o Git/GitHub

## Um pouco mais sobre o GIT:
### O que é o GIT ❓
    Por definição, o Git é um Sistema de Controle de Versão Distribuído. Ele foi criado por Linus Torvalds, que é mais conhecido por outra criação, o Linux.
    Linus desenvolveu o Git após ter ficado insatisfeito com uma mudança de licença de utilização do BitKeeper, o sistema de controle de versão que era utilizado por ele e pela equipe que desenvolvia o Linux.

    Como um bom sistema de controle de versão, o Git registra as mudanças que ocorrem no código-fonte de um projeto. Logo, permite que os arquivos sejam alterados de forma simultânea, por inúmeras pessoas, sem a preocupação que essas alterações sejam sobrescritas umas pelas outras.


### Qual a importância do Git ❓
    O Git é essencial em quase todos os projetos realizados em equipes que geralmente trabalham em paralelo. Isso porque ele evita que haja conflitos entre as alterações realizadas.
    Como os projetos costumam estar em constante evolução, é comum ocorrer alterações que possam causar problemas no funcionamento deles. Nesse caso, o Git permite que tais alterações sejam revertidas de maneira simples e rápida, voltando a versão antiga do projeto.

### Como o Git funciona, na prática ❓
    De forma simplificada, o Git trabalha em uma arquitetura em Branch (ou ramificações). Cada novo commit, ou seja, alteração do código, cria um novo ponto na ramificação atual (uma branch).

    Aqui vou mostrar uma exemplificação de um fluxo de contribuição em um projeto utilizando o Git:

    1. Clone do projeto
    O primeiro passo para obter o código-fonte do projeto é cloná-lo em nossas máquinas, para que seus arquivos fiquem disponíveis localmente.

    2. Criação da Branch
    Ao criar uma Branch, estamos criando uma nova ramificação, totalmente independente, para podermos alterar os arquivos do projeto sem interferir nos originais.

    Esse processo é considerado uma boa prática quando se está trabalhando em nova funcionalidade.

    3. Commits
    Conforme vão sendo criados e alterados os arquivos, elas vão sendo divididas em commits. É importante que a descrição de cada commit seja objetiva, pois ela vai ficar salva no histórico das alterações.

    4. Hora do Push
    Uma vez que a funcionalidade está totalmente finalizada, devemos enviar nossa Branch, com todas as alterações, de volta ao repositório remoto. Assim, ela ficará disponível para os demais contribuidores do projeto poderem ver e alterar.

    5 – Merge para juntar tudo
    Para mesclar as modificações de sua Branch com os arquivos originais do projeto da Branch principal ou máster, você pode utilizar o comando Merge. Após isso, é necessário dar um commit e um push, para enviar a ramificação máster mesclada ao repositório remoto e deixar tudo disponível para os demais contribuidores.

    Existe também o Pull Request, que geralmente tem relação com a contribuição em projetos open source. Basicamente, ele ocorre quando se pede para o dono do repositório que suas modificações sejam incluídas nele.

### Quais os comandos mais utilizados no Git ❓
 - git init - Inicializar um repositório;

 - git clone - Utilizado para clonar o repositório remoto para a sua maquina(local);

 - git status - você concegue ver os arquivos modificados antes de dar um git add . e um git commit  

 - git add . OU * OU ./caminho_especifico - o comando add ele vai adicionar suas alterações no staged area, no caso for git add . e git add * vai adicionar todas as alterações, mas se quiser algo mais especifico basta apenas especificar o arquivo alterado git add ./arquivo-alterado;

 - git commit -m "initial commit" - Faz o commit apenas dos arquivos modificados e que encontram-se adicionados na área de stage (Changes to be committed) do Git. Ou seja, trata-se apenas dos arquivos que você adicionou usando o comando anterior o git add; 

- git push - Esté comando de fato vai enviar os arquivos do commit | repositorio local para o remoto

 - git pull - Caso o seu commit não seja aceito é porque teve mudanças do repositorio remoto, então e necessário atualizar o seu repositorio local, por isso utilizamos o git pull, Mas tenha atenção , se for preciso fazer o pull atente se, porque poder aver um merge, e isso não vai te deixa-lo fazer o push 😢 , mais calma vecê pode aceitar as alteracoes feitas pelos seus colegas de contribuição e logo depois push 😁;

 ### Git é a mesma coisa que Github ❓
    Muitas pessoas confundem Git com Github, mas tratam-se de termos distintos. O Git é o sistema de versionamento, enquanto o Github é uma plataforma para criação de repositórios Git.

    Em outras palavras, o Github permite que você crie um repositório Git remoto, possibilitando que outras pessoas possam clonar esse repositório localmente, realizar alterações e enviar essas alterações de volta para o repositório remoto.

    É importante destacar que utilizar um sistema de hospedagem de código é uma forma mais rápida e simples de criar um repositório Git e começar a desenvolver projetos incríveis em equipe.

## Saiba mais sobre o GIT e GitHub 😍:
- [GIT // Dicionario do Programador](https://www.youtube.com/watch?v=za5KWZ5pRag&t=5s)
- [GITHUB // Dicionário do Programador](https://www.youtube.com/watch?v=myQuetgSEsY)

#### Creditos 👌
- [Algumas informaçoes foram tiradas do blog hostgator](https://www.hostgator.com.br/blog/git-o-sistema-de-controle/) 
- E complementos que vi no curso de git hub da DIO 🔥😉