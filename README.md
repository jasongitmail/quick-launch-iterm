# Quick Launch iTerm

Adds a button to MacOS Finder to launch iTerm at the currently-selected directory. Saves time versus dragging the directory to iTerm's dock icon or right clicking and then finding in the menu.

## Installation

1. Download [Quick Launch iTerm.app.zip](https://github.com/jasongitmail/quick-launch-iterm/releases/download/v1.0/Quick.Launch.iTerm.app.zip), unzip it, & move into `~/Applications`.
2. In Finder, hold `option command` and drag this app from your Applications directory onto the top bar of Finder. It will add itself as an icon.

## Usage

When using Finder, click this icon to open the currently-selected directory in iTerm.

_Note: When using this the first time, MacOS will prompt you that the application cannot be verified. Visit System Preferences > Security & Privacy, and click "open anyway"._

## Building

If you prefer to build the app yourself:
1. Double click `Quick Launch iTerm.scpt` to open it in Apple's Script Editor.
2. In Script Editor, use File > Export > "as application" and save to `~/Applications`.
3. To add your desired icon, right click on `Quick Launch iTerm.app` that was just created and select "Show Package Contents". Replace `Contents/Resources/droplet.icns` with your desired icons file.
4. Lastly, follow installation instructions above.
