---

# SAAS Backend Setup with Prisma & PostgreSQL

This project is a backend setup for a SaaS application using **Express.js**, **TypeScript**, **Prisma ORM**, and **PostgreSQL**.

---

## 📦 Initial Setup Commands

Execute the following commands step-by-step to set up the project:

```bash
# 1. Create project folder
mkdir SAAS-backend

# 2. Navigate into the folder
cd SAAS-backend

# 3. Initialize npm project
npm init -y

# 4. Install required dependencies
npm install express cors dotenv @prisma/client

# 5. Install development dependencies
npm install -D typescript ts-node-dev prisma @types/express @types/node

# 6. Initialize TypeScript configuration
npx tsc --init

# 7. Initialize Prisma
npx prisma init

# 8. Run initial Prisma migration (replace 'init' with your preferred name)
npx prisma migrate dev --name init
```

---

## 📊 View the Prisma Database (GUI)

To visually inspect your database like in **MongoDB Compass**, you can use:

```bash
npx prisma studio
```

This will open up **Prisma Studio**, an interactive GUI to view and manage your database models and records.

---

## ✅ You're all set!

Now your SaaS backend project is fully configured using:

* **Express.js** for server setup
* **TypeScript** for type-safe development
* **Prisma ORM** for database interaction
* **PostgreSQL** as the database

---
