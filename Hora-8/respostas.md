# Hora 8 - Estrutura de um Projeto Java Web com Maven

## Ex 1 - Localizar pom.xml

O ficheiro pom.xml encontra-se na raiz do projeto Hora-8.
É responsável pela configuração do projeto Maven.

## Ex 2 - Nome e Versão

- groupId: pt.escola.curso
- artifactId: minha-app
- version: 1.0-SNAPSHOT

## Ex 3 - Empacotamento WAR

O projeto utiliza packaging war.

O ficheiro WAR contém a aplicação Web e pode ser publicado num servidor como o Apache Tomcat.

## Ex 4 - Código Java e Recursos Web

- src/main/java: contém o código Java.
- src/main/resources: contém ficheiros de configuração.
- src/main/webapp: contém páginas HTML, CSS e JavaScript.

## Ex 5 - Criar sobre.html

Foi criado o ficheiro sobre.html dentro da pasta src/main/webapp.

A página contém um título e uma breve apresentação do projeto.

## Ex 6 - Estrutura de Diretórios

Hora-8/
- pom.xml
- respostas.md
- src/
  - main/
    - java/
    - resources/
    - webapp/
      - sobre.html
      - WEB-INF/
        - web.xml
  - test/
    - java/

### Explicação de 5 elementos

1. pom.xml - Configura o projeto Maven.
2. java - Guarda as classes Java.
3. resources - Guarda ficheiros de configuração.
4. webapp - Guarda os ficheiros da aplicação Web.
5. WEB-INF - Guarda configurações protegidas da aplicação.

## Resultado

O comando mvn clean package foi executado com sucesso.

O Maven criou o ficheiro target/minha-app.war.
