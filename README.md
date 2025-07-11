# Battle.net (Unofficial)
## Building
> **_NOTE:_**  With org.winestaging.Sdk and org.winestaging.Platform installed.
```console
flatpak run org.flatpak.Builder build-dir --repo=../Compatpak/repo --force-clean com.blizzard.Battlenet.yml
```
## Installing
```console
flatpak install --user ../Compatpak/repo com.blizzard.Battlenet
```
## Running
```console
flatpak run com.blizzard.Battlenet
```
## Removing
```console
flatpak remove com.blizzard.Battlenet
```
## Troubleshooting
- Check if Flatpak is installed
```console
flatpak list | grep Battlenet
```
- Enter Flatpak in command line mode
```console
flatpak run --command=sh com.blizzard.Battlenet
```
## Flatpak locations
- Installation directory             = /var/lib/flatpak/app/com.blizzard.Battlenet/
- Wine prefix                        = ~/.var/app/com.blizzard.Battlenet/data/wine
