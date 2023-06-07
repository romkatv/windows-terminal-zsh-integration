# Zsh Integration for Windows Terminal

If you are using Windows Terminal with WSL and Zsh, this Zsh plugin is for you.
It forces Zsh to report its current working directory to Windows Terminal so
that features of Windows Terminal such as *Open tab in the same directory* work
as expected.

This plugin achieves the same thing as the [code snippet](
  https://learn.microsoft.com/en-us/windows/terminal/tutorials/new-tab-same-directory#zsh)
in the official Windows Terminal documentation but with fewer bugs and better
performance.

## Installation

1. Clone the repo.
```zsh
git clone https://github.com/romkatv/windows-terminal-zsh-integration.git ~/windows-terminal-zsh-integration
```
2. Add the following line to `~/.zshrc`:
```zsh
source ~/windows-terminal-zsh-integration/windows-terminal-zsh-integration.plugin.zsh
```

*Using a plugin manager? You can install `windows-terminal-zsh-integration` the
same way as any other Zsh plugin hosted on GitHub.*
