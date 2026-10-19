# Built-in features for pagehaven-os

Purpose: reading and ebooks

1. **prepare study and research files** — run pagehaven-os-workspace. It creates ~/Documents/pagehaven-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run pagehaven-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pagehaven-os-session-plans/.
3. **check study and source readiness** — run pagehaven-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pagehaven-os-workspace features/pagehaven-os-plan features/pagehaven-os-check "$HOME/.local/bin/"
