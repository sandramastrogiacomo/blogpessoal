# 📝 Blog Pessoal  

O **Blog Pessoal** é uma plataforma para criação e gerenciamento de postagens, permitindo interação dinâmica entre usuários. Desenvolvido com **Spring Boot**, conta com **Spring Security** para autenticação e autorização, além de um **frontend integrado** para melhor experiência do usuário. Os testes da API foram realizados via **Insomnia**.  

🚀 **Tecnologias utilizadas**:  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)  
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)  
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF?style=flat&logo=insomnia&logoColor=white)  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)  

---

## 📌 Funcionalidades  

✅ **Cadastro e autenticação de usuários**  
📝 **Criação, edição e exclusão de postagens**  
📂 **Gerenciamento de categorias de posts**  
🔐 **Proteção de rotas com Spring Security**  
📡 **Consumo da API no frontend**  

---

## 🚀 Como Executar  

### **Pré-requisitos**  

- [Git](https://git-scm.com/) instalado  
- [JDK 17+](https://www.oracle.com/java/technologies/javase-downloads.html)  
- [MySQL](https://www.mysql.com/) configurado  
- [Node.js](https://nodejs.org/) instalado para rodar o frontend  
- [Insomnia](https://insomnia.rest/download) para testes da API  

### **1️⃣ Back-end (API)**  

1. **Clone o repositório**  
```bash
git clone https://github.com/sandramastrogiacomo/blogpessoal.git
cd blogpessoal
Configure o banco de dados no application.properties

Compile e execute

bash
Copiar
Editar
mvn clean install
mvn spring-boot:run
A API estará disponível em http://localhost:8080

2️⃣ Front-end
Acesse o diretório do frontend

bash
Copiar
Editar
cd frontend
Instale as dependências

bash
Copiar
Editar
npm install
Execute o projeto

bash
Copiar
Editar
npm start
O frontend estará disponível em http://localhost:3000

📡 Testando a API no Insomnia
Os testes foram realizados via Insomnia. Você pode utilizar Postman ou outra ferramenta REST.

Principais Endpoints:

🔹 Cadastro de usuário:
POST http://localhost:8080/usuarios/cadastrar (JSON no corpo da requisição)

🔹 Login de usuário:
POST http://localhost:8080/usuarios/logar (Retorna um token JWT)

🔹 Criar postagem:
POST http://localhost:8080/postagens

🔹 Listar postagens:
GET http://localhost:8080/postagens

🔹 Atualizar postagem:
PUT http://localhost:8080/postagens/{id}

🔹 Excluir postagem:
DELETE http://localhost:8080/postagens/{id}

💡 Caso haja uma coleção de testes no Insomnia, importe o arquivo JSON no aplicativo.

🤝 Contribuições
💡 Contribuições são bem-vindas! Se tiver sugestões, melhorias ou encontrar problemas, abra uma issue ou envie um pull request.

📜 Licença
📝 Este projeto está licenciado sob a MIT License.

📬 Contato
🔗 GitHub: sandramastrogiacomo
🔗 LinkedIn: Sandra Mastrogiacomo

📌 Este projeto está em constante evolução. Acompanhe as atualizações! 🚀


