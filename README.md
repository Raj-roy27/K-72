# K-72

A modern, responsive web application built with React and Vite. K-72 is a multi-page frontend project featuring dynamic navigation, project showcases, and agency information.

---

## 🚀 Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI library |
| Vite | Build tool & dev server |
| React Router | Client-side routing |
| Context API | Global state management |
| ESLint | Code quality & linting |

---

## 📁 Project Structure

```
K-72/
├── public/               # Static assets
├── src/
│   ├── assets/           # Images, fonts, icons
│   ├── components/
│   │   ├── common/       # Reusable UI components
│   │   ├── home/         # Home page components
│   │   ├── Navigation/   # Navbar and routing components
│   │   └── projects/     # Project-related components
│   ├── context/
│   │   └── NavContext.jsx  # Navigation state (Context API)
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Projects.jsx
│   │   └── Agence.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) v18 or higher
- npm v9 or higher

Verify your setup:
```bash
node -v
npm -v
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Raj-roy27/K-72.git
cd K-72
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

The app will be running at `http://localhost:5173`

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint checks |

---

## 🌍 Pages

| Route | Page | Description |
|---|---|---|
| `/` | Home | Landing page |
| `/projects` | Projects | Project showcase |
| `/agence` | Agence | Agency information |

---

## 🔧 Environment Variables

This project currently does not require environment variables.  
If added in the future, copy `.env.example` to `.env` and fill in the values:

```bash
cp .env.example .env
```

> ⚠️ Never commit `.env` files to version control.

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feat/your-feature-name`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feat/your-feature-name`
5. Open a Pull Request

### Commit Message Convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:     New feature
fix:      Bug fix
chore:    Config, tooling, setup
refactor: Code restructuring
docs:     Documentation changes
style:    Formatting only (no logic change)
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Raj Roy**  
GitHub: [@Raj-roy27](https://github.com/Raj-roy27)
