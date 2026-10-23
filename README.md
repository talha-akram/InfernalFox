# InfernalFox

A minimal take on creating the ultimate Firefox css

## Key Features
1. space efficient - one bar layout works well with [tree style tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
2. few and well commented changes made to css, easy to maintain and easy to extend
3. coloured menu button to differentiate private windows

## Preview

### InfernalFox: normal window
<img width="1293" height="742" alt="InfernalFox Preview: normal window" src="https://github.com/user-attachments/assets/fc3a743f-7db0-4d8e-9d50-5c3d5d0dd62f" />

### InfernalFox: normal window with treestyle tabs
<img width="1292" height="740" alt="InfernalFox Preview: normal window with treestyle tabs" src="https://github.com/user-attachments/assets/9aba7c1c-31f5-41b4-bb91-1504478c0741" />

### InfernalFox: private window
<img width="1293" height="741" alt="InfernalFox Preview: private window" src="https://github.com/user-attachments/assets/d8e85184-f797-4008-ab71-b529c23125a0" />

### InfernalFox: private window with treestyle tabs
<img width="1293" height="742" alt="InfernalFox Preview: private window with treestyle tabs" src="https://github.com/user-attachments/assets/3ff305f0-0a64-49a2-acd6-3541b7ecb193" />

## Installation

1. Go to `about:profiles` and click `Show in Finder` button next to `Root Directory`.
2. Create a folder `chrome` if it does not already exist.
3. Copy the ![userChrome.css](/userChrome.css "link to InfernalFox css code") file to this (chrome) directory.
4. Set `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config` to `true`.
5. Restart Firefox for changes to take effect.

## How to hide the sidebar?
1. Right click on the sidebar
2. Click "Customize sidebar"
3. Uncheck "open open tools from sidebar"
4. Click the "X" next to the sidebar to close customization.
5. Reopen "Tree Style Tab" using shortcut `Option + A` or through extension button in the address bar.

<img width="344" height="423" alt="Image" src="https://github.com/user-attachments/assets/ddb69d90-6750-47ec-a8ef-40251d4192d4" />

## Contributing
Found a bug or something is broken?
Have a suggestion or feature you want added?
Please open an issue.

Want to contribute? Awesome! please make a pull request.
