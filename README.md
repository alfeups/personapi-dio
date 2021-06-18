## Creating an API REST using Sprint Boot to People Management

In this course we review the steps below:

<li>First of all, the whole project setup using Spring Boot Initialzr;
<li>A data model to mapping entities into data banks;
<li> Users management operations; 
<li> Relations between operations - registering, reading, updating, removing user from the system - taking into account REST concepts while developing the project;
<li> Deployment using heroku cloud service.

Configuração da estação

`cd /Downloads/`

- instalando sdk para instalar a versao java 11;

`curl -s "https://get.sdkman.io" | bash`

Checar versoes disponiveis: 

`sdk list java | less`

Para instalar a versao 11.0.11.hs-adpt do java, segue o comando:

`sdk install java 11.0.11.hs-adpt`

E para coloca-la em uso e checar a versão, respectivamente:

`sdk use java 11.0.11.hs-adpt`
`java --version`

Agora para instalar e colocar em uso o Maven, outra ferramenta necessária para criação da API, segue o comando ainda com o sdk:

`sdk install maven 3.6.3`
`sdk use maven 3.6.3`

Instalar a IDE que foi utilizada: <a hred"link">IntelliJ IDEA</a>. Criar uma conta no <a hred"link">Heroku </a> para o realizar o deploy na nuvem. E concluindo o setup com a criação do arquivo Spring Boot. Após realizar o download do arquivo, descompactar e abrir com o IntelliJ.

## Recursos utilizados
<li><a href="https://intellij-support.jetbrains.com/hc/en-us">IntelliJ</a> - IDE
<li><a href="https://herokuapp.com/">Heroku</a> - Cloud deployment
<li><a href="https://mapstruct.org/">MapStruct</a> - Java DTOs mapping
<li><a href="https://www.postman.com/">Postman</a> - Support to documentation, executing and requestings.
<li><a href="https://www.oracle.com/java/technologies/persistence-jsp.html">JPA</a> - 


## Steps

<li><a href="https://github.com/alfeups/personapi-dio/tree/master/img">Images</a>
