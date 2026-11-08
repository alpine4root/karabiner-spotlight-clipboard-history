# Spotlight Clipboard History Keyboard Shortcut

[한국어](README.ko.md)

Open macOS Spotlight's **Clipboard history** with **Option+V (⌥V)** using [Karabiner-Elements](https://karabiner-elements.pqrs.org/).

## Installation

Requires **[macOS Tahoe 26+](https://www.apple.com/newsroom/2025/06/macos-tahoe-26-makes-the-mac-more-capable-productive-and-intelligent-than-ever/)** and **[Karabiner-Elements](https://karabiner-elements.pqrs.org/) 16+** with permissions configured.

1. Open **Complex Modifications → Add your own rule** in [Karabiner-Elements](https://karabiner-elements.pqrs.org/).
2. Paste [`karabiner-rule.json`](karabiner-rule.json), save, and press **⌥V**.

## Behavior

Sends Command+4 only when Spotlight's search field is focused. Checks immediately if Spotlight is already open, on a quick V release, or at 100ms while held, with a 300ms fallback. Blocks duplicate opening commands for 500ms.

If it does not switch, press **⌥V** again. No helper program is required.

Maintained until Apple provides a direct shortcut for Spotlight Clipboard history.
