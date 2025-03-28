# H8Mate - Classmate Tier List Web App

## 📌 About the Project
H8Mate is a **tier list ranking** web app built using the **T3 Stack** (Next.js, TypeScript, tRPC, TailwindCSS, and Prisma). It allows users to drag and drop classmates into different tiers for fun and interactive ranking.

## 🚀 Features
- **Drag-and-drop interface** for ranking classmates.
- **Real-time updates** using React state.
- **Interactive UI** with smooth animations.
- **Deployed on Vercel** for easy access.

## 🛠️ Tech Stack
- **Frontend**: Next.js, React, TypeScript, TailwindCSS
- **Backend**: tRPC (no database for now)
- **State Management**: React Hooks
- **Deployment**: Vercel

## 📂 Folder Structure
```
H8Mate/
│── src/
│   ├── app/
│   │   ├── _components/
│   │   │   ├── TierList.tsx
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   ├── server/
│   │   ├── api/
│   │   │   ├── root.ts
│   ├── styles/
│   │   ├── globals.css
│── public/
│── .env
│── package.json
│── README.md
```

## 🔧 Setup & Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/h8mate.git
cd h8mate
```

### 2️⃣ Install dependencies
```sh
pnpm install  # or npm install
```

### 3️⃣ Setup environment variables
Create a **.env** file and add placeholders:
```sh
AUTH_SECRET=placeholder_secret
AUTH_DISCORD_ID=placeholder_discord_id
AUTH_DISCORD_SECRET=placeholder_discord_secret
DATABASE_URL=https://example.com
NODE_ENV=development
```

### 4️⃣ Run the development server
```sh
pnpm run dev  # or npm run dev
```

## 🚀 Deployment on Vercel
### **Step 1: Push to GitHub**
```sh
git add .
git commit -m "Initial commit"
git push origin main
```

### **Step 2: Deploy**
1. Go to **[Vercel](https://vercel.com/)** and log in.
2. Click **New Project** → Import your GitHub repo.
3. Set environment variables in **Vercel Settings**.
4. Click **Deploy** and wait for the build to complete.
5. 🎉 Done! Your project is now live!

## 🛠️ Troubleshooting
### ❌ `Cannot find module '@trpc/react-query'`
- Run: `pnpm install @trpc/react-query`

### ❌ `Error: Command "pnpm run build" exited with 1`
- Check your **environment variables** in `.env` or Vercel.

### ❌ `Module not found: Can't resolve './styles/globals.css'`
- Ensure `globals.css` exists inside `styles/` and is correctly imported.

## 🎯 Future Improvements
- Add a database for **saving rankings**.
- Implement **authentication**.
- Improve **UI/UX animations**.

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m "Added new feature"`
4. Push to GitHub and submit a Pull Request!

## 📜 License
MIT License © 2025 H8Mate Team

