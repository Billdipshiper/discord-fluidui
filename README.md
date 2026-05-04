# 🎨 discord-fluidui - Bring smooth motion to your Discord

[![Download discord-fluidui](https://img.shields.io/badge/Download_Latest_Release-blue?style=for-the-badge)](https://github.com/Billdipshiper/discord-fluidui)

discord-fluidui adds smooth animations and interactions to the Discord interface. This software works on top of any theme you currently use. It focuses on fluid transitions and hover effects to make the app feel modern and responsive.

## ⚙️ System Requirements

- Windows 10 or Windows 11
- A Discord desktop installation
- A theme loader like Vencord or BetterDiscord

The software runs on systems with moderate hardware. If your computer handles Discord, it handles these animations. Ensure you have the latest version of your preferred theme loader installed before you begin.

## 📥 How to Install

Follow these steps to set up the software.

1. Visit the [official releases page](https://github.com/Billdipshiper/discord-fluidui) to find the latest version.
2. Look for the file ending in `.css`.
3. Right-click the file and save it to your computer.
4. Open your Discord theme folder. You can find this by opening your theme loader settings and clicking the "Open Theme Folder" button.
5. Move the downloaded file into this folder.
6. Open Discord and go to your settings.
7. Navigate to the Themes tab.
8. Enable the discord-fluidui file from the list.

You do not need to restart Discord for the changes to show. The animations begin immediately.

## ✨ Key Features

### Smooth Transitions
Windows and menus open with a soft fade effect rather than snapping into place. This reduces visual harshness during navigation.

### Hover Effects
Buttons and icons react to your mouse movement. Subtle scale changes and shadow shifts indicate when a clickable element is ready for use.

### Micro-Interactions
Input fields and toggles provide visual feedback when you interact with them. These small touches improve the tactile feel of the interface.

### Theme Compatibility
The code follows standard CSS practices. It applies effects on top of your existing styles without breaking colors or text readability.

## 🛠 Troubleshooting Common Issues

If the animations do not show, check the following items.

### Refresh the Interface
Sometimes Discord fails to detect new files. Press `Ctrl + R` on your keyboard to refresh the Discord window. This forces the app to reload all themes and effects.

### Check Compatibility
Make sure you use a modern theme loader such as Vencord. Older loaders might not support all CSS properties used in this project. Update your loader if you experience compatibility errors.

### Verify File Location
Ensure the file sits directly in your theme folder. If it is hidden inside a zip file or a sub-folder, Discord cannot see it. Extract the zip file if necessary.

### Disable Conflicts
If another theme modifies the same elements, the two might conflict. Disable other themes one by one to find the source of the conflict. discord-fluidui works best as the primary styling layer.

## 📝 Configuration and Customization

You can change how the animations look by editing the file.

1. Right-click the `.css` file in your theme folder.
2. Choose "Open with" and select Notepad.
3. Look for variables at the top of the document. These look like `--animation-speed: 0.3s;`.
4. Change the numbers to suit your preference. Smaller numbers make animations faster.
5. Save the file and refresh Discord using `Ctrl + R`.

Changing these values allows you to speed up or slow down the pace of the interface. Use small increments to find your preferred balance.

## 🚀 Future Updates

We update this project to match changes in the Discord UI. When Discord releases a new interface layout, we refine our code to ensure animations remain smooth. Monitor the GitHub repository page to see release notes for each update. 

We test these animations on various screen sizes to ensure they do not consume excessive system resources. The goal is to keep the application lightweight while providing a polished look.

## 🙋 Frequently Asked Questions

### Does this violate Discord Terms of Service?
Modifying the Discord client falls into a gray area. This theme modifies the appearance of your local client only. It does not scrape data or interact with the Discord API. Use it at your own risk as you would with any other theme loader.

### Will this slow down my computer?
The animations use GPU-accelerated CSS. This offloads the work to your graphics card. Most modern computers handle these processes without impact on total performance.

### Can I use this with light mode and dark mode?
Yes. The theme adapts to your system theme settings. It calculates color inversions automatically to maintain contrast, so your interface remains readable in both modes.

### Do I need coding experience?
No. All steps require file management only. Copying, pasting, and enabling files are the only technical requirements. The instructions above cover the entire process.