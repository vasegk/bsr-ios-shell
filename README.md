# iOS app shell (Godot 4.1.1)

Builds an **unsigned iOS app shell**: the official Godot 4.1.1 engine with an Info.plist
(landscape, local network permission). This repository contains only an empty Godot project,
an export preset and the GitHub Actions workflow — no game content of any kind.

The workflow publishes the `ios-shell` artifact (`shell.ipa`). The owner inserts their own
locally built `.pck` into it and signs/installs the result for personal use.
