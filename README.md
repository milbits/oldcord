# OldCord 🏳️‍🌈🏳️‍⚧️

A Discord theme that tries to restore its 2020 UI, while preserving most features.

By default, it removes profile effects (like banners) and clan tags. See `addons` below to get them back!

![Preview](https://raw.githubusercontent.com/milbits/oldcord/master/.github/preview.webp)

> [!IMPORTANT]
>
> - **Enable `"Apply theme on other users' profiles"` in `Settings > Appearence` to fix broken profile colors**
> - **For the old colors, use the `"Ash"` theme in `Settings > Appearance`**
>   - Don't use vencord's "Client Theme" plugin; use Discord's own theme picker (with fakenitro if needed)
> - UI Density should be on default; the other options aren't supported (they still kind of work, though)
> - Disable "display name style" in `Settings > Accessibility` if you want!

<details> <summary><h3>Custom Light mode</h3></summary>

Light mode is custom, with better contrast and darker colors that won't blind you as much! basically if discord actually gave a shit about it. I know this goes against what the theme is trying to do, but who cares, right? :3

ash/darkmode has priority, so lightmode a bit inconsistent.

<img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/previewLight.webp>

###### preview very outdated

</details>

<details><summary><h1>Addons</h1></summary>

## By OldCord

These are usually included in oldcord.theme.css, so all you need to do is remove `/*` in the file for each addon you want to use

| Name                                                                                                          | Preview                                                                                     | CSS                                                                                |
| ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Show Profile Effects (the one you prob want)                                                                  | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/showeffects.webp) | `@import url("https://milbits.github.io/oldcord/src/components/showEffects.css");` |
| Show Clan Tags                                                                                                | im too lazy for an image                                                                    | `@import url("https://milbits.github.io/oldcord/src/components/showTags.css");`    |
| Old Plead Emoji                                                                                               | ![Image](https://raw.githubusercontent.com/milbits/oldcord/master/.github/emojis.webp)      | `@import url("https://milbits.github.io/oldcord/src/components/oldEmojis.css");`   |
| Context Menu hover bg.                                                                                        | <img src=https://raw.githubusercontent.com/milbits/oldcord/master/.github/oldcontext.webp>  | `@import url("https://milbits.github.io/oldcord/src/components/oldContext.css");`  |
| [Tanza3D & KingGamingYT's NoMosaic plugin (BetterDiscord)](https://github.com/KingGamingYT/discord-no-mosaic) | Restores the old image layout                                                               |

If you use custom/quickcss, paste the CSS at the very top!

## 3rd party

| Name                                                                                                                                  | Description                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| [Old Roles](https://github.com/KhimarikMayer/OldRoles)                                                                                | Improves gradient role borders and adds the old role design as a standalone option |
| [Icon Revert](https://github.com/davart154/Icon-Revert-2023/blob/main/2023%20Icon%20Revert.theme.css)                                 | Reverts all icons to pre-2023. Can cause lag (see #37)                             |
| [Vencord's NoMosaic plugin](https://vencord.dev/plugins/NoMosaic)                                                                     | Restores the old image layout                                                      |
| [KingGamingYT's NoMosaic plugin](https://betterdiscord.app/plugin/NoMosaic)                                                           | BetterDiscord NoMosaic plugin                                                      |
| [NewOldProfiles](https://betterdiscord.app/plugin/NewOldProfiles)                                                                     | Restores period-accurate profiles w/ modern enhancements                           |
| [hide-nitro-upselling](https://github.com/D3SOX/complementary-discord-theme/blob/master/hide-nitro-upselling.betterdiscord.theme.css) | Hides nitro ads, could cause lag                                                   |

---

</details>

# Installation

## 😺[Vencord](https://github.com/Vendicated/Vencord)

#### Online

Paste the following in `Settings > Themes`:

- `https://milbits.github.io/oldcord/src/main.css`

#### Local

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Move the file to the Vencord theme folder:

- `Settings > Themes > Open theme folder`

## 🚮[BetterDiscord](https://betterdiscord.app/)

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (Rightclick > "Save As", or open link and press <kbd>Ctrl</kbd> + <kbd>S</kbd>)
2. Save/move the file to your BetterDiscord theme folder:

- Windows: `%appdata%/BetterDiscord/themes`
- Linux: `~/.config/BetterDiscord/themes` (flatpak: `~/.var/app/com.discordapp.Discord/config/BetterDiscord/themes/`)
- MacOS: `/Library/Application\ Support/BetterDiscord/themes/`

## 🎛️ Other

1. Paste this at **the very top** of the CSS file/window:

```css
@import url("https://milbits.github.io/oldcord/src/main.css");
```
