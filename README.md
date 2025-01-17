# SysBot.NET
![License](https://img.shields.io/badge/License-AGPLv3-blue.svg)

## Support Discords:

For specific support for this fork of [Zyro](https://github.com/zyro670)'s [NotForkBot.NET](https://github.com/zyro670/NotForkBot.NET) fork of [Koi](https://github.com/Koi-3088)'s [ForkBot.NET](https://github.com/Koi-3088/ForkBot.NET) of [kwsch](https://github.com/kwsch)'s [SysBot.NET](https://github.com/kwsch/SysBot.NET) repo feel free to join! (No support will be provided in the official PKHeX or PA Discord, please don't bother the devs)

[Support Server: Manu's Server](https://discord.com/invite/yWveAjKbKt)

[<img src="https://canary.discordapp.com/api/guilds/693083823197519873/widget.png?style=banner2">](https://discord.gg/yWveAjKbKt)

[usb-Botbase](https://github.com/Koi-3088/USB-Botbase) client for remote USB control for this fork.

[sys-botbase](https://github.com/olliz0r/sys-botbase) client for remote control automation of Nintendo Switch consoles.

## SysBot.Base:
- Base logic library to be built upon in game-specific projects.
- Contains a synchronous and asynchronous Bot connection class to interact with sys-botbase.

## SysBot.Tests:
- Unit Tests for ensuring logic behaves as intended :)

# Example Implementations

The driving force to develop this project is automated bots for Nintendo Switch Pokémon games. An example implementation is provided in this repo to demonstrate interesting tasks this framework is capable of performing. Refer to the [Wiki](https://github.com/kwsch/SysBot.NET/wiki) for more details on the supported Pokémon features.

## SysBot.Pokemon:
- Class library using SysBot.Base to contain logic related to creating & running Sword/Shield bots.

## SysBot.Pokemon.WinForms:
- Simple GUI Launcher for adding, starting, and stopping Pokémon bots (as described above).
- Configuration of program settings is performed in-app and is saved as a local json file.

## SysBot.Pokemon.Discord:
- Discord interface for remotely interacting with the WinForms GUI.
- Provide a discord login token and the Roles that are allowed to interact with your bots.
- Commands are provided to manage & join the distribution queue.

## SysBot.Pokemon.Twitch:
- Twitch.tv interface for remotely announcing when the distribution starts.
- Provide a Twitch login token, username, and channel for login.

## SysBot.Pokemon.YouTube:
- YouTube.com interface for remotely announcing when the distribution starts.
- Provide a YouTube login ClientID, ClientSecret, and ChannelID for login.

Uses [Discord.Net](https://github.com/discord-net/Discord.Net) , [TwitchLib](https://github.com/TwitchLib/TwitchLib) and [StreamingClientLibary](https://github.com/SaviorXTanren/StreamingClientLibrary) as a dependency via Nuget.

## Other Dependencies
Pokémon API logic is provided by [PKHeX](https://github.com/kwsch/PKHeX/), and template generation is provided by [AutoMod](https://github.com/architdate/PKHeX-Plugins/).

Permutation generation provided by [PermuteMMO](https://github.com/kwsch/PermuteMMO).

## Special Credits:
This SysBot fork is an agglomeration of different forks and other PKHeX/SysBot based programs.
Thanks to [Zyro](https://github.com/zyro670), [Koi](https://github.com/Koi-3088), [Berichan](https://github.com/berichan), [Anubis](https://github.com/Lusamine), [Archit](https://github.com/architdate), [Kurt](https://github.com/kwsch) and all the developers that contributed and will contribute to their repositories!

# License
Refer to the `License.md` for details regarding licensing.
