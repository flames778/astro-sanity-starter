# 🚀 Astro Netlify Sanity Starter

Astro Netlify Sanity Starter is a modern full-stack starter template that combines **Astro**, **Sanity CMS**, and **Netlify** to build fast, scalable, and content-driven websites. The project includes visual editing, headless content management, and a streamlined development workflow for developers and content creators.

## ✨ Features

- ⚡ High-performance static site generation with Astro
- 📝 Headless CMS powered by Sanity
- 🎨 Netlify Visual Editor integration
- 🔄 Real-time content editing and preview
- 📱 Responsive and modern design
- 🚀 Optimised deployment on Netlify
- 🔐 Secure environment variable configuration
- 🛠️ Developer-friendly project structure

---

## 🛠️ Tech Stack

- Astro
- Sanity CMS
- Netlify
- JavaScript
- Node.js
- Stackbit Visual Editor

---

## 📦 Prerequisites

- Node.js v20+
- npm
- (Optional) nvm for Node version management
- Sanity CLI
- Stackbit CLI

---

## 🚀 Installation

### Clone the Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
npm install
```

### Login to Sanity

```bash
npm install -g @sanity/cli
sanity login
```

### Create a Sanity Project

```bash
npm run create-project
```

### Import Sample Content

```bash
npm run import <projectId>
```

### Configure Environment Variables

Create a `.env` file in the project root.

```env
SANITY_PROJECT_ID=your_project_id
SANITY_DATASET=production
SANITY_TOKEN=your_token
```

---

## ▶️ Run the Development Server

```bash
npm run dev
```

---

## 📝 Run Sanity Studio

```bash
cd studio
npm install
sanity dev
```

Open:

```
http://localhost:3333
```

---

## 🎨 Enable Netlify Visual Editor

Install the Stackbit CLI:

```bash
npm install -g @stackbit/cli
```

Start the editor:

```bash
stackbit dev
```

---

## 📂 Project Structure

```
/
├── src/
├── public/
├── studio/
├── astro.config.mjs
├── package.json
└── README.md
```

---

## 🎯 Use Cases

- Business websites
- Portfolio websites
- Blogs
- Documentation sites
- Marketing landing pages
- Headless CMS projects
- JAMstack applications

---

## 🔮 Future Improvements

- Authentication support
- Multi-language content
- SEO enhancements
- Analytics integration
- Dark mode
- Image optimisation
- Content scheduling

---

## 👨‍💻 Author

**Evans Emmanuel Davou**

AI Engineer • Cybersecurity Student • Full-Stack Developer

---

## 📄 License

This project is intended for educational, personal, and commercial web development purposes.
