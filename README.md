# Hive Desktop

Official repository for **Hive Desktop** installers.

Do **not** use `/releases/latest/download/Hive-Setup-VERSION.exe`.
GitHub `latest` is whatever release is marked latest on this repo (right now **0.0.1.3**).
A versioned filename on that shortcut 404s if that tag does not contain that file.

Always use the **tag** URL:

`https://github.com/samkomedved319-dev/Hive-Desktop/releases/download/vX.Y.Z.W/Hive-Setup-X.Y.Z.W.exe`

## Current download

Until **0.0.1.5** is attached here, the live 0.0.1.4 installer is:

- [Hive-Setup-0.0.1.4.exe](https://github.com/samkomedved319-dev/hive-releases/releases/download/v0.0.1.4/Hive-Setup-0.0.1.4.exe)

## Next: 0.0.1.5

1. Build `Hive-Setup-0.0.1.5.exe` from HiveSOURCE (`bun run dist:win`)
2. Create a release on this repo: tag `v0.0.1.5`, attach the `.exe`, mark latest
3. Then point HiveSOURCE `latest.json` (and this repo’s `latest.json`) at:

`https://github.com/samkomedved319-dev/Hive-Desktop/releases/download/v0.0.1.5/Hive-Setup-0.0.1.5.exe`

## Releases

https://github.com/samkomedved319-dev/Hive-Desktop/releases
