# OldCord

A Discord theme that tries to restore its 2020 UI

 By default, it removes profile effects (like banners) and clan tags. See `addons` below to get them back!

![Preview](https://raw.githubusercontent.com/milbits/oldcord/master/.github/preview.webp)

> [!IMPORTANT]
> - For the old grey colors, use the "Ash" theme in `Appearance` under settings
>   - Don't use vencord's "Client Theme" plugin, use Discord's own theme picker (with fakenitro if needed)
> - Enable "Sync Profile Themes" in `Settings > Accessibility` to fix broken profile colors
> - Disable "display name style" in `Settings > Accessibility`  if you don't want the flashy names
> - UI Density should be on default, i won't support the other 2 options (they still kinda work, though)
> - If you use BetterFolders, expect half your screen to turn blank every few months

<details> <summary><h3>Light mode</h3></summary>

Light mode is CUSTOM, it has higher contrast and slightly darker colors with adjustable tint, keeping it bright while not burning your retinas

It is currently not compatible with ShowEffects, sorry

<img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/previewLight.webp>

###### preview slightly outdated

Adjust the tint with `--oldcord-tint`, value/number has to be in HSL hue (e.g. 200). You can find it in the theme's `oldcord.theme.css` file.

</details>



<details><summary><h1>Addons</h1></summary>

## By OldCord

These are usually included in oldcord.theme.css, so all you need to do is remove `/*` in the file for each addon you want to use

| Name                   | Preview                                                                                | CSS                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Show Profile Effects (the one you prob want) | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/showeffects.webp)                                                         | `@import url("https://milbits.github.io/oldcord/src/components/showEffects.css");` |
| Show Clan Tags | im too lazy for an image                                                     | `@import url("https://milbits.github.io/oldcord/src/components/showTags.css");` |
| Old Plead Emoji        | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/emojis.webp)     | `@import url("https://milbits.github.io/oldcord/src/components/oldEmojis.css");`   |
| Context Menu hover bg. | <img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/oldcontext.webp> | `@import url("https://milbits.github.io/oldcord/src/components/oldContext.css");`  |
| [Tanza3D & KingGamingYT's NoMosaic plugin (BetterDiscord)](https://github.com/KingGamingYT/discord-no-mosaic)                         | Restores the old image layout                               |

If you use custom/quickcss, paste the CSS at the very top!

## 3rd party

| Name                                                                                                                                  | Description                                                 |
| ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [Icon Revert](https://github.com/davart154/Icon-Revert-2023/blob/main/2023%20Icon%20Revert.theme.css)                                 | Reverts all icons to pre-2023. Can cause lag (see #37) |
| [Vencord's NoMosaic plugin](https://vencord.dev/plugins/NoMosaic)                                                                     | Restores the old image layout                               |
| [hide-nitro-upselling](https://github.com/D3SOX/complementary-discord-theme/blob/master/hide-nitro-upselling.betterdiscord.theme.css) | Hides nitro ads, could cause lag                            |

---

</details>

# Installation

## 🚮[BetterDiscord](https://betterdiscord.app/)

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Save the file to your BetterDiscord theme folder:

- Windows: `%appdata%/BetterDiscord/themes`
- Linux: `~/.config/BetterDiscord/themes`
- MacOS: `/Library/Application\ Support/BetterDiscord/themes/`

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


