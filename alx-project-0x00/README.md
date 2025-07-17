# 🏡 ALX Project 0x00 - Airbnb Clone (Next.js, TypeScript, TailwindCSS)

This project is designed to **teach the fundamentals of building modern web applications using Next.js, React, and TypeScript** while replicating core features of Airbnb’s UI, including property listings with images, ratings, and interactive reusable components.

---

## 🎯 Learning Objectives

By completing this project, you will:

✅ Scaffold a **Next.js project with TypeScript** using `create-next-app`  
✅ Understand **Next.js folder structure and organization**  
✅ Implement **basic routing** using the **Pages Router**  
✅ Create **reusable, typed React components** with **TypeScript**  
✅ Work with **TypeScript interfaces** for component props  
✅ Manage **assets and static files** within Next.js  
✅ Apply **component composition principles** for modular design  
✅ Develop **responsive designs with Tailwind CSS**  
✅ Set up and configure **ESLint for code quality**  

---

## 🛠️ Requirements

✅ Node.js (v16+)  
✅ npm or yarn  
✅ Visual Studio Code (recommended)  
✅ Next.js v13+  
✅ TypeScript  
✅ Tailwind CSS  
✅ ESLint

---

## 📂 Best Practices

### 🗂️ Project Structure
- **`/components`**: Contains reusable UI components (Card, Pill, Button)
- **`/interfaces`**: Centralized TypeScript interfaces for consistent typing
- **`/pages`**: Follows Next.js Pages Router conventions
- **`/public/assets/images`**: Stores static images used across components

### 🧩 Component Design
- Components typed with **TypeScript interfaces**
- Reusable components accepting props for dynamic data
- Modular, single-responsibility design for maintainability

### 🧹 Code Quality
- **ESLint configured** for consistent styling and linting
- **TypeScript** for type safety
- Consistent arrow function syntax

### 🎨 Styling
- **Tailwind CSS** for utility-first styling
- Responsive design for mobile and desktop
- Consistent spacing and typography scales

### 🚀 Performance
- **Next.js `Image` component** for optimized images
- Automatic code splitting by Next.js
- Only essential dependencies included

---

## 🚧 Project Tasks Overview

✅ **Task 0: Scaffold Project**  
Create a Next.js app with TypeScript, ESLint, and TailwindCSS using:
```bash
npx create-next-app@latest alx-project-0x00 --typescript
```

✅ **Task 1: Setup Project Directories**  
Create `/components` and `/interfaces`, refactor `index.tsx` to use an arrow function and export default at the bottom.

✅ **Task 2: Basic Routing**  
Implement new pages (`landing.tsx`, `about.tsx`) using **Pages Router**.

✅ **Task 3: Rendering Components**  
Create reusable `Card` and `Pill` components with TailwindCSS styling.

✅ **Task 4: Using Components**  
Import and use `Card` inside `landing.tsx`, demonstrating reusability.

✅ **Task 5: Typing Components**  
Use TypeScript interfaces for props (`PillProps`) to make components dynamic.

✅ **Task 6: Advanced - Button Component**  
Create a `Button` component accepting `title` and `style` props, use different shapes and sizes on the landing page.

✅ **Task 7: Manual Review**  
Submit for review ensuring:
- All components typed and reusable
- Pages render cleanly without errors
- Linting passes with no issues
- Responsive design verified

---

## 🚀 Running the Project Locally

1️⃣ **Clone the Repository:**
```bash
git clone https://github.com/your-username/alx-project-0x00-setup.git
cd alx-project-0x00
```

2️⃣ **Install Dependencies:**
```bash
npm install
```

3️⃣ **Run the Development Server:**
```bash
npm run dev -- -p 3000
```

4️⃣ Visit [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## ⚠️ Note on Learning

While **copying and pasting code may feel quick**, it often limits deep understanding. For your best learning outcome:

✅ **Read and understand each instruction** before implementing  
✅ **Type out the code manually** to grasp structure and syntax  
✅ **Experiment and test components** to see how props, state, and layout interact  
✅ **Debug actively** to build your problem-solving skills

Hands-on practice builds mastery. Keep coding!

---

## 🤝 Contributing

Feel free to fork this repository, open pull requests, and suggest improvements.

---

Happy Coding 🚀✨
