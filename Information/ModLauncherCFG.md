

# 🛠 Mod Launcher Configuration Guide (`launcher.cfg`)

The `launcher.cfg` file (often saved as an `.xml` file) is the "map" that tells the 7D2D Mod Launcher who you are, what your mod does, and exactly where to download the files.

## 📂 File Placement

For the Mod Launcher to work correctly, this file must be placed at the **top level** of your GitHub/GitLab repository.

---

## 🏗 Essential XML Structure

### 1. Server Group (The Category)

The `<ServerGroup>` tag creates a folder in the launcher's sidebar. This is where you group different versions of your mods.

* **Name**: The heading your friends will see.
* **Description**: A short blurb about your mod team or project.

### 2. Server (The Mod Instance)

The `<Server>` tag represents a specific version of your mod (e.g., "Stable" vs "Experimental").

* **Name**: The specific name of this mod version.
* **Logo**: A direct link to a **2064x452** image. If left blank, the launcher uses a default image.

### 3. Core Technical Settings

These tags control how the game is installed on the user's PC:

* **`<Deploy>Full</Deploy>`**: **Highly Recommended.** This tells the launcher to make a separate copy of the game files for this mod. This prevents your mod from breaking the user's "vanilla" game.
* **`<Version>`**: Specify the game version (e.g., `alpha21.1` or `Latest`).
* **`<Author>`**: Your name or team name.

---

## 📥 Download Methods

The `<Downloads>` section is the most critical part of the file. You should only provide **one** active download link per server.

### Option A: Direct Git Sync (Best for Updates)

This allows the launcher to check for updates every time it opens. Use your main repository URL.

```xml
<Download>https://github.com/YourUsername/YourRepoName</Download>

```

### Option B: GitHub Releases (Best for Large Packs)

If you want users to download a specific Zip file you uploaded to the "Releases" section:

```xml
<Download>https://github.com/YourUsername/YourRepoName/releases</Download>

```

*Note: The launcher will automatically grab the first zip file attached to your latest release.*

---

## 🔗 Social & Support Tags

You can include various links to help users find your community:

* **`<Discord>`**: Direct invite link to your server.
* **`<WebSite>`**: Link to your personal site or mod page.
* **`<Donate>`**: Link to your Patreon, Ko-fi, or PayPal.
* **`<ReleaseNotes>`**: A link to a text file or webpage detailing what changed.

---

## 📝 Configuration Template

Paste this into your file and update the placeholders:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<Servers>
	<ServerGroup Name="My Mod Team" Logo="" Description="Custom mods for our server.">
		<Server Name="Mod Pack - Stable" Logo="">
			<Description>Enter a detailed description here.</Description>
			<Author>YourName</Author>
			<Deploy>Full</Deploy>
			<Version>Latest</Version>
			<Downloads>
				<Download>https://github.com/YourUsername/YourRepoName</Download>
			</Downloads>
		</Server>
	</ServerGroup>
</Servers>

```

