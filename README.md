
---

## 🛠️ Tech Stack
### Backend
- [NestJS](https://nestjs.com/)  
- [Prisma ORM](https://www.prisma.io/)  
- [PostgreSQL](https://www.postgresql.org/)  
- JWT Authentication & Bcrypt  

### Frontend
- [React](https://reactjs.org/) + Vite  
- [Redux Toolkit](https://redux-toolkit.js.org/)  
- [TailwindCSS](https://tailwindcss.com/)  

---

## ⚙️ Requirements
- Node.js >= 18  
- PostgreSQL (local or cloud)  
- npm or yarn  

---

## ▶️ Running Locally
### Backend
```bash
cd backend
npm install
npx prisma migrate dev --name init
npm run prisma:seed
npm run start:dev
