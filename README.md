# Task Manager API

Projeto desenvolvido como prática de conceitos de Java com Spring Boot.  
Trata-se de uma API REST para gerenciamento de tarefas, com funcionalidades como criação, listagem, atualização de status e exclusão de tarefas.

---

## 📌 Funcionalidades

- ✅ Criar nova tarefa
- 📄 Listar todas as tarefas
- 🔄 Atualizar status da tarefa (Pendente, Em Andamento, Concluída)
- ❌ Deletar uma tarefa
- 🔍 Buscar tarefas por status

---

## 🛠️ Tecnologias utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Maven
- Postman (para testes)

---

## 📁 Estrutura do projeto

```
projeto/
├── controller/
│   └── TaskControllerImpl.java
├── domain/
│   └── Task.java
├── repository/
│   └── TaskRepository.java
├── service/
│   └── TaskServiceImpl.java
└── TaskApiApplication.java
```

---

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/guibonf1m/Task_Manager_Project.git
   ```

2. Navegue até o projeto:
   ```bash
   cd Task_Manager_Project/projeto
   ```

3. Execute a aplicação (pode usar o botão de run da sua IDE ou o comando abaixo):
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse a API no navegador ou via Postman:
   ```
   http://localhost:8080/api/tasks
   ```

---

## 🔄 Futuras melhorias

- Integração com banco de dados
- Paginação e ordenação na listagem
- Validações com Bean Validation
- Testes com JUnit

---

## 👨‍💻 Desenvolvedor

**Guilherme Bonfim**  
[LinkedIn](https://www.linkedin.com/in/guibonf1m)  
[GitHub](https://github.com/guibonf1m)
