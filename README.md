# **luminous.fish** ✨🐟

A fast, clean, and informative prompt for the **Fish shell**.

Luminous is a heavily modified fork of the [**lucid**](https://github.com/mattgreen/lucid.fish) prompt, with substantial additions and refinements focused on usability, performance, and visual clarity.

---

## ✨ Features

* 🧾 Two-line prompt with left/right layout
* 🌿 Git status (branch, merge/rebase state, dirty indicator)
* ⚡ Background Git dirty checking (non-blocking)
* 🌐 SSH detection with OS / distro icon
* ⌨️ Vi mode indicator (`fish_vi_key_bindings`)
* 🚦 Error state indicator for failed commands
* 📐 Responsive layout that adapts to terminal width
* 🧹 Skips extra newline after `clear` and `reset`

---

## 🚀 Installation

Using **fisher**:

```fish
fisher install KyleJKC/luminous.fish
```

Restart Fish or reload your session after installing.

---

## ⚙️ Configuration

All configuration is done via global Fish variables.
You can directly edit these variables in `luminous.fish` or override them in `config.fish` before the prompt loads.

Examples:

```fish
set -g luminous_prompt_symbol "λ"
set -g luminous_dirty_indicator "*"
set -g luminous_cwd_color cyan
set -g luminous_git_color magenta
```

Enable Git status in `$HOME` (disabled by default):

```fish
set -g luminous_git_status_in_home_directory 1
```

---

## 📦 Requirements

* Fish shell 3.4+
* Nerd Font (or compatible) for icons
* `git` available in `$PATH`

---

## 🧭 Attribution

This project is based on the MIT-licensed **lucid** Fish prompt.
Luminous includes significant modifications and additional features.

---

## 📄 License

MIT