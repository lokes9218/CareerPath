# 🚀 CareerPath – Interactive Career Development Platform

## 📌 Overview

**CareerPath** is a modern, interactive web application designed to guide users through their professional journey. It provides visually engaging experiences, personalized learning paths, and insightful dashboards to help users explore, learn, and grow in their careers.

Built with cutting-edge technologies like **Next.js 14**, **React 18**, and **Three.js**, the platform focuses on performance, scalability, and immersive UI/UX.

---

## ✨ Features

* 🎯 **Career Guidance Modules**

  * Learnscape: Structured learning paths
  * Launchpad: Career starting tools
  * Rewind: Progress tracking & reflection

* 📊 **Interactive Dashboards**

  * Nutrition-style analytics dashboard
  * Data visualization using charts (Recharts)

* 🌌 **3D & Animated UI**

  * Three.js + React Three Fiber integration
  * Particle effects and animated backgrounds
  * Smooth transitions using Framer Motion

* 🔐 **Authentication**

  * Secure user authentication using Clerk

* ⚡ **Performance Optimized**

  * Server-side rendering (SSR) with Next.js
  * Optimized assets and modular components

* 🛠 **Error Monitoring**

  * Integrated Sentry for real-time error tracking

---

## 🏗️ Project Structure

```
CareerPath-main/
│
├── app/                    # Next.js App Router
│   ├── api/                # Backend API routes
│   ├── data/               # Static JSON data
│   ├── learnscape/         # Learning module
│   ├── launchpad/          # Career starter tools
│   ├── rewind/             # Progress tracking
│   ├── nutrition-dashboard/ # Analytics dashboard
│   └── layout.tsx          # Root layout
│
├── components/             # Reusable UI components
│   ├── ui/                 # Core UI elements
│   ├── Hero.tsx
│   ├── Footer.tsx
│   └── ...
│
├── public/                 # Static assets
├── styles/                 # Global styles
├── package.json            # Dependencies & scripts
└── next.config.mjs         # Next.js configuration
```

---

## 🧰 Tech Stack

### Frontend

* **Next.js 14 (App Router)**
* **React 18**
* **TypeScript**

### UI & Styling

* **Tailwind CSS**
* **Framer Motion**
* **Lucide Icons / Tabler Icons**

### Visualization & Graphics

* **Three.js**
* **React Three Fiber**
* **Recharts**

### Backend & Services

* **Next.js API Routes**
* **Clerk Authentication**
* **Sentry Monitoring**

### Deployment

* **Vercel**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/careerpath.git
cd careerpath
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file in the root directory and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret
SENTRY_DSN=your_sentry_dsn
```

### 4️⃣ Run Development Server

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---

## 📦 Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build production app
npm run start     # Run production server
npm run lint      # Lint code
npm run deploy    # Deploy to Vercel
```

---

## 🌐 Deployment

This project is optimized for **Vercel** deployment.

```bash
npm run deploy
```

Or connect your GitHub repo directly to Vercel for CI/CD.

---

## 🧪 Future Enhancements

* 🤖 AI-based career recommendations
* 📈 Advanced analytics dashboard
* 🌍 Multi-language support
* 📱 Mobile app integration
* 🧠 Personalized learning engine

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Developed with ❤️ by  Lokeswarann S 

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub and share it!

---
