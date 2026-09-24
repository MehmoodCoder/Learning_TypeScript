# Learning TypeScript

✨ A beginner-friendly TypeScript practice repository for learning types, interfaces, classes, generics, and the TypeScript compiler workflow. 🚀

The repository currently contains one starter project, `First_TS_Project`, with hands-on notes and examples in `src/Notes.ts`.

---

## 🚀 Features

* **TypeScript Fundamentals:** Practice primitive types, arrays, tuples, unions, enums, and type assertions.
* **Object-Oriented TypeScript:** Learn type aliases, interfaces, classes, inheritance, and method contracts.
* **Functions and Generics:** Create typed functions, void functions, function interfaces, and reusable generic functions.
* **Strict Compiler Setup:** Compile source code with strict type checking, declarations, source maps, and modern JavaScript output.
* **Beginner-Friendly Examples:** Follow a single notes file that grows as new TypeScript concepts are learned.

---

## 🛠️ Tech Stack

* **Language:** TypeScript
* **Runtime:** Node.js
* **Package Manager:** npm
* **Compiler:** TypeScript (`tsc`)
* **Version Control:** Git, GitHub

---

## ✨ What You Will Practice

- 🔢 **Primitive Types** – `number`, `string`, `boolean`, and `any`
- 📚 **Arrays and Tuples** – Typed arrays, mixed arrays, tuples, and tuple arrays
- 🔀 **Unions and Enums** – Values that accept multiple types and named constant sets
- 🧱 **Types and Interfaces** – Object shapes, optional properties, readonly properties, and function contracts
- 🛠️ **Functions** – Parameter types, return types, and `void` functions
- 🧑‍💻 **Classes and Inheritance** – Constructors, implementation, subclasses, and `extends`
- 🧬 **Generics** – Reusable functions that preserve type information
- 🗺️ **Compiler Configuration** – `rootDir`, `outDir`, `target`, `module`, declarations, and source maps

---

## 📋 Prerequisites

- **Node.js** (LTS version recommended)
- **npm** (included with Node.js)
- Basic familiarity with JavaScript
- A terminal and a code editor such as VS Code

Check your installed versions:

```bash
node --version
npm --version
```

---

## ⚙️ Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Main_folder/Project_Folder
```

### 2. Global TypeScript Installation

Install TypeScript globally on your system to use `tsc` commands directly:

```bash
npm install -g typescript
```

### 3. Install Dependencies

TypeScript is already listed as a project dependency. Install it locally with:

```bash
npm install
```

Or

```bash
npm i typescript
```

Using the local dependency keeps the project compiler version consistent across different machines.

### 4. Initialize TypeScript Configuration

Generate the `tsconfig.json` file to configure compiler settings and strict type-checking rules:

```bash
tsc --init
```

> Note: This creates a tsconfig.json file in your root folder with "strict": true enabled by default.

### 5. Explore the Source File

Open `src/Notes.ts` and review the examples covering the concepts listed above.

---

## 🧰 TypeScript Commands

Run these commands from inside the `Project Folder` directory.

### Compile the Project

```bash
tsc
```

This reads `tsconfig.json`, compiles TypeScript files from `src/`, and writes JavaScript, declaration, and source map files to `dist/`.

### Watch for Changes

```bash
tsc --watch
```

The compiler will rebuild the project whenever a source file changes. Press `Ctrl + C` to stop watch mode.

### Run the Compiled JavaScript

```bash
node dist/FileName.js
```

### Run Compiled Code

```bash
node dist/FileName.js
```

### Type-Check Without Emitting Files

```bash
tsc --noEmit
```

This checks the project for type errors without creating or changing files in `dist/`.

---

## ⚡ Optional: Convenient npm Scripts

You can add these shortcut scripts to your package.json file:

```json
"scripts": {
  "build": "tsc",
  "watch": "tsc --watch",
  "start": "tsc && node dist/Notes.js",
  "check": "tsc --noEmit"
}
```

Now you can run:

* `npm run build` to compile
* `npm run watch` for auto-rebuild
* `npm start` to compile and run in one step
* `npm run check` for quick type checks

---

## 🗂️ Project Structure

**Generated:** 9/24/2026, 6:46:44 AM
**Root Path:** `workspace\Learning_TypeScript`

```text
Learning_TypeScript/
├── 📄 README.md
├── ⚙️ .gitignore
└── 📁 First_TS_Project/
	├── 📁 src/
	│   └── 📄 Notes.ts
	├── 📄 package.json
	├── ⚙️ package-lock.json
	├── ⚙️ tsconfig.json
	└── 📁 dist/              # Generated after compilation
```

### ⚙️ Compiler Configuration

The project uses `tsconfig.json` with these important settings:

* `rootDir: "./src"` – Defines the source directory.
* `outDir: "./dist"` – Defines the compiled output directory.
* `target: "esnext"` – Emits modern JavaScript syntax.
* `module: "nodenext"` – Uses Node.js-compatible module behavior.
* `strict: true` – Enables strict type checking.
* `sourceMap: true` – Generates source maps for debugging.
* `declaration: true` – Generates `.d.ts` declaration files.

---

## 📚 Learning Resources

* [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) – Official TypeScript concepts and language guide
* [TypeScript Playground](https://www.typescriptlang.org/play) – Experiment with TypeScript in the browser
* [Node.js Documentation](https://nodejs.org/docs/latest/api/) – Learn about the JavaScript runtime
* [npm Documentation](https://docs.npmjs.com/) – Manage packages and project scripts
* [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) – Review JavaScript foundations

---

## 🤝 Contributing

Contributions and learning improvements are welcome.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/new-example`
3. Add or improve a TypeScript example.
4. Run `npx tsc --noEmit` to check for type errors.
5. Commit and push your changes.
6. Open a Pull Request.

---

## 👤 Author

**MehmoodCoder**

- 🔗 GitHub: [MehmoodCoder](https://github.com/MehmoodCoder)
- 🌐 Portfolio: [mh56-portfolio.vercel.app](https://mh56-portfolio.vercel.app)

---

## 📝 Changelog

### v1.0.0 - Initial Learning Project

- ✨ Added the `First_TS_Project` TypeScript workspace.
- 📘 Added examples for core TypeScript types and language features.
- ⚙️ Added strict compiler configuration with source maps and declarations.
- 🚀 Added compilation and execution instructions.

---

### *Happy Coding without Chai ! ☕*
