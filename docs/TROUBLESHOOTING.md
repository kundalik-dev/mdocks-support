# Troubleshooting Guide

This guide helps you resolve the most common issues you might encounter while using **mDocks**.

---

## 💻 Local Server Shows "Offline" or Red Indicator

### Symptom:
The Server Panel in the sidebar reports that the local helper is unreachable, and you cannot clone or view GitHub repositories.

### Solutions:
1. **Ensure the Helper is Running:**
   Check if your terminal or command prompt window running the helper is still open. If you closed it, the server stopped. Open your terminal and start it again:
   ```bash
   npx @iprep/mdocs start
   ```
2. **Check the Connection Port:**
   By default, the mDocks helper connects via port `5540`. Ensure no other application on your machine is utilizing this port.
3. **Allow Local Connections:**
   Ensure your local firewall or antivirus software is not blocking local communication on port `5540`.

---

## 📁 File Tree shows "Permission Prompt Required"

### Symptom:
A folder you previously opened is listed in the Source Switcher, but it is empty, or you see a banner stating that permission is required.

### Explanation:
By design, web browsers automatically revoke folder permissions whenever you reload the page, close the tab, or restart your browser. This is a critical security feature that prevents web pages from accessing your computer's files without your active consent.

### Solutions:
1. Click the **Permission Required** or **Re-auth** button on the file tree sidebar.
2. A native browser prompt will appear at the top-left of your screen (near the URL address bar).
3. Click **View Files** or **Grant Access** to authorize and reload your folder contents instantly.
4. If the folder still does not load, simply click the **Clear All** option in the Source Switcher and open the folder fresh using **Open Folder**.

---

## 🔄 Changes to My Files are Not Showing Up

### Symptom:
You edited a Markdown file in your favorite text editor (e.g., Obsidian, VS Code, or Notepad++), but the mDocks reader still shows the old version.

### Solutions:
1. **Wait a few seconds:** mDocks automatically checks for local file updates in the background every **2 seconds**.
2. **Bring the Window to Focus:** If the mDocks tab is running in the background, it temporarily pauses automatic synchronization to save your computer's battery. Click back onto the mDocks tab to let it refresh.
3. **Save your changes:** Ensure that you have actually saved the modifications in your text editor.
