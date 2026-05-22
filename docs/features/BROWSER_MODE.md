# Browser Files Mode

**Browser Files Mode** is a zero-installation feature that allows you to load and read folders or individual Markdown files stored directly on your computer.

---

## 📁 Reading Local Folders

To open a local folder:
1. On the landing page or sidebar switcher, click the **Open Folder** button.
2. Select your folder from your computer's native file explorer.
3. Click **Select / Authorize** on the browser security prompt.
4. Your folder structure is parsed instantly, and you can browse through files using the collapsible file tree in the sidebar.

---

## 🔒 Security & Sandboxing

* **Local Safety:** The browser processes your files inside a secure client-side sandbox. The code is running on your machine, meaning none of your directories or files are uploaded to any external server.
* **Persistent Access:** The list of folders you open is stored in your browser's private local storage. When you return to mDocks, you can jump back to previous directories quickly. You only need to click the re-authorization prompt to regain access to your files.

---

## 🔄 Live Editing & Auto-Refresh

If you use a local markdown editor (such as Obsidian, VS Code, Logseq, or Notepad++):
* You can keep mDocks open side-by-side with your editor.
* Every time you save changes to your Markdown file in your text editor, mDocks automatically detects the file update and updates the viewer in real-time.
* You do not need to click refresh or reload the page to see your updated text.
