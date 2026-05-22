# Initial Setup Guide

Setting up **mDocks** is simple, fast, and highly flexible depending on how you wish to read your Markdown documents.

---

## 🌐 Option 1: Direct Web App Usage (No Installation)

If you only want to read local files and folders on your computer, you do not need to install anything!

1. Open your web browser (Chrome, Edge, or any Chromium-based browser).
2. Go to the official web app: **[https://mdocks.dev](https://mdocks.dev)**.
3. Click **Open Folder** or **Open Files** to load your local directories or notes instantly.

---

## 💻 Option 2: Local Server Setup (For GitHub Repositories)

To clone and read GitHub repositories offline, you can run the optional lightweight helper server on your machine.

### Prerequisites:
* Make sure you have **Node.js** installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

### Step 1: Start the Local Helper
Open your computer's terminal or command prompt (PowerShell, Command Prompt, or Terminal) and run the following command:

```bash
npx @iprep/mdocs start
```

*This command automatically downloads and launches the lightweight helper on your local machine.*

### Step 2: Open the mDocks Viewer
1. Open your browser and navigate to the web app: **[https://mdocks.dev](https://mdocks.dev)**.
2. In the left sidebar, expand the **Server Panel**.
3. You will see a green connection indicator showing that mDocks has successfully connected to your local helper at `127.0.0.1:5540`.

### Step 3: Clone a Repository
1. In the **Server Panel**, paste the link to any public or private GitHub repository (e.g., `https://github.com/username/project`).
2. Click **Clone**.
3. The repository will be downloaded onto your machine, and a fully browsable directory tree will load in the sidebar. You can now read it offline!
