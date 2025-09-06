## How to setup (on linux) :

First you'll need any IDE (perk of working low-level), so go get visual studio code or jetBrain IDE whatever..

Then you'll need to install the **.NET SDK** (The minimum supported version is .NET 8)

```bash
sudo apt-get update && sudo apt-get install -y dotnet-sdk-8.0
```

If on visual studio code I strongly recommend installing the `C# DEV KIT` provided by microsoft
as well as the `monogame for vs code` extension

Then install **WINE** for effect Compilation (macOS & Linux)

```bash
sudo apt-get update && sudo apt-get install -y curl p7zip-full wine64
wget -qO- https://monogame.net/downloads/net8_mgfxc_wine_setup.sh | bash
```
