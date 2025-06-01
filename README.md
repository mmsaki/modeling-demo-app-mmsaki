# Lean 4 Project Setup

This project is written in [Lean 4](https://leanprover.github.io/) — a theorem prover and functional programming language.

## 🚀 Quickstart

### 1. Install Lean (via `elan`)

`elan` is the version manager and installer for Lean. Install it by running:

```bash
curl https://elan.lean-lang.org/elan-init.sh -sSf | sh
````

> [!NOTE]
> This will install `elan` and the default Lean toolchain. Restart your terminal after installation if needed.

To confirm it's working:

```bash
lean --version
```

### 2. Clone the project

```bash
git clone https://github.com/formalmind/lean-template.git
cd lean-template
```

### 3. Set up dependencies

This project uses [`lake`](https://github.com/leanprover/lake), Lean's build system and package manager. To fetch dependencies:

```bash
lake update
```

### 4. Build the project

```bash
lake build
```

You can now explore the code and proofs.

### 5. Optional: Run Lean files interactively

If you're using VS Code, install the **Lean 4 extension** for interactive development and proof checking.

---

## 🧠 Helpful Commands


| Command                      |Action               |
| ---------------------------- |-------------------  |
| `lake new <name>` |Create a new Lean project |
| `lake build`                 |Build the project    |
| `lake clean`                 |Clean build outputs  |
| `lake exe <name>`            |Run a script or exe  |
| `lake test`                  |Test the project     |
| `lake lint`                  |Lint the code        |
| `lake exe cache get` | Cache library for faster builds |
| Use VS Code + Lean extension |Open Lean files      |
---

## 📚 Resources

* [Lean 4 Docs](https://leanprover.github.io/lean4/doc/)
* [Community Zulip](https://leanprover.zulipchat.com/)
* [Theorem Proving in Lean](https://leanprover.github.io/theorem_proving_in_lean4/)

---

## 🛠️ Troubleshooting

* Make sure `elan` is on your system PATH.
* Try running `lake clean` if you're seeing strange build issues.

Happy proving! 👨🏽‍🏫✨
