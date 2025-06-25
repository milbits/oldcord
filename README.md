# OldCord

A theme for Discord that brings the 2020 UI back without removing features

 By default, it completely removes profile effects (like banners) and clan tags. See `addons` below to get them back!

![Preview](https://raw.githubusercontent.com/solaetv/soldcord/master/.github/preview.webp)

> [!IMPORTANT]  
> - Enable "Sync Profile Themes" in `Settings > Accessibility` to fix broken profile colors
> - UI Density should be on default, i wont support the other 2 options (they still kinda work though)
> - To have the old gray colors, use the "Ash" theme in appearance settings

<details> <summary>Light mode (shit)</summary>

<img src=https://raw.githubusercontent.com/solaetv/soldcord/master/.github/previewLight.webp>

</details>



<details><summary><h1>Addons</h1></summary>

## By OldCord

These are usually included in oldcord.theme.css, so all you need to do is remove `/*` in the file for each addon you want to use

| Name                   | Preview                                                                                | CSS                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Old Plead Emoji        | ![Image](https://raw.githubusercontent.com/solaetv/soldcord/master/.github/emojis.webp)     | `@import url("https://solaetv.github.io/soldcord/src/components/oldEmojis.css");`   |
| Context Menu hover bg. | <img src=https://raw.githubusercontent.com/solaetv/soldcord/master/.github/oldcontext.webp> | `@import url("https://solaetv.github.io/soldcord/src/components/oldContext.css");`  |
| Show Profile Cosmetics (Light theme not supported for now) | ![Image](https://raw.githubusercontent.com/solaetv/soldcord/master/.github/showeffects.webp)                                                           | `@import url("https://solaetv.github.io/soldcord/src/components/showEffects.css");` |
| HeaderPresence | ![Image](https://github.com/user-attachments/assets/1a809f81-0d76-4146-ad25-941b4332bcbd)                                                           | https://betterdiscord.app/plugin/HeaderPresence |
| [Tanza3D & KingGamingYT's NoMosaic plugin (BetterDiscord)](https://github.com/KingGamingYT/discord-no-mosaic)                         | Restores the old image layout                               |

If you use custom/quickcss, paste the CSS at the very top!

## By SoldCord

These are usually included in oldcord.theme.css, so all you need to do is remove `/*` in the file for each addon you want to use

| Name                   | Preview                                                                                | CSS                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Bad Buttons        | ![Image](https://raw.githubusercontent.com/solaetv/soldcord/master/.github/bad-buttons.webp)     | `@import url("https://solaetv.github.io/soldcord/src/components/badButtons.css");`   |
| Remove Reply Highlight        | ![Image](https://raw.githubusercontent.com/solaetv/soldcord/master/.github/replyHighlight.webp)     | `@import url("https://solaetv.github.io/soldcord/src/components/removeReplyHighlight.css");`   |

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

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/solaetv/soldcord/main/soldcord.theme.css) (right-click > "Save As")
2. Save the file to the BetterDiscord theme folder:

- Windows: `%appdata%/BetterDiscord/themes`
- Linux: `~/.config/BetterDiscord/themes`

## 😺[Vencord](https://github.com/Vendicated/Vencord)

#### Local method

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/solaetv/soldcord/main/soldcord.theme.css) (right-click > "Save As")
2. Move the file to the Vencord theme folder:

- `Settings > Themes > Open theme folder`

#### Online method

Paste the following in `Settings > Themes`:

- `https://solaetv.github.io/soldcord/src/main.css`

## 🎛️ Other

1. Paste the following at **the top** of the CSS file/window:

```css
@import url("https://solaetv.github.io/soldcord/src/main.css");
```


