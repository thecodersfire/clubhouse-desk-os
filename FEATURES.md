# Built-in features for clubhouse-desk-os

Purpose: club administration

1. **organize work and records** — run clubhouse-desk-os-workspace. It creates ~/Documents/clubhouse-desk-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run clubhouse-desk-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/clubhouse-desk-os-session-plans/.
3. **check records and task readiness** — run clubhouse-desk-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/clubhouse-desk-os-workspace features/clubhouse-desk-os-plan features/clubhouse-desk-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for club administration:

1. **GNOME Calendar** — org.gnome.Calendar
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
