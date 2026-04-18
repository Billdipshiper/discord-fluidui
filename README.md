# Discord FluidUI

> A complete motion and interaction polish for Discord. Works on any theme.

![Vencord](https://img.shields.io/badge/Vencord-compatible-5865F2?style=flat-square)
![BetterDiscord](https://img.shields.io/badge/BetterDiscord-compatible-3E82E5?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## About

Discord FluidUI is a **pure feel pack**. Zero colors, zero backgrounds, zero fonts are changed — only motion, interaction feedback, and a handful of subtle white-wash highlights. Drop it on top of default dark, ClearVision, Midnight, or any custom theme and everything gains smooth, GPU-accelerated life without fighting the theme underneath.

Every animation is restricted to `transform` and `opacity`, and every highlight is rendered in neutral `rgba(255,255,255,X)` so it blends into whatever color palette you already have.

## Features

### Entrance animations
- Context menus slide in from the left
- User popouts scale in with a soft overshoot
- User profile modals (legacy, v1, and v2) scale in
- Settings, image viewer, and dialog modals scale in
- Modal backdrops fade in
- Tooltips pop in instantly
- Emoji, GIF, sticker, and reaction pickers rise from the chat bar
- Autocomplete and slash command popups slide up
- Search results drop down from the top
- Inbox and thread panels slide in from the right
- Dropdown menus slide down
- Typing indicators fade in
- Message action bars scale in
- Settings sidebar items slide in from the left
- Member list items fade in

### Hover micro-interactions
- Server icons scale on hover and press on click
- DM list items lift and gain a faint wash
- Channel list items nudge right (thread spines stay aligned)
- Member list items, friend rows, and role pills respond to hover
- Filled and outlined buttons grow on hover, press in on click
- Reaction buttons pop up slightly
- Home / DM button scales up
- User avatar, server folders, image thumbnails, emoji picker cells, and toolbar icons all zoom on hover
- Messages gain a subtle left accent rail on hover without shifting position

### Highlights and polish
- Focus glow on text area and inputs
- Near-invisible message hover wash
- Slim neutral scrollbars
- Smooth scroll across every scrollable surface
- Soft halo around the unread pill on server icons
- Crisp left rail and short bleed-in on the selected or connected channel

### Accessibility
- Honors the OS-level `prefers-reduced-motion` setting — all animations and transitions collapse to a near-zero duration when the user has reduced motion enabled

## Installation

### Vencord

1. Download `discord-fluidui.theme.css`
2. Open Discord → **Settings** → **Themes**
3. Click **Open Themes Folder** (on Windows this is `%AppData%\Roaming\Vencord\themes`)
4. Drop the file into the folder
5. Toggle **Discord FluidUI** on in the theme list

### BetterDiscord

1. Download `discord-fluidui.theme.css`
2. Open Discord → **Settings** → **Themes**
3. Click **Open Themes Folder**
4. Drop the file into the folder
5. Toggle **Discord FluidUI** on in the theme list

No restart needed in either client.

## Stacking with other themes

Because Discord FluidUI never touches color, background, or font, it sits cleanly on top of **any** theme, including:

- Default Discord dark
- ClearVision
- Midnight
- Solana
- Any custom theme you already use

If a theme introduces its own animations on the same elements, the later-loaded stylesheet wins — move Discord FluidUI below it in the theme list for FluidUI to take precedence.

## Credits

Author: **nightwielder23**

Issues and suggestions are welcome on the [GitHub repository](https://github.com/nightwielder23/discord-fluidui).

## License

[MIT](./LICENSE) © 2026 nightwielder23
