# Local Server Mode & GitHub Browser

The **Local Server Mode** allows **mDocks** to connect to a local command-line helper, enabling you to clone public or private GitHub repositories and read their Markdown files offline.

---

## 🚀 Cloning a Repository

To read a GitHub repository:
1. Ensure the local helper is running in your terminal: `npx @iprep/mdocs start`.
2. Open mDocks and expand the **Server Panel** in the sidebar.
3. Paste the URL of any GitHub repository (e.g., `https://github.com/facebook/react`).
4. Click **Clone**.
5. The helper clones the repository and loads its folder structure into the mDocks file tree.

---

## 🔄 Syncing Updates

If the GitHub repository receives new commits:
* Click the **Sync** button in the header of your active repository card.
* The local helper will automatically fetch and pull down the latest commits, updating your offline workspace in real-time.

---

## 🗑️ Managing Cloned Repositories

* All cloned repositories are stored locally on your disk.
* To free up space or tidy your sidebar, click the **Settings / Actions** button next to the repository in your Server list and click **Delete**.
* This removes the repository cache from your local helper immediately.
