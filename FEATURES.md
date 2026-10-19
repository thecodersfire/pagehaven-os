# Built-in features for pagehaven-os

Purpose: reading and ebooks

1. **prepare study and research files** — run pagehaven-os-workspace. It creates ~/Documents/pagehaven-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run pagehaven-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pagehaven-os-session-plans/.
3. **check study and source readiness** — run pagehaven-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pagehaven-os-workspace features/pagehaven-os-plan features/pagehaven-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for reading and ebooks:

1. **Anki** — net.ankiweb.Anki
2. **LibreOffice** — org.libreoffice.LibreOffice
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for reading and ebooks:

1. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
2. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
3. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
4. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
5. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
10. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
