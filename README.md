# React Blog Website

## 🚀 Introduction
A fully functional blog website built with **React.js** and **Next.js**, featuring dynamic blog posts, a responsive design, and integration with **Supabase** for backend services.

## 🌟 Features
- ✨ **Next.js for SSR & SEO Optimization**
- 📝 **Dynamic Blog Posts**
- 🎨 **Responsive UI with Tailwind CSS**
- 🔥 **Supabase Integration for Database & Auth**
- 🌍 **Deployed on Vercel**

## 📂 Project Structure
```
react-blog-website-master/
│── app/               # Next.js App Directory
│── components/        # Reusable UI Components
│── pages/             # Next.js Pages
│── public/            # Static Assets
│── styles/            # Global Styles
│── .env.local         # Environment Variables
│── next.config.js     # Next.js Configuration
│── package.json       # Dependencies & Scripts
```

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/HarshTiwari14/react-blog-website-master.git
cd react-blog-website-master
```

### 2️⃣ Install Dependencies
```sh
npm install
# or
yarn install
```

### 3️⃣ Configure Environment Variables
Create a `.env.local` file in the root directory and add:
```env
SUPABASE_URL=your-supabase-url
SUPABASE_ANON_KEY=your-anon-key
```

### 4️⃣ Start Development Server
```sh
npm run dev
# or
yarn dev
```

Server will run at: **http://localhost:3000/**

## 🚀 Deployment
### Deploy on **Vercel**
```sh
vercel
```
Make sure to set your **environment variables** in Vercel's dashboard.

## 🛠️ Tech Stack
- **Frontend:** React.js, Next.js, Tailwind CSS
- **Backend:** Supabase (PostgreSQL)
- **Authentication:** Supabase Auth
- **Hosting:** Vercel

## 📜 License
This project is **MIT Licensed**. Feel free to contribute and improve! 🚀

---
### 💡 Contributing
1. Fork the repo & clone locally.
2. Create a new branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add new feature'`
4. Push to branch: `git push origin feature-name`
5. Create a PR & discuss changes!

Happy Coding! 🎉

