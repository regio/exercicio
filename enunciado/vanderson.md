Respostas:

1) Um repositorio de controle de versão, serve para controlar as versões dos arquivos comitados.

2) Git tem versionamento distribuido e tem branchs, pode trabalhar off-line e com varias equipes.

3) Eh uma ferramenta de automatizaçao de tarefas de build, serve para organizar e gerenciar as tarefas de projetos desenvolvidos em java.

4) No Ant voce precisa criar as tarefas e no Maven as tarefas ja vem pre-definidas e voce utiliza as goals.

5) Em Java.

6) Validate - valida se todo o projeto esta correto e toda informaçao necessaria para sua contruçao esta disponivel.
	Compile - compila o codigo fonte do projeto
	Test - executa os testes unitarios do codigo compilado, usando uma ferramenta de testes unitarios, como o junit.
	Package - empacota o codigo compilado de acordo com o empacotamento escolhido, por exemplo, em JAR.
	Verify - executa validaçoes relacionadas a testes de integraçao com o projeto gerado.
	Install - instala o pacote no repositorio local, para ser usado como dependencia de outros projetos locais.
	Deploy - feito em ambiente de integraçao ou de release, copia o pacote final para um repositorio remoto para ser compartilhado entre desenvolvedores e projetos.

7) Atraves do pom.xml dentro de <dependencies> e <plugins>.

8) SVN, GIT - repositorios de arquivos, Jenkins, Hudson e Cruise Control - sistema de contrução continua, Junit, Cucumber e Selenium - framework de testes.

9) Integração automatizada, testes automatizados, builds automatizados e deploy automatizados, fornecendo feedbacks para o time.

10) A diferença se da apos a separação, onde a Oracle virou proprietario do Hudson e o Jenkins passou permaneceu livre e desenvolvido pela comunidade Open Source.

11) É uma ferramenta de automatização de build e deploy de projeto.

12) Sim, por meio de plugins que possibilitam a integração de outras ferramentas.

13) Por varios motivos, automatização de builds, geração de artefatos, notificação de quebra de builds, a automatização tras um ganho significativo e gera seguranção para a equipe no que dis respeito a coerencia na codificação.

14) Eh uma biblioteca java utilizada para a geraçao de logs em aplicaçoes. Serve para habilitar o mecanismo de log em tempo de execuçao sem a necessidade de alteraçao no arquivo binario, inserindo loggin ao longo do codigo fonte sem acarretar perda de performance.

15) Armazenar as configuraçẽos do log4j para o projeto.

17) A dependencia deve ser incluida no arquivo pom.xml informando o groupid=log4j, o artifactid=log4j e o version=1.2.17.