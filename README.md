# InfernalFox (formerly Foximate)

A minimal take on creating the ultimate Firefox css

## Key Features
1. space efficient - one bar layout works well with [tree style tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
2. well commented few changes made to css, easy to maintain and easy to extend
3. coloured menu button to differentiate private windows

## Preview

### InfernalFox: normal window
![InfernalFox Preview: normal window ](/images/Foximate-normal.png?raw=true "InfernalFox Preview: normal window")

### InfernalFox: normal window with treestyle tabs
![InfernalFox Preview: normal window with treestyle tabs](/images/Foximate-normal-treestyle.png?raw=true "InfernalFox Preview: normal window with treestyle tabs")

### InfernalFox: private window
![InfernalFox Preview: private window](/images/Foximate-private.png?raw=true "Foximate Preview: private window")

### InfernalFox: private window with treestyle tabs
![InfernalFox Preview: private window with treestyle tabs](/images/Foximate-private-treestyle.png?raw=true "InfernalFox Preview: private window with treestyle tabs")

## Installation

1. Go to `about:profiles` and click `Show in Finder` button next to `Root Directory`.
2. Create a folder `chrome` if it does not already exist.
3. Copy the ![userChrome.css](/userChrome.css "link to InfernalFox css code") file to this (chrome) directory.
4. Set `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config` to `true`.
5. Restart Firefox for changes to take effect.

## Contributing
Found a bug or something is broken?
Have a suggestion or feature you want added?
Please open an issue.

Want to contribute? Awesome! please make a pull request.
