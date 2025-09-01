# 📝 Todo List - Fullstack (Angular + Spring Boot)

Projeto fullstack com frontend em Angular e backend em Spring Boot.  
Este repositório contém as duas aplicações separadas em:

- `/frontend` → Angular
- `/todolist` → Spring Boot

---

## 🚀 Como rodar o projeto

### ✅ Pré-requisitos

- Node.js (https://nodejs.org)  
- Java 17+ (https://adoptium.net)  
- Git (para clonar o projeto)

---

## 🖥️ Frontend (Angular)

1. Navegue até a pasta `frontend`:

```powershell
cd frontend
```

2. Instale as dependências do Angular:

```powershell
npm install
```

3. Rode o servidor de desenvolvimento:

```powershell
npm start
```

> Ou, se estiver usando o Angular CLI diretamente:
>
> ```powershell
> npx ng serve
> ```

---

## ☕ Backend (Spring Boot)

1. Navegue até a pasta `todolist`:

```powershell
cd todolist
```

2. Baixe e instale as dependências Java com Maven Wrapper:

```powershell
.\mvnw clean install
```

3. Inicie a aplicação Spring Boot:

```powershell
.\mvnw spring-boot:run
```

---

## 🌐 Endpoints

- Frontend: `http://localhost:4200`
- Backend: `http://localhost:8080`

---

## ⚠️ Dicas

- Se der erro dizendo que `ng` não é reconhecido, rode:
  
  ```powershell
  npm install -g @angular/cli
  ```

- Se a aplicação Angular precisar acessar o backend, o backend deve permitir **CORS**.
  Exemplo no controller do Spring Boot:

  ```java
  @CrossOrigin(origins = "http://localhost:4200")
  ```

---

## ✅ Resultado esperado

- O frontend exibe a lista de tarefas e permite interações.
- O backend expõe a API e persiste os dados.

---

Feito com ❤️
