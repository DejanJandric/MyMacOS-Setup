# My MacOS Setup
## _Some of these apps are also compatibles with other OS_

[![N|Solid](https://macos-defaults.com/media-2x1.jpg)](https://macos-defaults.com/)



My name is `Dejan` and for the last year I've been using `MacOS` for work related stuff and occasionaly browsing and coding. These applications will be separated into three main categories.

- **Necessary applications (Must have)**
- **QoL improvement application (Apps that improve Life on MacOs)**
- **Rarely used applications (Occasionally used)**

## Necessary apps (MUST HAVE)

- [Alfred] - Best Spotlight replacement and way easier to use and navigate through the system.
- [Latest] - Kind of replacement for App Store on MacOs, but its better, faster and so much simpler.
- [MacMouseFix] - Smooth and easy, improve using external mouse, similar would be [BetterMouse].
- [CleanShotX] - Best screenshoot tool, but its a paid option, free alternative would be [Shottr].
- [QuickSilver] - Best launcher and so so much more.
- [PDF Expert] - The ultimate PDF editor.

## QoL Improvement applications (Apps that improve Life on MacOs)
- [MacGPT] - ChatGPT on your Mac and Menubar (free and paid options)
- [FreeOffice] - Best Microsoft Office alternative for MacOS and its FREE
- [ProNotes] - Supercharge for Apple Notes
- [Onyx] - System maintenance for MacOS 
- [OnlySwitch] - Provides a series toggle switch to simply your routine work, such as Hiden desktop icons, dark mode and hide ugly notch of new Mackbook Pro. The switches show on your statusbar, you can easily control them.
- [Zen] - Best browser in the market for the MacOs, easy to import data from another browser.
- [Notion] - Best productivity and all-around tool for everyday use.
- [Phiewer] - MacOS image viewer (Free and paid options available).


## Rarely used applications (Occasionally used)
- [DaVinciResolve] - Video editor, free and paid options available.
- [Discord] - Voice and video chat for gamers.
- [GrammarlyAI] - Writing assistant, better with paid option.
- [CleanMyMacX] - Cleaning and removing all unnecessary stuff from your machine.
- [Noir] - Dark mode for Safari browser (PAID only).
- [Google Drive] - Online cloud backup solution.
- [Telegram] - Social media application.
- [LocalSend] - Excellent free app for sending files and folders from one machine to another (cross platform as well).
- [Clockify] - Free MacOS time tracker for projects.
- [MSVisualStudioCode] - Free Microsoft coding tool for projects and development. 

## MacOS Tweaks and Settings

Here are some tweaks and settings that I like to change prior to setting up a new MacBook.

- Remove mouse scroll/tracking acceleration. 
`System Settings` -> Set `Tracking speed` to MAX.
`System Settings` -> Set `Scroll speed` to MAX.
- Keyboard fixes for better typing and productivity.
Fix slow initial key repeat (great for arrow keys) `defaults write -g InitialKeyRepeat -int 10`
Fix slow key repeat (also great for arrow keys) `defaults write -g KeyRepeat -int 1`
- Windows fixes for MacOS
Drag a window by pressing `Control ⌃` `Commmand ⌘ `+ click anywhere in the window
`defaults write -g NSWindowShouldDragOnGesture -bool true`
Make file proxy immediately appear
`defaults write NSGlobalDomain "NSToolbarTitleViewRolloverDelay" -float "0"`
Don't automatically switch spaces when clicking on the dock.
`defaults write com.apple.dock workspaces-auto-swoosh -bool NO`
`System Settings` → `Mission Control `→ Untick `When switching to an application, switch to a Space with open windows for the application`.
- Bluetooth , Download and install [Bluesnooze], automatically switch off Bluetooth when macOS goes to sleep. This prevents it from connecting to e.g. Bluetooth headphones in its sleep, which can prevent your phone from connecting
- Finder little tweaks 
Always display the current path at the bottom `Finder` → `Settings `→ `Show Path bar`
or `defaults write com.apple.finder ShowPathbar -bool true`
Show file extensions ` Finder` → `Settings… `→ `Advanced `→ `Show all filename extensions`
Show useful folders in the sidebar `Finder `→ `Settings… `→ `Sidebar` → `tick <home folder>`.
Don't keep open previously previewed files `defaults write com.apple.Preview ApplePersistenceIgnoreState YES`





## License
MIT License

Copyright (c) 2025 Dejan Jandric

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



   [Alfred]: <https://www.alfredapp.com/>
   [Latest]: <https://max.codes/latest/>
   [MacMouseFix]: <https://macmousefix.com/>
   [BetterMouse]: <https://better-mouse.com//>
   [CleanShotX]: <https://cleanshot.com/>
   [Shottr]: <https://shottr.cc/>
   [QuickSilver]: <https://qsapp.com/>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [PDF Expert]: <https://pdfexpert.com/>
   [MacGPT]: <https://www.macgpt.com/>
   [FreeOffice]: <https://www.freeoffice.com/en/download/applications>
   [ProNotes]: <https://www.pronotes.app/>
   [Onyx]: <https://www.titanium-software.fr/en/onyx.html>
   [OnlySwitch]: <https://onlyswitch.macupdate.com/>
   [Zen]: <https://zen-browser.app/>
   [Notion]: <https://www.notion.so/>
   [Phiewer]: <https://phiewer.com/>
   [DaVinciResolve]: <https://www.blackmagicdesign.com/event/davinciresolvedownload>
   [Discord]: <https://discord.com/download>
   [GrammarlyAI]: <https://www.grammarly.com/desktop/mac>
   [CleanMyMacX]: <https://macpaw.com/cleanmymac>
   [Noir]: <https://apps.apple.com/us/app/noir-dark-mode-for-safari/id1592917505?mt=12>
   [Google Drive]: <https://workspace.google.com/products/drive/>
   [Telegram]: <https://macos.telegram.org/>
   [LocalSend]: <https://localsend.org/>
   [Clockify]: <https://clockify.me/mac-time-tracking>
   [MSVisualStudioCode]: <https://visualstudio.microsoft.com/>
   [Bluesnooze]: <https://github.com/odlp/bluesnooze>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
