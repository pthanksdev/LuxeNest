# 🏠 LuxeNest

<div align="center">

### *Elevate Your Living Experience*

[![React](https://img.shields.io/badge/React-18.0+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0+-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-Latest-FF0055?style=for-the-badge&logo=framer&logoColor=white)](https://www.framer.com/motion/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

[🌐 Live Demo](https://luxenest-eight.vercel.app/) • [🐛 Report Bug](https://github.com/pthanksdev/LuxeNest/issues) • [✨ Request Feature](https://github.com/pthanksdev/LuxeNest/issues)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Configuration](#-configuration)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About

**LuxeNest** is a modern, responsive real estate web application designed to help users discover their dream homes with elegance and ease. Built with cutting-edge technologies, LuxeNest offers a seamless browsing experience across all devices.

### Why LuxeNest?

- 🎨 **Beautiful UI/UX** - Sleek, modern design with smooth animations
- 📱 **Fully Responsive** - Perfect experience on mobile, tablet, and desktop
- ⚡ **Lightning Fast** - Optimized performance for quick loading
- 🔍 **Easy Navigation** - Intuitive interface for effortless browsing
- 🎭 **Animated Interactions** - Engaging micro-animations throughout

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🏡 Core Features
- **Property Listings** - Browse extensive real estate options
- **Advanced Search** - Filter by location, price, size
- **Property Details** - Comprehensive information & images
- **Contact Forms** - Easy inquiry submission
- **Responsive Design** - Mobile-first approach

</td>
<td width="50%">

### 🚀 Technical Features
- **React Router** - Smooth page navigation
- **Framer Motion** - Beautiful animations
- **Tailwind CSS** - Utility-first styling
- **Mobile Menu** - Hamburger navigation
- **SEO Optimized** - Better search visibility

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Frontend | Styling | Animation | Routing | Build Tool |
|:--------:|:-------:|:---------:|:-------:|:----------:|
| ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) | ![Tailwind](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | ![Framer](https://img.shields.io/badge/-Framer-FF0055?style=flat-square&logo=framer&logoColor=white) | ![Router](https://img.shields.io/badge/-Router-CA4245?style=flat-square&logo=react-router&logoColor=white) | ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |

</div>

### Dependencies

```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-router-dom": "^6.20.0",
  "framer-motion": "^10.16.0",
  "lucide-react": "^0.263.1"
}
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16.0 or higher)
- **npm** or **yarn**
- **Git**

### Installation

Follow these steps to set up LuxeNest locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/p-thanks/LuxeNest.git
   cd LuxeNest
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   ```
   Navigate to http://localhost:5173
   ```

### Quick Setup

```bash
# One-line setup
git clone https://github.com/p-thanks/LuxeNest.git && cd LuxeNest && npm install && npm run dev
```

---

## 📁 Project Structure

```
LuxeNest/
│
├── 📂 public/
│   └── favicon.ico
│
├── 📂 src/
│   ├── 📂 assets/
│   │   ├── logo.png
│   │   └── images/
│   │
│   ├── 📂 components/
│   │   ├── 📂 Navbar/
│   │   │   ├── Navbar.jsx
│   │   │   └── Navbar.css
│   │   ├── 📂 Hero/
│   │   ├── 📂 Services/
│   │   ├── 📂 Projects/
│   │   └── 📂 Footer/
│   │
│   ├── 📂 pages/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Services.jsx
│   │   ├── Projects.jsx
│   │   └── Contact.jsx
│   │
│   ├── 📂 utils/
│   │   └── constants.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── 📄 package.json
├── 📄 vite.config.js
├── 📄 tailwind.config.js
├── 📄 .gitignore
└── 📄 README.md
```

---

## ⚙️ Configuration

### Tailwind CSS Setup

Customize your theme in `tailwind.config.js`:

```javascript
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        primary: "#6366f1",
        secondary: "#8b5cf6",
      },
      fontFamily: {
        sans: ['Inter', 'sans-serif'],
      },
    },
  },
  plugins: [],
}
```

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=your_api_url
VITE_API_KEY=your_api_key
```

---

## 🌐 Deployment

### Build for Production

```bash
npm run build
# or
yarn build
```

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/pthanksdev/luxenest)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Guidelines

- Follow the existing code style
- Write meaningful commit messages
- Add comments for complex logic
- Update documentation as needed
- Test your changes thoroughly

---

## 📊 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/pthanksdev/luxenest?style=social)
![GitHub forks](https://img.shields.io/github/forks/pthanksdev/luxenest?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/pthanksdev/luxenest?style=social)

![GitHub issues](https://img.shields.io/github/issues/pthanksdev/luxenest)
![GitHub pull requests](https://img.shields.io/github/issues-pr/pthanksdev/luxenest)
![GitHub last commit](https://img.shields.io/github/last-commit/pthanksdev/luxenest)

</div>

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 LuxeNest

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

---

## 📧 Contact

<div align="center">

**Your Name** - [@yourtwitter](https://twitter.com/Pthanks01)

Project Link: [https://github.com/pthanksdev/luxenest](https://github.com/pthanksdev/luxenest)

**Email:** [pthanksdev](mailto:paulthanksgiving@gmail.com)

</div>

---

## 🙏 Acknowledgments

- [React Documentation](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Lucide Icons](https://lucide.dev/)
- [Vercel](https://vercel.com/)

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

Made with ❤️ by [Your Name](https://github.com/yourusername)

</div>
