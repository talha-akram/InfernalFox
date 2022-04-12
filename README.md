# InfernalFox (formerly Foximate)

A minimal take on creating the ultimate Firefox css

## Key Features
1. space efficient - one bar layout works well with treestyle tabs
2. well commented few changes made to css, easy to maintain and easy to extend
3. coloured menu button to differentiate private windows

## Preview

### Foximate: normal window
![Foximate Preview: normal window ](/images/Foximate-normal.png?raw=true "Foximate Preview: normal window")

### Foximate: normal window with treestyle tabs
![Foximate Preview: normal window with treestyle tabs](/images/Foximate-normal-treestyle.png?raw=true "Foximate Preview: normal window with treestyle tabs")

### Foximate: private window
![Foximate Preview: private window](/images/Foximate-private.png?raw=true "Foximate Preview: private window")

### Foximate: private window with treestyle tabs
![Foximate Preview: private window with treestyle tabs](/images/Foximate-private-treestyle.png?raw=true "Foximate Preview: private window with treestyle tabs")

## Installation

1. Go to `about:profiles` and click `Show in Finder` button next to `Root Directory`.
2. Create a folder `chrome` if it does not already exist.
3. Copy the ![userChrome.css](/userChrome.css "link to Foximate css code") file to this (chrome) directory.
4. Set `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config` to `true`.
5. Restart Firefox for changes to take effect.

## Contributing
Found a bug or something is broken?
Have a suggestion or feature you want added?
Please open an issue.

Want to contribute? Awesome! please make a pull request.
