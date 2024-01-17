# OldCord

A theme for Discord that brings back the 2020 UI (mostly) without removing features.

###### Completely removes profile effects, profile colors, avatar decos, and banners

![Preview](https://raw.githubusercontent.com/milbits/oldcord/master/.github/preview.png)

<details> <summary><strong>Light mode</strong></summary>
<img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/previewLight.png>

</details>

<details><summary><strong>Additional stuff</strong></summary>

| Name                                                                                                                                  | Description                              |
| ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| [Vencord's NoMosaic plugin](https://vencord.dev/plugins/NoMosaic)                                                                     | Restores the old image layout            |
| [Tanza3D's NoMosaic plugin (BetterDiscord)](https://github.com/KingGamingYT/discord-no-mosaic)                                        | Restores the old image layout            |
| [NoSuperReactions](https://github.com/xenrelle/Xens-BD-Dump/tree/main/plugins/NoSuperReactions)                                       | Removes super reactions                  |
| [OldFileUpload](https://github.com/xenrelle/Xens-BD-Dump/tree/main/plugins/OldFileUpload)                                             | Open the file picker with just one click |
| [hide-nitro-upselling](https://github.com/D3SOX/complementary-discord-theme/blob/master/hide-nitro-upselling.betterdiscord.theme.css) | Hides nitro ads                          |

#### Old Plead Emoji

In the custom CSS Tab on BD/Quick css file on Ven `(Settings > Vencord > Open quickcss file)`, copy-paste the following:

```css
@import url("https://milbits.github.io/oldcord/src/components/oldEmojis.css");
```

#### Old Context menu background

<img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/oldcontext.png>

```css
@import url("https://milbits.github.io/oldcord/src/components/oldContext.css");
```

#### Show Profile Cosmetics

Unhides things like profile banners

```css
@import url("https://milbits.github.io/oldcord/src/components/showEffects.css");
```

Make sure that they're at the top of the file!

</details>

#### Enable "Sync Profile Themes" in `Settings > Accessibility` to fix broken profiles

# Installation

## [BetterDiscord](https://betterdiscord.app/)

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Save the file to the BetterDiscord theme folder:

- Windows: `%appdata%/BetterDiscord/themes`
- Linux: `~/.config/BetterDiscord/themes`

## [Vencord](https://github.com/Vendicated/Vencord)

#### Local method

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Move the file to the Vencord theme folder:

- `Settings > Themes > Open theme folder`

#### Online method

Paste the following in `Settings > Themes`:

- `https://milbits.github.io/oldcord/src/main.css`

## Other

1. Paste the following at **the top** of the file/window:

```css
@import url("https://milbits.github.io/oldcord/src/main.css");
```

In OpenAsar, paste it in `Discord's Settings > OpenAsar > Theming`

---

# Credits

- Icon Revert Source: [Icon Revert 2023](https://github.com/davart154/Icon-Revert-2023/) by [davart154](https://github.com/davart154)
