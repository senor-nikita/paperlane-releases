# paperlane – Installer

PDF-Viewer und -Editor für Windows. Dieses Repository enthält nur die Installer, keinen Quellcode.

## Installieren

1. Unter [Releases](https://github.com/senor-nikita/paperlane-releases/releases/latest) die Datei `paperlane Setup <Version>.exe` herunterladen.
2. Doppelklick auf die Datei.
3. Der Installer ist nicht signiert. Windows SmartScreen zeigt deshalb „Der Computer wurde durch Windows geschützt“. Auf **Weitere Informationen** und dann auf **Trotzdem ausführen** klicken.
4. Installationsort wählen, fertig.

Voraussetzung: Windows 10 oder 11, 64 Bit.

## Prüfsumme

Zu jedem Release steht die SHA-256-Prüfsumme in den Release-Notizen. Prüfen in PowerShell:

```powershell
Get-FileHash "paperlane Setup 0.0.1.exe" -Algorithm SHA256
```

## Deinstallieren

Einstellungen → Apps → Installierte Apps → paperlane → Deinstallieren.

## Datenschutz

paperlane arbeitet vollständig lokal. Es baut keine Netzwerkverbindungen auf und sucht nicht selbst nach Updates.
