
# MovimentacoesProducts

Sistema de movimentações de produtos desenvolvido com **Laravel** no back-end e **Vue.js** no front-end, utilizando **MySQL** para o banco de dados.

---

## 📋 **Pré-requisitos**

Certifique-se de que o ambiente de desenvolvimento está configurado com as seguintes ferramentas:

- **PHP** >= 8.2
- **Composer** >= 2.0
- **Node.js** >= 16.x
- **npm** ou **yarn**
- **MySQL**
- **Laravel** >= 10.x
- **Vue.js** >= 3.x

---

## ⚙️ **Instalação**

### 1️⃣ Clone o Repositório

```bash
git clone https://github.com/JJoseNetto/MovimentacoesProducts.git
cd MovimentacoesProducts
```

---

### 2️⃣ Configuração do Back-end (Laravel)

#### Instale as dependências do Laravel:
```bash
composer install
```

#### Configure o arquivo `.env`:
1. Copie o arquivo de exemplo:
   ```bash
   cp .env.example .env
   ```
2. Atualize o arquivo `.env` com as credenciais do banco de dados:
   ```dotenv
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=movimentacoes_products
   DB_USERNAME=seu_usuario
   DB_PASSWORD=sua_senha
   ```

#### Gere a chave da aplicação:
```bash
php artisan key:generate
```

#### Execute as migrações e seeders:
```bash
php artisan migrate --seed
```

#### Inicie o servidor Laravel:
```bash
php artisan serve
```

---

### 3️⃣ Configuração do Front-end (Vue.js)

#### Instale as dependências do Node.js:
```bash
npm install
```

#### Compile os assets para desenvolvimento:
```bash
npm run dev
```

---

### 4️⃣ Configuração do Banco de Dados

Certifique-se de que o banco de dados MySQL está configurado e rodando. O script de migração criará as tabelas necessárias e o seeder inicializará os dados básicos.

---

## 🚀 **Comandos Básicos**

### Rodar servidor de desenvolvimento:
```bash
php artisan serve
npm run dev
```

### Rodar migrações e reiniciar os dados:
```bash
php artisan migrate:fresh --seed
```

---

## 📂 **Estrutura do Projeto**

- **Back-end (Laravel)**: 
  - Controladores, rotas e lógica do sistema.
  - Localizado em `app/`, `routes/` e `database/`.
  
- **Front-end (Vue.js)**:
  - Componentes, rotas e interação do usuário.
  - Localizado em `resources/js/` e `resources/views/`.

---

## 🤝 **Contribuição**

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações: `git checkout -b minha-feature`.
3. Commit suas alterações: `git commit -m "Minha nova feature"`.
4. Envie para o repositório principal: `git push origin minha-feature`.
5. Abra um Pull Request.

---

## 📞 **Suporte**
Se encontrar algum problema, entre em contato pelo repositório ou abra uma issue.

---

Com esses passos e comandos, seu projeto estará configurado e funcional! Se precisar de algo mais específico, é só pedir. 😊

