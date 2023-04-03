# integradorClinica🏥
_Este é o código-fonte do Integrador de Clínica, um programa para integrar informações de pacientes de várias clínicas médicas em um único sistema. Ele foi desenvolvido em Java e utiliza o framework Spring Boot._

## ⚙️Funcionalidades:
__O Integrador de Clínica é um programa que permite a integração de informações de pacientes de várias clínicas médicas em um único sistema. Ele possui as seguintes funcionalidades:__
- Cadastro de pacientes: permite o cadastro de pacientes no sistema, incluindo nome, data de nascimento, CPF, endereço, telefone e histórico médico.

- Busca de pacientes: permite a busca de pacientes cadastrados no sistema por nome, CPF ou telefone.

- Integração de informações: permite a integração de informações de pacientes de várias clínicas médicas em um único sistema, por meio da importação de arquivos CSV.

- Exportação de informações: permite a exportação de informações de pacientes cadastrados no sistema para arquivos CSV.

## 🛠️Como executar o aplicativo:
__Existem diversas formas de rodar a aplicação. Uma delas é através da IDE `NetBeans`. E a outra forma:__
1. Certifique-se de ter o Java JDK 11 ou superior instalado em sua máquina. Você pode baixá-lo no site oficial da Oracle: https://www.oracle.com/br/java/technologies/javase-downloads.html.

2. Faça o clone ou o download deste repositório em sua máquina local.

3. Abra um terminal na pasta raiz do projeto e execute o seguinte comando para compilar o projeto:
```bash
  ./mvnw clean package
  ```
Isso criará um arquivo JAR executável na pasta `target`.

4. Execute o seguinte comando para iniciar o programa:
```bash
  java -jar target/integrador-clinica-0.0.1-SNAPSHOT.jar
  ```
O programa iniciará e estará disponível em `http://localhost:8080`.

## ✍️Autores

__- [@cemeterydriiver](https://www.github.com/cemeterydriiver)__
