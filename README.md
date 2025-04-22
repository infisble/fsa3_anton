# fsa3_anton 



## my stack 

### Frontend:
- Angular 
- TypeScript

### Backend:
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- PostgreSQL

---

## 🚀 how to run project

### 🔧 required

- Node.js
- Yarn or  npm
- PostgreSQL
- Java 17+
- Maven

---

## 1️⃣ setup db

run postgre and setup db

```bash
psql -U postgres
```
How to connect the frontend with backend
Run this backend with the command:
```bash
./mvnw spring-boot:run
```
Make sure it works on http://localhost:8080

In the Angular project (fsa3_anton), in the environment.ts file, specify:


```bash
export const environment = {
  production: false,
  apiUrl: 'http://localhost:8080/api'
};
```
Login and passwords can be registered via POST 
```bash
/api/auth/register
```
and then login via POST 
```bash
/api/auth/login.
```

