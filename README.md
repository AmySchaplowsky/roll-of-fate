# roll-of-fate

Session notes and world wiki for our SOIF campaign

These files are meant to be viewed in the [Obsidian](https://obsidian.md) application with certain plugins installed and enabled. Obsidian is a knowledge management tool which allows you to view and edit local Markdown files. If you want to view them on multiple devices, a file syncing service should be used.

## Setup Obsidian on a PC

1. Clone this [Git Repo](https://github.com/AmySchaplowsky/roll-of-fate) or simply download the files.
2. Download [Obsidian](https://obsidian.md/download)
3. Launch Obsidian and open the roll-of-fate folder as a Vault
4. Open the Settings via the Gear icon at the bottom left
   1. Select the **Core plugins** section
      1. Enable **Daily Notes** and open the plugin options
         1. Set the **New file location** = `Session Notes`
         2. Set the **Template file location** = `_templates/New Session`
      2. Enable **Templates** and open the plugin options
         1. Set the **Template folder location** = `_templates`
   1. Select the Community Plugins section
      1. Set **Safe Mode** = `OFF`
      2. Click the **Browse** button under the Community plugins item
         1. Search for and install the **Dataview** plugin, then click the Enable button
         2. Search for and install the **Excalidraw** plugin, then click the Enable button
         3. Search for and intall the **Obsidian Git** plugin, then click the Enable button
   1. Go back to the main Settings menu and scroll down in the left pane to the **Plugin Options** section
      1. Select **Dataview** to open the plugin options
         1. Set **Enable JavaScript Queries** = `ON`
      2. Select **Excalidraw** to open the plugin options
	      1. Change the Excalidraw folder to `Images`  
      3. Select **Obsidian Git** to open the plugin options
	      1. Set **Auto pull interval (minutes)** to `15`
         1. Set **Pull update on startup** = `ON`
5. Go to [[Campaign Overview]] and confirm the Dataview queries are displaying data from the campaign notes
6. Click the Daily Note icon at the top left (see below) and confirm a new page is created in the Session Notes folder with today's date as the title and populated with the New Session template content
   ![[Daily Note Icon.png]]