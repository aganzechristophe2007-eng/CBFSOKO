# CBFSOKO — Marketplace Full-Stack (Bukavu / Sud-Kivu)

## Prérequis
- Node.js (v18+)
- PostgreSQL (ou Neon DB)

## 1. Installation du Backend
```bash
cd backend
npm install
cp .env.example .env
```
Remplissez votre `DATABASE_URL` dans le fichier `.env`.

```bash
# Exécuter les migrations Prisma
npx prisma migrate dev --name init

# Créer votre compte Super Administrateur
npm run create-admin

# Démarrer le serveur de développement
npm run dev
```

## 2. Installation du Frontend
```bash
cd frontend
npm install
npm run dev
```
