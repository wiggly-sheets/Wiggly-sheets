<!--
  ============================================================================
  Profile README for github.com/wiggly-sheets
  Palette: Tokyo Night (bg #1a1b26 · blue #7aa2f7 · purple #bb9af7 · cyan #7dcfff)

  Everything below is sourced from your public repos, their READMEs, release
  tags and language breakdowns (checked 2026-11-12). Nothing is invented.

  TODO before you commit:
    1. Add your name (optional) — the whoami block currently uses your handle.
    2. Add site / email links at the bottom (commented slots are ready).
    3. Trim projects you don't want to show off.
  ============================================================================
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:7aa2f7,50:bb9af7,100:7dcfff&text=wiggly-sheets&fontSize=52&fontColor=1a1b26&fontAlignY=34&desc=macOS%20utilities%20%C2%B7%20yabai%20%26%20SketchyBar%20%C2%B7%20dotfiles&descAlignY=56&descSize=16&animation=fadeIn" width="100%" alt="wiggly-sheets" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=7AA2F7&center=true&vCenter=true&width=720&height=45&lines=if+the+OS+won%27t+do+it%2C+I+will;native+macOS+utilities+%C2%B7+Swift+%2B+SwiftUI;yabai+%C2%B7+skhd+%C2%B7+SketchyBar+%C2%B7+dotfiles;vibing" alt="typing" />

<br>

<img src="https://img.shields.io/badge/macOS-1a1b26?style=for-the-badge&logo=apple&logoColor=7dcfff" alt="macOS">
<img src="https://img.shields.io/badge/Swift-1a1b26?style=for-the-badge&logo=swift&logoColor=ff9e64" alt="Swift">
<img src="https://img.shields.io/badge/SwiftUI-1a1b26?style=for-the-badge&logo=swift&logoColor=7aa2f7" alt="SwiftUI">
<img src="https://img.shields.io/badge/SketchyBar-1a1b26?style=for-the-badge&logo=macos&logoColor=bb9af7" alt="SketchyBar">
<img src="https://img.shields.io/badge/yabai-1a1b26?style=for-the-badge&logo=windowsterminal&logoColor=7dcfff" alt="yabai">
<img src="https://img.shields.io/badge/Homebrew-1a1b26?style=for-the-badge&logo=homebrew&logoColor=e0af68" alt="Homebrew">
<img src="https://img.shields.io/badge/zsh-1a1b26?style=for-the-badge&logo=gnubash&logoColor=9ece6a" alt="zsh">
<img src="https://img.shields.io/badge/Neovim-1a1b26?style=for-the-badge&logo=neovim&logoColor=9ece6a" alt="Neovim">
<img src="https://img.shields.io/badge/OpenWrt-1a1b26?style=for-the-badge&logo=openwrt&logoColor=7dcfff" alt="OpenWrt">
<img src="https://img.shields.io/badge/Linux-1a1b26?style=for-the-badge&logo=linux&logoColor=e0af68" alt="Linux">
<img src="https://img.shields.io/badge/TypeScript-1a1b26?style=for-the-badge&logo=typescript&logoColor=7aa2f7" alt="TypeScript">
<img src="https://img.shields.io/badge/Raycast-1a1b26?style=for-the-badge&logo=raycast&logoColor=f7768e" alt="Raycast">

<br><br>

<img src="https://komarev.com/ghpvc/?username=wiggly-sheets&style=for-the-badge&color=1a1b26&labelColor=24283b&label=VISITORS" alt="visitors">

</div>

---

## `> whoami`

```console
wiggly@macbook ~ % whoami

wiggly-sheets
macOS tinkerer · native app builder · dotfile hoarder
```

I write small native tools for the parts of macOS that only exist behind a
`defaults write` command, a config file, or not at all.

Nearly all of them started as a personal annoyance: **renaming Spaces**,
**previewing a SketchyBar config before breaking it**, **remembering which
`defaults` key did what**.

I run yabai, skhd and SketchyBar, keep the whole setup in
[dotfiles-mac](https://github.com/wiggly-sheets/dotfiles-mac), and ship the
parts worth sharing as GitHub releases through my own Homebrew tap.

---

## `> shipping`

<div align="center">

<a href="https://github.com/wiggly-sheets/SketchyBar-Studio/releases/latest"><img src="https://img.shields.io/github/v/release/wiggly-sheets/sketchybar-studio?style=for-the-badge&color=1a1b26&labelColor=24283b&label=SketchyBar%20Studio" alt="SketchyBar Studio release"></a>
<a href="https://github.com/wiggly-sheets/swiftdefaults/releases/latest"><img src="https://img.shields.io/github/v/release/wiggly-sheets/swiftdefaults?style=for-the-badge&color=1a1b26&labelColor=24283b&label=SwiftDefaults" alt="SwiftDefaults release"></a>
<a href="https://github.com/wiggly-sheets/wallpaper-selector/releases/latest"><img src="https://img.shields.io/github/v/release/wiggly-sheets/wallpaper-selector?style=for-the-badge&color=1a1b26&labelColor=24283b&label=Wallpaper%20Selector" alt="Wallpaper Selector release"></a>

</div>

```console
$ brew tap wiggly-sheets/homebrew-tap
$ brew install --cask sketchybar-studio swiftdefaults wallpaper-selector
```

> Every cask in the tap is generated from templates and follows the latest
> stable upstream release, so `brew upgrade` just works.

---

## `> currently-building`

I like software that feels **native, keyboard-driven, and one annoyance away from existing**.

<table>
<tr>
<td width="33%" align="center" valign="top">

### 🍎 Native Utilities

Swift & SwiftUI

Tweak the OS without
touching Terminal.

</td>
<td width="33%" align="center" valign="top">

### 🪟 Window Management

yabai · skhd · JankyBorders

Tiling, borders,
Spaces that keep their names.

</td>
<td width="33%" align="center" valign="top">

### 🎨 SketchyBar

Live preview & editing

27 palettes, 14 plugins,
backups before every write.

</td>
</tr>
<tr>
<td width="33%" align="center" valign="top">

### 🐚 Dotfiles

Managed with stow

zsh, Neovim, tmux —
macOS *and* Linux.

</td>
<td width="33%" align="center" valign="top">

### 📦 Distribution

Homebrew tap

Generated casks that
track upstream releases.

</td>
<td width="33%" align="center" valign="top">

### 📡 The Edge

OpenWrt & routing

WrtFetch on the router,
VPN routing at home.

</td>
</tr>
</table>

---

## `> projects`

### Built from scratch

|      | Project                                                                       | What it actually does                                                                     |
| :--: | ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
|  🎛️  | **[SketchyBar Studio](https://github.com/wiggly-sheets/SketchyBar-Studio)**   | Editor for your *existing* SketchyBar config: live preview, 27 palettes, 14 plugins, backups |
|  🧰  | **[SwiftDefaults](https://github.com/wiggly-sheets/swiftdefaults)**           | Browse and toggle macOS defaults in plain English — every change revertible                |
|  🖼️  | **[Wallpaper Selector](https://github.com/wiggly-sheets/wallpaper-selector)** | Menu-bar wallpaper picker and rotator; local folders, themes, light/dark matching          |
|  📡  | **[WrtFetch](https://github.com/wiggly-sheets/WrtFetch)**                     | Fastfetch-inspired system info for OpenWrt, pure BusyBox `ash` — no Bash required          |
|  🎸  | **[Is This Band…?](https://github.com/wiggly-sheets/is-this-band-raycast-extension)** | Raycast extension for emo/punk/metal/hardcore/indie verdicts                       |
|  ⚙️  | **[dotfiles-mac](https://github.com/wiggly-sheets/dotfiles-mac)**             | The entire macOS setup in one repo                                                         |
|  🐧  | **[dotfiles-linux](https://github.com/wiggly-sheets/dotfiles-linux)**         | The other side of the same habit                                                           |
|  📦  | **[homebrew-tap](https://github.com/wiggly-sheets/homebrew-tap)**             | Casks and a formula, regenerated from templates on every upstream release                  |

### Forks I actually maintain

|      | Project                                                                    | What changed                                                    |
| :--: | -------------------------------------------------------------------------- | --------------------------------------------------------------- |
|  ⌨️   | **[spaces-renamer](https://github.com/wiggly-sheets/spaces-renamer)**      | Rewritten for Tahoe, plus automatic yabai space naming           |
|  🧭  | **[Spacemap](https://github.com/wiggly-sheets/Spacemap)**                  | Interactive 2D map of yabai workspaces                           |
|  🖱️   | **[tfm-tui-mac](https://github.com/wiggly-sheets/tfm-tui-mac)**            | Mouse-first terminal file manager, ported to macOS              |
|  💡  | **[Fluor](https://github.com/wiggly-sheets/Fluor)**                        | Per-app Fn key modes — also distributed via the tap              |

<sub>Standing on the shoulders of **yabai**, **SketchyBar**, **JankyBorders**, **skhd** and **KBPulse**.</sub>

---

## `> stack`

```text
┌────────────────────────────────────────────────┐
│                                                │
│  os           macOS                            │
│  languages    Swift · Shell · TypeScript       │
│  ui           SwiftUI · AppKit · SketchyBar    │
│  window mgmt  yabai · skhd · JankyBorders      │
│  terminal     zsh · tmux · Neovim · Yazi       │
│  tools        stow · mise · atuin · Raycast    │
│  ships via    brew tap + GitHub Releases       │
│  also         Linux dotfiles · OpenWrt routers │
│  philosophy   If the OS won't do it, I will.   │
│                                                │
└────────────────────────────────────────────────┘
```

---

## `> stats`

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=wiggly-sheets&theme=tokyonight" alt="Profile summary" />

<br><br>

<img height="170" src="https://github-readme-stats-fast.vercel.app/api?username=wiggly-sheets&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b26&title_color=7aa2f7&icon_color=bb9af7&text_color=c0caf5" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=wiggly-sheets&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=1a1b26&title_color=7aa2f7&text_color=c0caf5" alt="Top languages" />

<br><br>

<img width="100%" src="https://streak-stats.demolab.com?user=wiggly-sheets&theme=tokyonight&hide_border=true&background=1a1b26&ring=bb9af7&fire=ff9e64&currStreakLabel=7aa2f7&sideLabels=c0caf5&dates=565f89" alt="Contribution streak" />

</div>

---

## `> dotfiles`

```console
$ ls ~/.dotfiles

alacritty      karabiner    skhd
atuin          kitty        sketchybar
btop           nvim         tmux
ghostty        raycast      yazi
hammerspoon    sesh         zsh
```

One folder per tool, one `stow` away from being installed.

---

<div align="center">

<img src="https://github.com/user-attachments/assets/d9861bd1-1de2-48ca-87dd-f2f4a78b8cbf" width="640" alt="vibing" />

<br><br>

**The best part of a computer is how much of it you can make yours.**

<br>

`─────────────────────────────── ◈ ───────────────────────────────`

<sub>native macOS utilities · yabai &amp; SketchyBar · dotfiles for two operating systems · a router that shouldn't be this interesting</sub>

<br><br>

<!-- add your links when you have them, e.g.
<a href="https://yoursite.dev"><img src="https://img.shields.io/badge/site-1a1b26?style=for-the-badge&logo=safari&logoColor=7dcfff"></a>
<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/email-1a1b26?style=for-the-badge&logo=gmail&logoColor=f7768e"></a>
-->

</div>
