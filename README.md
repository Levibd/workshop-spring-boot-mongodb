
# Workshop Spring Boot MongoDB

Bem-vindo ao repositório do projeto **Workshop Spring Boot MongoDB**! 🚀  
Este projeto foi desenvolvido para demonstrar o uso do framework Spring Boot integrado ao banco de dados NoSQL MongoDB, abordando conceitos como APIs RESTful, persistência de dados, e operações CRUD.

## 📜 Descrição

O projeto consiste em uma API RESTful que gerencia entidades como **usuários (Users)** e **posts**, com funcionalidades para criar, ler, atualizar e deletar registros, além de recursos adicionais como:  
- Busca de posts por título.  
- Aninhamento de comentários em posts.  

Foi desenvolvido como parte de um workshop, com o objetivo de aprender e aplicar conceitos práticos sobre o ecossistema Spring Boot e o banco de dados MongoDB.

---

## 🛠️ Funcionalidades

- **API RESTful** com operações CRUD para usuários e posts.  
- Busca avançada por título utilizando **queries no MongoDB**.  
- Integração entre entidades (usuários e posts).  
- Utilização do padrão DTO (Data Transfer Object) para transferência de dados.  

---

## 🔧 Tecnologias Utilizadas

As principais ferramentas e tecnologias utilizadas no projeto são:  

- **Java 17+**  
- **Spring Boot 3.0+**  
- **MongoDB**  
- **Spring Data MongoDB**  
- **Postman** (ou qualquer cliente REST) para testar a API.  
- **Maven** para gerenciamento de dependências.  

---

## 🚀 Pré-requisitos

Certifique-se de ter os seguintes itens instalados no seu ambiente:  

- **Java JDK 17+**  
- **MongoDB** (instância local ou em nuvem).  
- **Maven**  

---

## 📦 Instalação e Execução

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/workshop-spring-boot-mongodb.git
   cd workshop-spring-boot-mongodb
   ```

2. Configure o MongoDB:  
   - Certifique-se de que o MongoDB está rodando localmente na porta padrão `27017` ou ajuste a conexão em `application.properties`.  

3. Compile o projeto:  
   ```bash
   mvn clean install
   ```

4. Execute a aplicação:  
   ```bash
   mvn spring-boot:run
   ```

5. Teste a API:  
   - Use um cliente REST como o **Postman** para interagir com os endpoints.  
   - Exemplos de endpoints:  
     - `GET /users` - Lista todos os usuários.  
     - `POST /users` - Cria um novo usuário.  
     - `GET /posts/{id}` - Busca um post pelo ID.  

---

## 🖼️ Demonstração

![image](https://github.com/user-attachments/assets/512d9fd1-c2c7-4d90-8ac7-e58fe402fb91)
![image](https://github.com/user-attachments/assets/3d72fcc3-f688-4756-b1e3-79bfc3d718d4)
![image](https://github.com/user-attachments/assets/4955325c-9ad7-4783-a5df-e5cab8849abc)

---

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um **Pull Request** ou **Issue** para melhorias, sugestões ou reportar problemas.


---

## 📫 Contato

Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:  

- **Autor**: Levi Braga Dantas  
- **E-mail**: [levibdantas@gmail.com](mailto:seu-email@example.com)  
- **LinkedIn**: [https://www.linkedin.com/in/levi-dantas-a088a318b/](https://linkedin.com/in/seu-perfil)

---

Caso precise de ajustes ou queira incluir algo específico, é só avisar! 😊
