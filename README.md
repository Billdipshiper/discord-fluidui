# Discord FluidUI

> A complete motion and interaction polish for Discord. Works on any theme.

![Vencord](https://img.shields.io/badge/Vencord-compatible-5865F2?style=flat-square)
![BetterDiscord](https://img.shields.io/badge/BetterDiscord-compatible-3E82E5?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

## About

Discord FluidUI is a pure feel pack. It does not touch your colors, backgrounds, or fonts. What it adds is motion, interaction feedback, and a handful of subtle white-wash highlights that blend into whatever palette you already have.

Drop it on top of default dark, ClearVision, Midnight, or any custom theme and everything gains smooth, GPU-accelerated life without fighting the theme underneath. Every animation is restricted to `transform` and `opacity`, and every highlight is rendered in neutral `rgba(255,255,255,X)`, so it layers cleanly on anything.

## Features

### Entrance animations

The panels, menus, and modals that appear during normal use all animate in instead of popping. Context menus slide in from the left. User popouts and profile modals scale up with a soft overshoot. Settings, image viewer, and dialog modals scale in, with their backdrops fading behind them.

The chat surface gets the same treatment. Emoji, GIF, sticker, and reaction pickers rise from the chat bar. Autocomplete and slash command popups slide up, search results drop down from the top, and inbox and thread panels slide in from the right. Dropdown menus slide down, tooltips pop in, and typing indicators fade in so nothing appears abruptly.

### Hover micro-interactions

Interactive elements respond to the cursor with small, consistent transforms. Server icons scale on hover with spring easing, and their tooltips stay correctly positioned. DM and friends list rows scale individually with a subtle background highlight. Channel list items expand slightly, channel category headers scale on hover, and voice channel user avatars scale when you hover over their row.

Buttons and controls feel physical. Filled and outlined buttons grow on hover and press in on click. Reaction buttons pop up slightly. Your user avatar, server folders, emoji picker cells, and toolbar icons all zoom on hover. The user panel in the bottom left glows when you hover it, and messages gain a subtle left accent rail and background wash as you pass over them.

### Highlights and polish

Focus states are more visible. The message input bar and search bars get a soft glow when focused. Unread channels are easier to spot thanks to a subtle text glow and background highlight, and the unread pill on server icons gets a soft halo.

The small touches matter too. Scrollbars are slim and neutral, scroll behavior is smooth across every scrollable surface, and the selected or connected channel gets a crisp left rail with a short bleed-in so you always know where you are.

### Accessibility

FluidUI honors the OS-level `prefers-reduced-motion` setting. When reduced motion is enabled, all animations and transitions collapse to a near-zero duration.

## Installation

### Vencord

1. Download `discord-fluidui.theme.css`.
2. Open Discord, then go to **Settings** and **Themes**.
3. Click **Open Themes Folder**. On Windows this is `%AppData%\Roaming\Vencord\themes`.
4. Drop the file into the folder.
5. Toggle **Discord FluidUI** on in the theme list.

### BetterDiscord

1. Download `discord-fluidui.theme.css`.
2. Open Discord, then go to **Settings** and **Themes**.
3. Click **Open Themes Folder**.
4. Drop the file into the folder.
5. Toggle **Discord FluidUI** on in the theme list.

No restart is needed in either client.

## Stacking with other themes

Because FluidUI never touches color, background, or font, it sits cleanly on top of any theme, including default Discord dark, ClearVision, Midnight, Solana, and any custom theme you already use.

If another theme introduces its own animations on the same elements, the later-loaded stylesheet wins. Move Discord FluidUI below it in the theme list for FluidUI to take precedence.

## Credits

Author: **nightwielder23**. Issues and suggestions are welcome on the [GitHub repository](https://github.com/nightwielder23/discord-fluidui).

## License

[MIT](./LICENSE) (c) 2026 nightwielder23
