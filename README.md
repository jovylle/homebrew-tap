# homebrew-tap

Homebrew tap for [MenubarWindows](https://github.com/jovylle/menubar-windows), a free, open source macOS
app that shows one tab per window in the empty middle of the menu bar.

```sh
brew tap jovylle/tap
brew install --cask menubarwindows
```

Apple silicon, macOS 13 or later. The current build is not notarized: after install, open it once, then
go to System Settings > Privacy & Security and click **Open Anyway**. Then switch on MenubarWindows under
Accessibility.

Update with `brew upgrade --cask menubarwindows`. Remove with `brew uninstall --cask menubarwindows`.
