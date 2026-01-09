
# 🚀 Mod Upload & Sharing Guide

### 🛑 Step 1: Choose Your Platform & Method

Check your **Mods** folder first to decide where to go.

* **Is any single file > 100MB?**
* **YES:** Use [GitLab](https://gitlab.com). GitHub will block individual files over 100MB.
* **NO:** Use GitHub.


* **Is your total Zipped pack < 2GB?**
* **YES:** Use **Method B (GitHub Releases)**. It’s the easiest for your friends.
* **NO:** Use **Method A (GitHub Desktop)**. Your friends will also need GitHub Desktop to download it.



---

## 🛠 Step 2: Create Your Account & Repository

*Required for both methods.*

1. **Sign Up:** Go to [GitHub.com](https://github.com) and create an account.
2. **Create Repository:** Click the **+** icon (top right) → **New repository**.
3. **Setup:**
* **Name:** Give it a name (e.g., `My-Mod-Pack`).
* **Visibility:** Choose **Public** (anyone can see) or **Private** (only friends you invite).
* Click **Create repository**.



---

## 🔄 Method A: Using GitHub Desktop

*Best for: Managing updates and packs larger than 2GB.*

1. **Install:** Download and install [GitHub Desktop](https://desktop.github.com).
2. **Clone:** Sign in and select your new repository. Choose a folder on your computer to be your **"Cloud Sync Folder."**
3. **Locate Mods:** Find your actual **Mods** folder on your PC.
4. **Copy & Paste:** Copy the **entire Mods folder** and paste it into the **Cloud Sync Folder**.
* *Your Cloud Sync Folder should now contain a folder named "Mods".*


5. **Upload:**
* Open **GitHub Desktop**.
* Type "Update mods" in the Summary box (bottom left).
* Click **Commit to main**, then click **Push origin** at the top.



---

## 🎁 Method B: Using GitHub Releases

*Best for: Simple one-click downloads (No GitHub Desktop required).*

1. **Zip Your Mods:** Locate your **Mods** folder on your PC. Right-click the **Mods folder itself** → **Compress to ZIP file**. Name the resulting zip `ModPack.zip`.
* *When opened, the zip should show the "Mods" folder at the top level.*


2. **Open Browser:** Go to your repository page on GitHub.com.
3. **Find Releases:** On the right-hand sidebar, click **"Create a new release"**.
4. **Create Tag:** Click **"Choose a tag"**, type `v1.0`, and click **"Create new tag"**.
5. **Attach Zip:** Scroll down to the **"Assets"** box. Drag and drop your `ModPack.zip` file into this box.
6. **Publish:** Click **Publish release**. You can now send the link to this page to your friends!
