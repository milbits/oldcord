# OldCord

A theme for Discord that brings the 2020 UI back without removing features

 By default, it completely removes profile effects (like banners) and clan tags. See `addons` below to get them back!

![Preview](https://raw.githubusercontent.com/milbits/oldcord/master/.github/preview.webp)

> [!IMPORTANT]  
> - Enable "Sync Profile Themes" in `Settings > Accessibility` to fix broken profile colors
> - UI Density should be on default, i wont support the other 2 options (they still kinda work though)
> - To have the old gray colors, use the "Ash" theme in appearance settings
>   - If you use vencord's "Client Theme" plugin, use darker
>  
> - If you use BetterFolders, expect half of your screen to become black. I always try to fix this but no promises

<details> <summary><h3>Light mode (usable!)</h3></summary>

Light mode does NOT have 2020 colors and it's tailored to ME but i think nobody cares at all

<img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/previewLight.webp>
preview outdated

there's a `--oldcord-tint` variable to adjust the tint, value/number has to be in HSL hue

</details>



<details><summary><h1>Addons</h1></summary>

## By OldCord

These are usually included in oldcord.theme.css, so all you need to do is remove `/*` in the file for each addon you want to use

| Name                   | Preview                                                                                | CSS                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Show Profile Effects (the one you prob want) | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/showeffects.webp)                                                         | `@import url("https://milbits.github.io/oldcord/src/components/showEffects.css");` |
| Hide Clan Tags | im too lazy for an image                                                     | `@import url("https://milbits.github.io/oldcord/src/components/hideTags.css");` |
| Old Plead Emoji        | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/emojis.webp)     | `@import url("https://milbits.github.io/oldcord/src/components/oldEmojis.css");`   |
| Context Menu hover bg. | <img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/oldcontext.webp> | `@import url("https://milbits.github.io/oldcord/src/components/oldContext.css");`  |
| HeaderPresence | ![Image](https://github.com/user-attachments/assets/1a809f81-0d76-4146-ad25-941b4332bcbd)                                                           | https://betterdiscord.app/plugin/HeaderPresence |
| [Tanza3D & KingGamingYT's NoMosaic plugin (BetterDiscord)](https://github.com/KingGamingYT/discord-no-mosaic)                         | Restores the old image layout                               |

If you use custom/quickcss, paste the CSS at the very top!

## 3rd party

| Name                                                                                                                                  | Description                                                 |
| ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [Vencord's NoMosaic plugin](https://vencord.dev/plugins/NoMosaic)                                                                     | Restores the old image layout                               |
| [NoSuperReactions](https://github.com/xenrelle/Xens-BD-Dump/tree/main/plugins/NoSuperReactions)                                       | Removes super reactions                                     |
| [OldFileUpload](https://github.com/xenrelle/Xens-BD-Dump/tree/main/plugins/OldFileUpload)                                             | Open the file picker with just one click                    |
| [hide-nitro-upselling](https://github.com/D3SOX/complementary-discord-theme/blob/master/hide-nitro-upselling.betterdiscord.theme.css) | Hides nitro ads, could cause lag                            |
| [Icon Revert](https://github.com/davart154/Icon-Revert-2023/blob/main/2023%20Icon%20Revert.theme.css)                                 | Reverts all icons to pre-2023. Can cause huge lag (see #37) |

---

</details>

# Installation

## 🚮[BetterDiscord](https://betterdiscord.app/)

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Save the file to the BetterDiscord theme folder:

- Windows: `%appdata%/BetterDiscord/themes`
- Linux: `~/.config/BetterDiscord/themes`

## 😺[Vencord](https://github.com/Vendicated/Vencord)

#### Local method

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Move the file to the Vencord theme folder:

- `Settings > Themes > Open theme folder`

#### Online method

Paste the following in `Settings > Themes`:

- `https://milbits.github.io/oldcord/src/main.css`

## 🎛️ Other

1. Paste the following at **the top** of the CSS file/window:

```css
@import url("https://milbits.github.io/oldcord/src/main.css");
```


