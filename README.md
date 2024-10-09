# Projeto MongoDB/NoSQL com Spring Boot
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/AndUrban/workshop-spring-boot-mongodb)


# Sobre o projeto

O projeto MongoDb com Spring Boot, oferecida pela [DevSuperior](https://devsuperior.com "Site da DevSuperior"),
consiste na elaboração de um sistema que simula a postagem de posts, seus autores e seus comentários.
Utilizando o paradigma de Banco de Dados Orientado a Agregados, as informações são armazenadas em formato
não relacional - utilizando dentro do paradigma, o modelo orientado a documentos. Nesse sistema, um conjunto de 
objetos relacionados são tratados como uma unidade.


## Estrutura Lógica
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/spring_mongodb_1.png)
## Instanciação dos Objetos em Memória
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/spring_mongodb_2.png)
## Diagrama de Classes
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/spring_mongodb_3.png)
## Exemplo Representado em Formato JSON
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/spring_mongodb_4.png)

# Tecnologias utilizadas
- Java
- Spring Boot
- MongoDB

# Execução
Pré-requisitos: JavaSE-21

```bash
# clonar repositório:
git clone https://github.com/AndUrban/workshop-spring-boot-mongodb.git

# Dentro da IDE, importar o projeto:
workshopmongo

# Caminho para a execução:
workshopmongo/(src/main/java)/com.andreurban.workshopmongo/WorkshomongoApplication.java

-> Inicie o MongoDB
-> Run as Spring Boot App
--> É possível alterar os valores das instanciações na classe/arquivo Instantiation.java
# Caminho do arquivo
workshopmongo/(src/main/java)/com.andreurban.workshopmongo.config/Instantiation.java

# Foi utilizado o programa Postman para rodar as requisições

# Link:
http://localhost:8080
# Endpoints:
  - /users
  - /posts
```

# Agradecimentos
Dr. Nélio Alves - DevSuperior: Escola de Programação

## LinkedIn
www.linkedin.com/in/andurban
