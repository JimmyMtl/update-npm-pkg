npm-update-package
---

An interactive CLI tool to update outdated packages in your project. The tool supports multiple package managers: npm,
yarn, and pnpm.

---

# Features

- Detect outdated packages.
- Choose between npm, yarn, or pnpm as your package manager.
- Interactively select specific packages to update or update all at once.
- Provides clear feedback on the update process.

---

# Installation

1. Clone the repository:

```bash
git clone git@github.com:JimmyMtl/npm-update-package.git
```

2. Install the dependencies:

```bash
npm install
```

3. Link the package:

```bash
npm link
```

You can now use the `update-npm` command in your terminal.

---

# Usage

Run the CLI tool in your project directory:

```bash
update-npm
```

## Step

1. Select your preferred package manager (npm, yarn, or pnpm).
2. View a list of outdated packages.
3. Choose:
    - Update all packages.
    - Select specific packages to update.

---

# Example

1. Start CLI

```bash
update-npm
```

2. Select package manager

```bash
? Which package manager do you want to use? (Use arrow keys)
> npm
  yarn
  pnpm
```

3. View outdated packages

```bash
Outdated Packages:
┌──────────────┬─────────┬─────────┬─────────┐
│ Name         │ Current │ Wanted  │ Latest  │
├──────────────┼─────────┼─────────┼─────────┤
│ lodash       │ 4.17.21 │ 4.18.0  │ 4.18.0  │
│ @types/node  │ 16.11.7 │ 16.18.3 │ 17.0.0  │
└──────────────┴─────────┴─────────┴─────────┘
```

4. Select packages to update

```bash
? Select packages to update:
◯ lodash
◯ @types/node
```

5. Update all or specific packages:

```bash
✔ Do you want to update all packages instead? No
```

--- 

# Supported Commands

- Update All: Update all outdated packages.
- Update Specific: Select specific packages to update.

---

# Contributing

Contributions are welcome! Please feel free to submit a Pull Request.