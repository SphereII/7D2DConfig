## 1. Create a GitHub Account

1. Go to [GitHub.com](https://github.com/) and click **Sign up**.
2. Once logged in, click the **+** icon (top right) → **New repository**.
3. Name it (e.g., `My-Mod-Pack`), set it to **Public** or **Private**, and click **Create repository**.

## 2. Install GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/).
2. Sign in and click **Clone a Repository from the Internet**.
3. Select your new repository and choose a **Local Path** on your computer. This folder is now your "Cloud Sync" folder.

## 3. Syncing Your Mods

To upload your mods, you must bring them into the "Cloud Sync" folder you just created.

1. **Locate Your Mods**: Open the folder where your mods currently live. (This might be in `%AppData%/7DaysToDie/Mods`, your Steam folder, or a custom Mod Launcher folder).
2. **Copy**: Select all the folders inside your current **Mods** folder and copy them.
3. **Paste**: Go to your new GitHub "Cloud Sync" folder and paste them there.
4. **Upload**:
* Open **GitHub Desktop**. You will see the files listed on the left.
* In the **Summary** box (bottom left), type "Update mods".
* Click **Commit to main**, then click **Push origin** at the top.



---

## ⚠️ Important: File & Size Limits

Before you upload, check your file sizes to avoid errors.

### 🛑 The 100MB Individual File Limit

GitHub will reject your upload if **any single file** inside your folders is larger than **100MB** (common with large custom unity bundles or 8k textures).

* **If you have 100MB+ files**: You must use [GitLab](https://gitlab.com/) instead. It is very similar to GitHub but allows larger individual files on their free tier.

### 📦 The 2GB Zip Rule (Releases)

If you want to provide a single "Download All" button for your friends:

* **GitHub Releases**: If your total zipped mod pack is **under 2GB**, you can attach it as a "Release."
* **How**: On your GitHub web page, click **Create a new release** (right side) and drag your `.zip` file into the box.

### ⏳ Bandwidth Warning (LFS)

If you use "Git LFS" (Large File Storage) to bypass the 100MB limit on GitHub, be careful: GitHub Free only gives you **1GB of download bandwidth per month**. If five friends download your 200MB mod, your bandwidth is gone for the month. **GitLab or GitHub Releases** are usually better for sharing with others.

