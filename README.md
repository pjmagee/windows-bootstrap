# Windows Bootstrap

My collection of `Windows Package Manager (winget)` import files

## Customising your own packages

You can also create your own import file from https://winget.run/


## Exporting packages

```
winget export .\my-packages.json
```

## Installing packages

```
winget import .\example-file.json --accept-package-agreements
```

## Game library managers

- Steam
- EA Desktop
- Amazon Games
- Ubisoft Connect
- Paradox Launcher
- Epic Games

```
winget import .\game-library-managers.json --accept-package-agreements
```

## Developer tools

- Visual Studio 2022
- VS code
- Docker
- Windows Terminal
- Web Tools - Fiddler & Postman
- PgAdmin

```
winget import .\developer-tools.json --accept-package-agreements
```

## Security tools

- 1Password
- Nord VPN
- GPG Encryption
- 2FA Yubi Key Manager

```
winget install .\security-tools.json --accept-package-agreements
```

## Linux Distros

- Ubuntu

```
winget import .\windows-linux-distros.json --accept-package-agreements
```