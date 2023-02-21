# animdl-tui (currently broken)

[![License](https://img.shields.io/github/license/h4rldev/animdl-tui?style=flat-square)](https://github.com/H4rldev/animdl-tui/blob/main/LICENSE)

A Terminal User Interface for [animdl](https://github.com/justfoolingaround/animdl)

(_heck, I had to fork a library and make it better for this_)

(__I WON'T ADD FUZZYFINDER FOR THIS BECAUSE TWIST.MOE IS RANCID__)

## News

The latest version of animdl-tui has been released
and will probably be the most stable release as of rn.

> How to run:

```shell
git clone https://github.com/H4rldev/animdl-tui
cd animdl-tui
main.py
```

> or:

Download from the [releases](https://github.com/h4rldev/animdl-tui/releases/latest)

Please report bugs in [issues](https://github.com/h4rldev/animdl-tui/issues)

## Todo

- Code Cleanup
- Less skill issues.
- Mal/Anilist Sync (If you're downloading only, use [taiga](https://taiga.moe/))
- Compatibility with other oses
- animdl rewrite in rust (the funny)

## Installation

1. Download from the [releases](https://github.com/h4rldev/animdl-tui/releases/latest)
2. Put the executable anywhere.
3. Execute the name of the executable in your terminal or make a shortcut.
4. Profit???

## Build/running latest

### From the command line

> Run in the cloned repository:

```shell
python main.py
```

> Build in the cloned repository:

```shell
pyinstaller --onefile --icon logo.ico main.py
```

### Directly

> Run in the cloned repository:

- Run the main.py file by double clicking it.

> Built in the cloned repository:

- Run the executable I've built or you've built by double clicking it.

## Requirements (building)

- Python 3.10
- Windows (as of right now)
- [animdl](https://github.com/justfoolingaround/animdl)
- [colored](https://pypi.org/project/colored/)
- [click](https://pypi.org/project/click/)
- [rebullet](https://pypi.org/project/rebullet) and dependencies.
- [pyinstaller](https://pyinstaller.org/en/stable/) (if you want to build from source)

## Requirements (running)

- Python 3.10 (probably)
- Windows (as of right now)
- [animdl](https://github.com/justfoolingaround/animdl)
- [mpv](https://mpv.io/)
- other deps i can't find out atm
