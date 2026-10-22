# Claude Code Launcher releases

Downloads for **Claude Code Launcher**, a Windows app for working with Claude Code (Anthropic's
coding agent): one list of all your projects, one-click open and session resume, model and effort
control, Claude Code on Ollama models, Codex, global rules, prompts and workspaces.

- **Install**: download `Claude-Code-Launcher-Setup-<version>.exe` from the
  [latest release](https://github.com/trustxix/claude-code-launcher-releases/releases/latest)
  (per-user, no admin). The launcher checks this repository for updates and offers them in the
  status bar; it downloads and installs only when you say so.
- **Portable**: `Claude-Code-Launcher-<version>-portable.exe` runs without installing and tells
  you when a new version is out.
- **First run**: without Claude Code, the launcher installs the official build from claude.ai and
  opens the sign-in. You need a Claude subscription (Pro or Max) or an Anthropic Console account.
- **Requirements**: Windows 10 or 11, 64-bit. Windows Terminal and Git are optional.
- **Your data**: settings live in `%APPDATA%\Claude Code Launcher` and survive updates and
  reinstalls.
- **Verify**: every release ships `SHA256SUMS`; on Windows run `certutil -hashfile <file> SHA256`.
- The executables are not code-signed yet: Windows SmartScreen shows "unrecognized app" on the
  first run. Choose *More info → Run anyway* after verifying the checksum.

This repository holds release assets only. Claude Code Launcher is an unofficial tool, not made or
endorsed by Anthropic.
