# PM-Dev-Env

PM-Dev-Env combines multiple PenguinMod repositories into one workspace so you can easily develop PenguinMod and PenguinMod extensions. It supports live updates to the localhost website (repository `penguinmod.github.io`) when the local repository `PenguinMod-Vm` changes.

## Quick Setup

### 1. Install required tools first

```bash
choco install git
choco install nvm
choco install pnpm
```

Note: Chocolatey is optional. You can install Git, nvm, and pnpm manually if you prefer.

### 2. Clone and set up the workspace

Clone the repository and enter the project folder:

```bash
git clone https://github.com/GermanCodeEngineer/PM-Dev-Env
cd PM-Dev-Env
```

Install both Node versions used in this workflow:

```bash
nvm install node
nvm install 16.20.2
```

Use the latest Node version to install dependencies:

```bash
nvm use node
pnpm install
```

Switch to Node 16 and run the app:

```bash
nvm use 16
npm start
```
