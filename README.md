# Hive Desktop

Official repository for **Hive Desktop** installers.

Source lives on **HiveSOURCE**. This repo is Windows Setup.exe releases only.

Do **not** use `/releases/latest/download/Hive-Setup-VERSION.exe`.
GitHub `latest` is whatever release is marked latest on this repo.
A versioned filename on that shortcut 404s if that tag does not contain that file.

Always use the **tag** URL. Tags have **no `v` prefix**:

`https://github.com/samkomedved319-dev/Hive-Desktop/releases/download/0.0.1.7.2/Hive-Setup-0.0.1.7.2.exe`

## Current download

- **Version**: 0.0.1.7.2
- **Installer**: [Hive-Setup-0.0.1.7.2.exe](https://github.com/samkomedved319-dev/Hive-Desktop/releases/download/0.0.1.7.2/Hive-Setup-0.0.1.7.2.exe)
- **Platform**: Windows 10 / 11 (64-bit)
- **All versions**: https://github.com/samkomedved319-dev/Hive-Desktop/releases

## Next: 0.0.1.7.3

1. Pull latest HiveSOURCE `main`
2. Double-click `make-installer.bat` and leave the window open (5–15 min)
3. Attach `release\Hive-Setup-0.0.1.7.3.exe` to tag `0.0.1.7.3` (no `v`), then mark that release **Latest**
4. Then point HiveSOURCE `latest.json` (and this repo’s `latest.json`) at:

`https://github.com/samkomedved319-dev/Hive-Desktop/releases/download/0.0.1.7.3/Hive-Setup-0.0.1.7.3.exe`

Do not publish that URL until the exe is actually attached. Until then, Update stays on **0.0.1.7.2** so it does not 404.

## What 0.0.1.7.3 is

The full 0.0.1.7 line, plus this update.

- A DM is only you and one person. Hive stays out.
- Invite a bot from the right panel (HiveBox). You add, or the other person adds — both from that panel.
- HiveBox has Crew / Work / Desk. Office is the house icon, not this panel.
- @ in a DM only lists bots already in that thread.
- Hive Free: NVIDIA NIM Lightning. GLM is off.
- Required public username after login. People add you with `@username`.
- Optional BYOK: OpenRouter / OpenAI / Anthropic / Google, routed by key prefix. Skip = NIM.
- Chat `@` mentions only Workers roster bots, not people.
- Groups: people by username plus bots.
- Loop agents in chat + Workers. They never auto-run on a greeting, and they stay off DMs.
- Office is the floor only — no Nudge-pair panel, no WebGL crash banner.
- Buddy in the left rail. 1,000,000-token daily quota per username.
