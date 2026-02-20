
# Frontend – Setup & Run Guide

## 📦 Prerequisites

Make sure you have installed:

* **Node.js** (v16 or higher recommended)
  Check version:

  ```bash
  node -v
  ```

* **npm** (comes with Node)

  ```bash
  npm -v
  ```

---

## 🚀 Installation

Navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Run Development Server

Start the Vite dev server:

```bash
npm run dev
```

You should see output like:

```
VITE vX.X.X  ready in XXX ms
➜  Local:   http://localhost:5173/
```

Open the shown URL in your browser.

---

## 🏗 Build for Production

To create a production build:

```bash
npm run build
```

The build files will be generated inside:

```
dist/
```


## 📁 Project Structure

```
frontend/
│
├── public/          # Static assets
├── src/             # Source code
├── dist/            # Production build (generated)
├── index.html       # App entry HTML
├── package.json     # Dependencies & scripts
├── vite.config.js   # Vite configuration
