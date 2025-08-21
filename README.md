<p align="center"><em>“Who hath ascended up into heaven, or descended? who hath gathered the wind in his fists? who hath bound the waters in a garment? who hath established all the ends of the earth? what is his name, and what is his son's name, if thou canst tell?”</em><br><em>- Proverbs 30:4 (KJV)</em></p>

<p align="center"><em>“For God so loved the world, that he gave his only begotten Son, that whosoever believeth in him should not perish, but have everlasting life.”</em><br><em>“For God sent not his Son into the world to condemn the world; but that the world through him might be saved.”</em><br><em>- John 3:16-17 (KJV)</em></p>



<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=moraroy&theme=transparent&show_icons=true&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=moraroy&theme=transparent&hide_border=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=moraroy&theme=transparent&show_icons=true&hide_border=true&layout=compact" width="48%" />
</p>



<p align="center">
  <img src="https://github.com/cchrkk/NSLOSD-DL/raw/main/logo.svg" width=40% height=auto
</p>

<h1 align="center">
NonSteamLaunchers 🚀
</h1>

This script installs the latest UMU & GE-Proton and installs NonSteamLaunchers under one unique Proton prefix folder in your compatdata folder path called "NonSteamLaunchers" and adds them to your Steam Library. It will also add the games automatically in real time and will attempt to remove the games from your library in real time when you uninstall a game from a launcher. Collections for your games will also be created per launcher.
NSL can be used on Desktop or in Game Mode, and don't you worry,
Local Saves and Cloud saves are supported, as well as multiplayer/online support (because you're using the launchers). Obviously, certain anticheat games will not work on linux enviroments; this is on a game to game basis.

<h1 align="center">
Features  ✅
</h1>

- Automatic installation of the most popular launchers in your Steam Deck 🎮

- Handle automatically the download and installation of your chosen launchers and the games, artwork included! ⌚️ 

- MicroSD Support 💾 This script supports moving the entire prefix to a microSD. The script will install launchers and games to your SD card, and the launchers in Steam will point to the SD card installation. This allows you to save internal storage space on your Steam Deck!

- ProtonTricks is compatible with NonSteamLaunchers default installation (one prefix). This will add a NonSteamLaunchers shorcut in your library...this shortcut doesnt do anything. All you have to do is simply "Hide this Game" in your Library. Right click its properties and choose "Manage" and "Hide this Game". You never have to worry about it again! If you were to open up ProtonTricks to fix any game or launcher it is now accessible! 

- In case you didnt know, you can also choose to check mark "Separate App Id's" when installing a launcher, this will install all launchers in each of their own prefix. Automatically working with ProtonTricks!

- Command Line Ready, you can call it from online, heres an example of installing a launcher ``` /bin/bash -c 'curl -Ls https://raw.githubusercontent.com/moraroy/NonSteamLaunchers-On-Steam-Deck/main/NonSteamLaunchers.sh | nohup /bin/bash -s -- "Epic Games"' ```

- NSL can in fact be installed on many linux distros, feel free to try, here are some examples of some... Ubuntu LTS, ChimeraOS, Nobara and Arch Linux as well as any KDE Environments such as this opensuse - tumbleweed - wayland , if for any reason you find that NonSteamLaunchers installs perfectly or not, let me know!

- RemotePlayWhatever is also bundled with NSL to allow for local and co-op play between non steam games, this is created by m4Engi, here is the repo [here](https://github.com/m4dEngi/RemotePlayWhatever)

- Ludusavi is also pre-installed and setup for NSL for your games save backups. Not all games will work with this yet so bare this in mind when deleted or uninstalling games that are arent backed up yet, here is the repo [here](https://github.com/mtkennerly/ludusavi)

In both versions of NonSteamLaunchers, Desktop or Decky, NSL will back up your games saves here automatically ```/home/deck/NSLGameSaves``` The Desktop Version only does this once, at the start of when the script is opened and you see the main options list. The decky plugin version does this on every manual scan that you do.

- [UMU Launcher](https://github.com/Open-Wine-Components/umu-launcher) is automatically used and is processed for each game and Launcher. Proton GE will be used where necessary.

### Notes
- With NSL youre able to send notes to each other and communicate to other NSL users via a hashtag in your note at the beginning, write #nsl and leave a space, and then type your actual note. The script will then look for that note and send it through the api and spit it back out for that non-steam game. Everyone who uses NSL will then receive it and it will be added to the "NSL Community Note". This is to allow people to have first hand information about their games right in front of them from others! Currently you can participate only if you send a note! Once you created a note, open up NonSteamLaunchers and press the ❤️. This is an expiremental feature so keep that in mind!


# As Seen on
just to name a few!...there are much more videos and articles out there just wanted to share some resources on how to install and how the program works.
## Videos
- [Linus Tech Tips](https://www.youtube.com/watch?v=tdR-bxvQKN8&t=885s) (starting at 14:45)
- [GameTechPlanet](https://www.youtube.com/watch?v=jE1qD3yzrks)
- [NerdZap](https://www.youtube.com/watch?v=t2EzbKkbS1Q)
- [Joserra y sus cosicas](https://www.youtube.com/watch?v=6ETxmbzRODQ)
- [Steam Deck In Hand](https://www.youtube.com/watch?v=_j3HV6yyGjI)
- [Steam Deck Gaming](https://www.youtube.com/watch?v=svOj4MTEAVc)
- [BakaKuma](https://www.youtube.com/watch?v=QluZ3UGYoKo)
- [SteamFlow](https://www.youtube.com/watch?v=aud5F6iwA0s)
- [Hooandee - 6 Hour Video](https://www.youtube.com/watch?v=OGmwtSS-zoE&t=7023s) (starting at 1:57:23)
- [Central Deck](https://www.youtube.com/watch?v=oIKL1JRn4cw)
- [Goldenoptic Gaming](https://www.youtube.com/watch?v=dMnUn3U0dPE)
- [Deck Ready](https://www.youtube.com/watch?v=9Ap_suofBV8&t=196s) (starting at 3:16)
- [Steam Deck Checker](https://www.youtube.com/watch?v=vFRllG15jjs)

## Articles
- [Gaming On Linux - Non-Steam Launchers Tool for Installing Popular Game Stores](https://www.gamingonlinux.com/2025/01/nonsteamlaunchers-tool-for-installing-popular-game-stores-working-on-better-desktop-linux-support/)
- [Steam Deck HQ - Non-Steam Launchers New Update Community Notes](https://steamdeckhq.com/news/nonsteamlaunchers-new-update-community-notes/)
- [Windows Central - How to Install Decky Loader on Steam Deck](https://www.windowscentral.com/gaming/how-to-install-decky-loader-on-steam-deck)
- [Dexerto - Non-Steam Launchers on Steam Deck](https://www.dexerto.com/tech/nonsteamlaunchers-steam-deck-2808063/)
- [MSN - Steam Deck: How to Install Epic Games Launcher with Decky Loader](https://www.msn.com/en-ca/news/technology/steam-deck-how-to-install-epic-games-launcher-with-decky-loader/ar-BB1pW1Ht)
- [PCMAG - How to Install Third-Party Game Launchers on Steam Deck](https://www.pcmag.com/how-to/steam-deck-install-third-party-game-launchers)

<p align="center">
    ▶️ **YouTube Tutorial** 🡺🡺🡺 <a href="https://youtu.be/sxMmI8I9G_g">Watch here</a> 🡸🡸🡸 ▶️
</p>
<p align="center">
    📖 **Step-by-step Article** 🡺🡺🡺 <a href="https://steamdeckhq.com/news/nonsteamlaunchers-adds-scan-support-launchers">here</a> 🡸🡸🡸 📖
</p>

---






<h1 align="center">
Currently Working On 👷‍♂️
</h1>

* Decky Loader Plugin is available [here](https://github.com/moraroy/NonSteamLaunchersDecky) and the pull request for it [here](https://github.com/SteamDeckHomebrew/decky-plugin-database/pull/677) and can be installed with this big button, only press this button if you have Decky Loader installed already
* Working on Flatpak version

 <p align="center">
  <a name="download button" href="https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck/releases/download/v3.9.6/NSLPlugin.desktop"><img src="https://user-images.githubusercontent.com/98482469/242361563-33f31d3d-9a69-4fca-a928-207a5d17a98f.png"  alt="Download NSL Decky Plugin" width="350px" style="padding-top: 15px;"></a>

---

**Windows Installation Steps**:

1. **Sign in to GitHub** and go to this [link](https://github.com/SteamDeckHomebrew/decky-loader/actions/workflows/build-win.yml).

2. Choose the latest link or whichever version works for you.

3. Scroll down to **"Artifacts"** and download **"PluginLoader Win"**. This is a zip file that you need to extract on your Windows machine. Make sure you're signed in to see the download link.

4. Download **NSLPluginWindows.exe** from [here](https://github.com/moraroy/NonSteamLaunchersDecky/releases).

5. Run **NSLPluginWindows.exe** first. This will also create the necessary cef debugging file for Decky Loader.

6. Run either **No_console.exe** or **Plugin Loader.exe**, depending on your preference.

7. Go into **Game Mode** or **Big Picture Mode** to see the Decky Loader plugin and NonSteamLaunchers.


This setup will automatically add all your non-Steam games with artwork, correctly formatted for Windows. Only scanning will work; nothing else will function, so you can either auto-scan or manually scan your games.

<h1 align="center">
How to Install the Desktop Version 🔧
</h1>

<p align="center">
  <a name="download button" href="https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck/releases/download/v3.9.1/NonSteamLaunchers.desktop"><img src="https://user-images.githubusercontent.com/98482469/242361563-33f31d3d-9a69-4fca-a928-207a5d17a98f.png"  alt="Download NonSteamLaunchers" width="350px" style="padding-top: 15px;"></a>
</p>
<!--- Thanks https://github.com/Heus-Sueh -->

* Go to desktop mode, click the download button above and it should download the .desktop file in your Downloads folder.
* Go to your downloads folder, click the NonSteamLaunchers icon, it will download and run the latest NonSteamLaunchers.sh from this repository and run it.
* You will simply have to choose which launcher to install and let the script handle the rest. 💻 No files are left in your "Downloads" they are deleted after installation.
* After running the script, you'll find the new launchers in your library under the non-steam tab. Click a launcher to see your installed games from that store, and launch them directly from Steam! If you have downloaded a game inside of your launcher, the scanner should have added it to our library, if not simply run a scan. Restart your Deck or quit and reopen Steam and the NSLGameScanner.service should add it to your library, even in gamemode! 🥳

<p align="center">

<h1 align="center">
How to Run 🏃‍♂️
</h1>

+ Select your launchers and hit OK. This will install your selected launchers. (Optionally, check "separate app ids", to install each launcher in its own prefix)
+ ❤️ = this will send and recieves any notes you have created to the community using the ```#nsl``` tag at the beginning of your note.
+ Uninstall = uninstalls the specific launchers and possibly its games too, each launcher uninstallation is different.
+ 🔍 = Pressing the magnifying glass will stop the NSL Sanner and prompt you to restart it if needed. When you open NSL the scanner only runs once. So restarting it activates the real time service file for active scanning.
+ Start Fresh = Wipes all of NSL, all the preixes, launchers, games, etc. Shortcuts will remain, and your game save backups, if any, at ```/home/deck/NSLGameSaves``` will not be deleted.
+ Move to SD Card = moves each prefix to your SD Card, this is legacy code and probably still needs work.
+ Update Proton GE = this will update and install Proton GE and UMU if you dont have it already, the script attempts to do this on each launcher install but you can do it manually and help the script before hand if you want.
+ 🖥️ Off = this simply turns off your screen, useful if your doing long downloads to save battery.
+ NSLGameSaves = this will inject your game saves from ```/home/eck/NSLGameSaves``` into its correct locations using ludusavi into your launchers. Use this if you pressed "Start Fresh" and have downloaded your launchers again, dont download your games until you have pressed this button.
+ README = opens up this read me file.



<h1 align="center">
Command Lines 🫡
</h1>
The NSL script can be called from online via bash, heres an example of it installing a launcher

```/bin/bash -c 'curl -Ls https://raw.githubusercontent.com/moraroy/NonSteamLaunchers-On-Steam-Deck/main/NonSteamLaunchers.sh | nohup /bin/bash -s -- "Epic Games"'```


- All launchers can be installed by calling their name like this  ```"Epic Games"``` ```"Ubisoft Connect"``` etc.
- All launchers can be uninstalled by calling their name like this ```"Uninstall Epic Games"``` ```"Uninstall Ubisoft Connect"``` etc.
- Here is the list of commands that can also be called
  
- ```"Start Fresh"``` ```"Update Proton-GE"``` ```"Stop NSLGameScanner"``` ```"Move to SD Card"```

- The "Move to SD Card" function can only be called in this format
  
```/bin/bash -c 'curl -Ls https://raw.githubusercontent.com/moraroy/NonSteamLaunchers-On-Steam-Deck/main/NonSteamLaunchers.sh | nohup /bin/bash -s -- "Move to SD Card" "EpicGamesLauncher"```

- The format of "EpicGamesLauncher" comes from the user choosing to either "Separate App ID's" or use the default installation prefix "NonSteamLaunchers" in the compatdata folder. This would be named differently for each launcher. Otherwise the command line would then only be 

```/bin/bash -c 'curl -Ls https://raw.githubusercontent.com/moraroy/NonSteamLaunchers-On-Steam-Deck/main/NonSteamLaunchers.sh | nohup /bin/bash -s -- "Move to SD Card" "NonSteamLaunchers"```





<h1 align="center">
Supported Stores 🛍
</h1>

- Unreal Engine (via Epic Games) ✔️
- Amazon Games Launcher ✔️
- Battle.net ✔️
- EA App ✔️
- Epic Games ✔️
- GOG Galaxy ✔️
- Humble Games Collection ✔️
- IndieGala ✔️
- Itch.io ✔️
- Legacy Games ✔️
- Rockstar Games Launcher ✔️
- Ubisoft Connect ✔️
- Glyph ✔️
- Playstation Plus ✔️
- VK Play ✔️
- HoYoPlay ✔️
- Nexon Launcher ✔️
- Game Jolt Client ✔️
- Artix Game Launcher ✔️
- ARC Launcher ✔️
- Pokémon Trading Card Game Live ✔️
- Minecraft Launcher(Legacy) (Java Edition doesnt work but its for Dungeons) ✔️
- PURPLE Launcher ✔️
- Plarium Play ✔️
- VFUN Launcher ✔️
- Tempo Launcher ✔️
- Antstream Arcade ✔️
- RemotePlayWhatever ✔️
- NVIDIA GeForce NOW (Native Linux) ✔️
- STOVE Client ✔️

<h1 align="center">
Supported Streaming Sites for games and as well as any website. 🌐
</h1>

- Website Shortcut Creator ✔️
- Fortnite ✔️
- Venge ✔️
- PokéRogue ✔️
- Xbox Game Pass ✔️
- Better xCloud ✔️
- GeForce Now ✔️
- Amazon Luna ✔️
- Boosteroid Cloud Gaming ✔️
- Stim.io ✔️
- WebRcade ✔️
- WebRcade Editor ✔️
- Afterplay.io ✔️
- OnePlay ✔️
- AirGPU ✔️
- CloudDeck ✔️
- JioGamesCloud ✔️
- WatchParty ✔️
- Rocketcrab ✔️
- Netflix ✔️
- Amazon Prime Video ✔️
- Disney+ ✔️
- Hulu ✔️
- Tubi ✔️
- Youtube ✔️
- Twitch ✔️
- Plex ✔️
- Apple TV+ ✔️
- Crunchyroll ✔️


<h1 align="left">
Finds Games Automatically
</h1> 

"NSLGameScanner.service" is also live when you use this script and continues after the script is closed and even works after your Steam Deck has restarted. This works in the background as a service file to automatically add your games to your library on every Steam restart. Currently adds:
- Epic Games 🎮          💾 Full SD Card Support
- Ubisoft Connect 🎮     💾 Full SD Card Support
- EA App 🎮              💾 Full SD Card Support not sure 
- Gog Galaxy 🎮          💾 Full SD Card Support
- Battle.net 🎮
- Amazon Games 🎮        💾 Full SD Card Support
- Itch.io 🎮
- Legacy Games 🎮
- VK Play 🎮             💾 Full SD Card Support
- HoYoPlay 🎮            💾 Full SD Card Support
- Game Jolt Client 🎮    💾 Full SD Card Support
- Minecraft Launcher 🎮
- Waydroid Apps 🎮
- Humble Games Collection 🎮 💾 Full SD Card Support
- NVIDIA GeForce NOW (Native) - You must "Favorite" the game

## Chrome Bookmarks
The scanner will pick these up automatically. But for Geforce Now only, change the name of the bookmark to your actual game name. Or you can press "Play" then Use "Ctrl + D". As long as the game name is in the Bookmark Name.
- Xbox Game Pass
- GeForce Now
- Amazon Luna

To stop the NSLGameScanner.service, open up NSL and hit "Stop NSLGameScanner" it will then ask you if you want to restart it, click no, and that's it.



<!--- TODO: handful of broken icons (cf. 🡺🡺🡺 ); probably should remove or replace them with more common font to handle unicode-->





<h1 align="center">
Contributing 🤝
</h1>

If you have any suggestions or improvements for this script, feel free to open an issue or submit a pull request.

You can donate to me on [ko-fi](https://ko-fi.com/moraroy), [liberapay](https://liberapay.com/moraroy), or [sponsor me on github](https://github.com/sponsors/moraroy) or [patreon](https://patreon.com/moraroy)

## Development Environment

### Dev Container

Install [Docker](https://docs.docker.com/compose/install/). Once installed, a clean dev environment with a Docker container [native to VSCode](https://code.visualstudio.com/docs/devcontainers/create-dev-container#_dockerfile) is spun up automatically. 

* [Command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) (⇧⌘P) > Dev Containers: Reopen in Container
* F5 for debug
    * May need to select interpreter (e.g., `/opt/venv/bin/python`) first

**VSCode Extensions (Dev Container)**

* [Atom Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)
* [Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode)
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
* [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
* [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
* [MS Visual Studio Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Shellcheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)

### Manual Docker Instance

If VSCode isn't present or only the python portion (cf. `__init__.py`) is being worked on, it's possible to just run a Docker container on its own. The container installs the correct version of python and any dependencies (e.g., ipython, rich) in `requirements.txt`.

```bash
# navigate to directory with Dockerfile
cd .devcontainer/

# build image
docker build -t nonsteamlaunchers .

# run container
docker run -it --rm --name=mynonsteamlaunchers --workdir=/app -v $(pwd):/app nonsteamlaunchers bash

# exit container
exit
```

### Python virtual environment

Useful for the python module(s), but extra compared to the [dev container](#dev-container) portion that covers the core shell script.

```bash
# create virtual environment
python -m venv .venv

# activate virtual environment
source .venv/bin/activate

# install dependencies
python -m pip install -r requirements.txt 
```

### Pre-commit hooks

Pre-commit hooks are installed via `pre-commit` and are run automatically on `git commit`. 

Most importantly, `ruff` is used to lint all python code.

* Install [pre-commit](https://pre-commit.com/#install)
* Install pre-commit hooks
    ```bash
    pre-commit install
    ```
* Trigger pre-commit hooks automatically on `git commit`
    ```bash
    git add .
    git commit -m "commit message"
    ```
* Bypass pre-commit hooks
  * Sometimes, it's necessary to bypass pre-commit hooks. This can be done with the `--no-verify` flag.
    ```bash
    git commit -m "commit message" --no-verify
    ```

### Conventional Commits

While not currently enforced, by using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary), it's possible to automatically generate changelogs and version numbers via [release-please](https://github.com/googleapis/release-please).

To help with that, the [commitizen](https://commitizen-tools.github.io/commitizen/) tool can be installed. 

To reduce some of the non-essential tooling, it's been removed from the repo, but feel free to install globally without checking into source control.

### Formatting

> **TL;DR**: The [Ruff formatter](https://astral.sh/blog/the-ruff-formatter) is an extremely fast Python formatter, written in Rust. It’s over 30x faster than Black and 100x faster than YAPF, formatting large-scale Python projects in milliseconds — all while achieving >99.9% Black compatibility.

* While it runs automatically on commits, it can also be run manually
    ```bash
    # check for errors
    ruff check .

    # fix (some) errors automatically
    ruff check . --fix
    ```

### Additional tooling

<!-- TODO: swap with mise -->
#### asdf

* Install [asdf](https://asdf-vm.com/guide/getting-started.html#_2-download-asdf)
* Add plugins
    ```bash
    asdf plugin-add python
    asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
    ```
* Usage
  * Install local plugins in repo
    ```bash
    asdf install
    ```
  * Install specific plugins
    ```bash
    # install stable python
    asdf install python <latest|3.11.4>

    # set stable to system python
    asdf global python latest
    ```

#### uv

[uv](https://docs.astral.sh/uv/) is a faster drop-in replacement for `poetry` among other dependency and virtual environment managers written in rust.

Common operations after [installing](https://docs.astral.sh/uv/getting-started/installation/):

```bash
# create venv w/pinned python version
uv venv --python ">=3.11,<3.13"

# activate venv
source .venv/bin/activate

# add deps
uv add redis
uv add --optional dev ruff

# install optional (extra) deps
uv pip install -r pyproject.toml --all-extras

# pip freeze
uv pip freeze > requirements.txt
```

#### Ruff

[Ruff](https://docs.astral.sh/ruff/) is a linter and formatter compatible with various other tools like black, flake8, isort, etc. Like [uv](#uv), it's by Astral and written in rust.

Install is handled by `uv`. These are a few of my favorite things 🎵:

```bash
# run linter
ruff check .

# formatter
ruff format .

# run tests
ruff

# run tests with coverage
ruff --coverage

# run tests with coverage and open in browser
ruff --coverage --open
```

#### shellcheck

`.shellcheckrc` excludes various [bash language rules](https://github.com/koalaman/shellcheck/wiki/Ignore#ignoring-one-or-more-types-of-errors-forever). Useful to control noise vs. legitimate warnings/errors when using the shellcheck extension.

<h1 align="center">
License 📝
</h1>

This project is licensed under the MIT License. See the `LICENSE` file for more information.
