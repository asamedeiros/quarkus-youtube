# Primeira Aplicação
## Pré-requisitos
* JDK 1.8+ com JAVA_HOME configurado
* Uma IDE (Eclipse ou IntelliJ)
* Apache Maven 3.5.3+
* Docker (caso queira criar e executar uma imagem da aplicação)
* GraalVM (caso queira gerar o executável nativo para Linux)

## Passos

### 1. Como Criar Projeto


* [Baixar fonte](https://github.com/viniciusfcf/quarkus/archive/v0.0.1.zip)

* Clonar do projeto do meu GIT: **git clone --branch v0.0.1 https://github.com/viniciusfcf/quarkus.git**

O projeto irá conter:

1. Projeto seguindo estrutura maven

2. O recurso com.github.viniciusfcf.hello.HelloResource disponível no contexto /hello e /hello/quarkus

3. Um teste de unidade para HelloResource utilizando REST Assured 

4. Uma página inicial index.html

5. Arquivos Dockerfile para criação de imagens em modo nativo e JVM

6. Arquivo application.properties para configuração das extensões

### 2. Subir aplicação com Hot Reloading
* ./mvnw compile quarkus:dev

### 3. Acessar aplicação
* http://localhost:8080
* http://localhost:8080/hello
* http://localhost:8080/hello/quarkus

### 4. Apresentação

[Baixe aqui](https://docs.google.com/presentation/d/1S8oylcN4Hpcj0m6Zavkes9Q6SO4zfy_IMB4g0DMQuuI/edit?usp=sharing)

### 5. Vídeo do Youtube

https://youtu.be/pBc0qSLaHO8


# Segundo vídeo: Utilizando Hibernate ORM

## Pré-requisitos
* JDK 1.8+ com JAVA_HOME configurado
* Uma IDE (Eclipse ou IntelliJ)
* Apache Maven 3.5.3+
* Postgres
* GraalVM (caso queira gerar o executável nativo para Linux)

## Passos

### 1. Como acessar o código do projeto do final do vídeo

* [Baixar fonte](https://github.com/viniciusfcf/quarkus/archive/v0.0.2.zip)

* Clonar do projeto do meu GIT: **git clone --branch v0.0.2 https://github.com/viniciusfcf/quarkus.git**

### 2. Vídeo do Youtube

https://youtu.be/
