# ⚡ Brovite Demo

A minimal demo project for **Brovite**.

Brovite is a lightweight Vite-like development tool and bundler for modern ES module projects.

---

## Prerequisites

Install Brovite globally (one time only):

```bash
npm install -g brovite
```

After that, the `brovite` command will be available in any project folder.

---

## Run the Demo

```bash
git clone https://github.com/your-username/brovite-demo.git
cd brovite-demo
brovite dev
```

Open your browser at:

```text
http://localhost:3000
```

---

## Optional npm Scripts

This project includes scripts in `package.json`:

```json
{
  "scripts": {
    "dev": "brovite dev",
    "build": "brovite build",
    "preview": "brovite preview"
  }
}
```

So you can also run:

```bash
npm run dev
npm run build
npm run preview
```

These are shortcuts for the equivalent Brovite commands.

---

## Build for Production

```bash
brovite build
```

Output will be generated in:

```text
dist/
```

---

## Preview the Production Build

```bash
brovite preview
```

---

## Project Structure

```text
brovite-demo/
├── index.html
├── main.js
├── package.json
└── README.md
```

---

## Notes

- Brovite is installed globally, so users only need to install it once.
- After installation, `brovite dev` works in any project.
- `npm run dev` is optional and simply runs `brovite dev`.

---

## Links

- npm package: https://www.npmjs.com/package/brovite
- Source repository: https://github.com/your-username/brovite
