# DirectoryOpus-DFIRConfig
A config file for [Directory Opus](https://www.gpsoft.com.au/) that's curated specfically for DFIR examiners with shortcuts to common Windows artifacts and settings enabled that help make your life easier with various file management tasks.

## Change Log

| Date       | Comments        |
|------------|-----------------|
| 2021/11/23 | Initial release |
| 2021/11/27 | V2 - added seconds/milliseconds in Time column |

## Why Should I Care? Isn't Windows File Explorer Good Enough?

Sure it's good enough, but you don't know what you don't know if you've never used an alternative to File Explorer before, be it Directory Opus or another application. Things Windows File Explorer cannot do that saves an immeasurable amount of time:

1. Flat View 
2. Copy files from multiple folders into the same destination folder with choice to recreate (or ignore) each file's directory structure
3. Queue and stack multiple copy tasks with various unattended options (Have you ever copy something overnight only to find it stalled an hour into it when you wake up the next day?)
4. Create multiple folders all at once
5. Robust searching including but not limited to filenames and file contents
6. Calculate folder sizes, not just file sizes
7. Hash files
8. ...and many, many more!

## Directory Opus Themes

I've provided a Light and Dark theme. See below!

![DOpusPreviewLight.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/DOpusPreviewLight.jpg)

![DOpusPreviewDark.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/DOpusPreviewDark.jpg)

Click [here](https://resource.dopus.com/c/themes/24?order=views) for a link to a pre-sorted list of the most viewed themes created for Directory Opus. The Light theme used is default and the Dark theme is [Simple Windows 10 Dark Theme](https://resource.dopus.com/t/simple-windows-10-dark-theme/30055). 

## Details of this Directory Opus Config File

Here's a rundown of what modifications I made to the default configuration of Directory Opus. 

* Enabled automatic folder size calculation

![CalculateFolderSizes](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/CalculateFolderSizes.jpg)

* Enabled filter bar by default

![DisplayFilterBar.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/DisplayFilterBar.jpg)

* Enabled Dual Folder Tree by default, when in Dual Horizontal mode

![DualFolderTree.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/DualFolderTree.jpg)

* Enabled Highlight Path to Selected Folder by default

![HighlightPathtoSelectedFolder.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/HighlightPathtoSelectedFolder.jpg)

* Adjusted various default settings, including new tab opens to This PC by default

![ListerTabOptions.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/ListerTabOptions.jpg)

* Enabled automatic folder size enumeration for Network Drives by default

![NetworkDrivesAutoLoadonTabActivation.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/NetworkDrivesAutoLoadonTabActivation.jpg)

* Enabled relative graphs for File Size and Last Modified timestamp

![RelativeGraphsSizeModifiedDate.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/RelativeGraphsSizeModifiedDate.jpg)

* Enabled PowerShell Here (Admin) and Command Prompt Here (Admin) in the right-click context menu

![CommandPromptAdminHere.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/CommandPromptAdminHere.jpg)

Function: `CLI DOSPROMPT=powershell,admin,nocolor`

![PowerShellAdminHere.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/PowerShellAdminHere.jpg)

Function: `CLI DOSPROMPT=admin,nocolor`

**Added in V2**

* Add Seconds and Milliseconds to any Time column

![SecondsMillisecondsTimeColumn](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/SecondsMillisecondsTimeColumn.jpg)

# Feedback

What do you like? What don't you like? Let me know and I'll consider adding or changing it for the greater good!

# Resources

Want to learn more about Directory Opus and how insanely customizable it is? Look no further!

* [Directory Opus on YouTube](https://www.youtube.com/c/DirectoryOpus)
* [Directory Opus (File Manager) - Customization / Layout / Look 'n Feel](https://www.youtube.com/watch?v=x5fH2H2APOY)
* [Directory Opus: Personalize Folder Colors, Columns, Labels and more!](https://www.youtube.com/watch?v=-L8ybqqUmFo)
* [Directory Opus: Using System-Wide Hotkeys to Control Audio Output (and almost anything else)](https://www.youtube.com/watch?v=Zq7xxOla1Zk)
* [Directory Opus meets Quick Access Popup - Discussing 2 great productivity tools](https://www.youtube.com/watch?v=4HGl09aVFgA)
* [How to use your Folder's Icon in the Taskbar with Directory Opus](https://www.youtube.com/watch?v=aBiqOzHa2r8)
* [How to create buttons in Directory Opus & learn more amazing tips!](https://www.youtube.com/watch?v=vlh5XqIykLw)

# TO ADD (NEXT RELEASE)

Nothing at this time!
