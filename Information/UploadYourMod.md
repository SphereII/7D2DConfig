

# 🚀 Mod Upload & Sharing Guide

### 🛑 Step 1: Choose Your Platform & Method

Check your **Mods** folder first to decide where to go.

* **Is any single file > 100MB?**
* **YES:** Use [GitLab](https://gitlab.com). GitHub will block individual files over 100MB.
* **NO:** Use GitHub.


* **Is your total Zipped pack < 2GB?**
* **YES:** Use **Method B (GitHub Releases)**. This is the cleanest way for friends to download.
* **NO:** Use **Method A (GitHub Desktop)**. Note that for very large packs, friends will use the "Download ZIP" button on your main page.



---

## 🛠 Step 2: Create Your Account & Repository

*Required for both methods.*

1. **Sign Up:** Go to [GitHub.com](https://github.com) and create an account.
2. **Create Repository:** Click the **+** icon (top right) → **New repository**.
3. **Setup:**
* **Name:** Give it a name (e.g., `My-Mod-Pack`).
* **Visibility:** Choose **Public** so your friends can access it without an account.
* Click **Create repository**.



---

## 🔄 Method A: Uploading via GitHub Desktop

*Use this for large packs or if you plan to update the mods frequently.*

1. **Install:** Download [GitHub Desktop](https://desktop.github.com).
2. **Clone:** Select your new repository in the app and choose a folder on your PC to be your **"Cloud Sync Folder."**
3. **Copy & Paste:** Copy your **entire Mods folder** and paste it into that **Cloud Sync Folder**.
4. **Upload:** In GitHub Desktop, type "Update" in the summary box and click **Commit to main**, then **Push origin**.
5. **How Friends Download:** Send them the link to your GitHub page. Tell them to click the green **"<> Code"** button and select **"Download ZIP"**. They do **not** need an account or any software.

---

## 🎁 Method B: Uploading via GitHub Releases

*Use this for the easiest, "one-click" experience for your friends.*

1. **Zip Your Mods:** Locate your **Mods** folder. Right-click the **Mods folder itself** → **Compress to ZIP file**. Name it `ModPack.zip`.
2. **Open Browser:** Go to your repository page on GitHub.com.
3. **Find Releases:** On the right-hand sidebar, click **"Create a new release"**.
4. **Create Tag:** Click **"Choose a tag"**, type `v1.0`, and click **"Create new tag"**.
5. **Attach Zip:** Drag and drop your `ModPack.zip` into the **"Assets"** box.
6. **Publish:** Click **Publish release**.
7. **How Friends Download:** Send them the link to this Release page. They just click the `ModPack.zip` link under **Assets** to download it instantly.


