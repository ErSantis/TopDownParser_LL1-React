
# LL(1) Grammar Analyzer — Non-Recursive Descent Parser

A web-based tool built in **React + TypeScript** for analyzing context-free grammars and simulating LL(1) parsers. This tool helps users understand and visualize compiler construction techniques such as First/Follow sets, left recursion removal, and predictive parsing.

---

## 📚 Features

- ✍️ Input grammar via web UI
- 🧮 Calculate First and Follow sets
- 🔁 Remove **left recursion**
- 🪄 Apply **left factoring**
- 📊 Generate LL(1) parsing table (M-table)
- ⚙️ Simulate non-recursive descent parsing
- 🌐 Interactive and responsive interface

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 16.x
- npm or yarn

### Installation

```bash
git clone https://github.com/your-username/LL1-grammar-analyzer.git
cd LL1-grammar-analyzer
npm install
```

### Run Locally

```bash
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🧠 How It Works

1. **Input Grammar**: Define non-terminals, terminals, and production rules.
2. **Preprocessing**: Handles elimination of left recursion and left factoring.
3. **First/Follow Sets**: Uses algorithms to derive sets for each non-terminal.
4. **M-Table Construction**: Based on the First and Follow sets, builds parsing table.
5. **Parser Simulation**: Enter input string and see the parsing process in action.

---

## 🛠 Technologies Used

| Area         | Tech Stack            |
|--------------|------------------------|
| Frontend     | React, TypeScript      |
| Tooling      | Vite                   |
| State & Logic| Custom Context + Hooks|
| Styling      | CSS Modules            |

---

## 📦 Folder Structure

```
src/
├── components/       # UI components (input, results, simulation)
├── styles/           # CSS Modules for each component
├── utils/            # Grammar logic (first, follow, m-table, transformations)
├── types/            # TypeScript types
└── main.tsx          # App entry point
```

---

## 🧪 Example Use Case

- Input Grammar:
  ```
  S -> A a | b
  A -> A c | d
  ```
- First & Follow sets are calculated.
- Left recursion removed from `A -> A c | d`.
- Predictive table created and parsing simulated.

---

## 🌐 Live Demo

 [Vercel](https://top-down-parser-psi.vercel.app/) 

---

## 📄 License

[MIT License](./LICENSE)

---

## 🙌 Authors

Developed as a compiler theory project by a team passionate about education and software engineering.

# LL(1) Grammar Analyzer — Non-Recursive Descent Parser

A web-based tool built in **React + TypeScript** for analyzing context-free grammars and simulating LL(1) parsers. This tool helps users understand and visualize compiler construction techniques such as First/Follow sets, left recursion removal, and predictive parsing.

---

## 📚 Features

- ✍️ Input grammar via web UI
- 🧮 Calculate First and Follow sets
- 🔁 Remove **left recursion**
- 🪄 Apply **left factoring**
- 📊 Generate LL(1) parsing table (M-table)
- ⚙️ Simulate non-recursive descent parsing
- 🌐 Interactive and responsive interface

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 16.x
- npm or yarn

### Installation

```bash
git clone https://github.com/your-username/LL1-grammar-analyzer.git
cd LL1-grammar-analyzer
npm install
```

### Run Locally

```bash
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🧠 How It Works

1. **Input Grammar**: Define non-terminals, terminals, and production rules.
2. **Preprocessing**: Handles elimination of left recursion and left factoring.
3. **First/Follow Sets**: Uses algorithms to derive sets for each non-terminal.
4. **M-Table Construction**: Based on the First and Follow sets, builds parsing table.
5. **Parser Simulation**: Enter input string and see the parsing process in action.

---

## 🛠 Technologies Used

| Area         | Tech Stack            |
|--------------|------------------------|
| Frontend     | React, TypeScript      |
| Tooling      | Vite                   |
| State & Logic| Custom Context + Hooks|
| Styling      | CSS Modules            |

---

## 📦 Folder Structure

```
src/
├── components/       # UI components (input, results, simulation)
├── styles/           # CSS Modules for each component
├── utils/            # Grammar logic (first, follow, m-table, transformations)
├── types/            # TypeScript types
└── main.tsx          # App entry point
```

---

## 🧪 Example Use Case

- Input Grammar:
  ```
  S -> A a | b
  A -> A c | d
  ```
- First & Follow sets are calculated.
- Left recursion removed from `A -> A c | d`.
- Predictive table created and parsing simulated.

---

## 🌐 Live Demo

_Coming Soon_ (or host it on [Vercel](https://vercel.com) / [Netlify](https://netlify.com) for easy sharing)

---

## 📄 License

[MIT License](./LICENSE)

---

## 🙌 Authors

Developed as a compiler theory project by me :)