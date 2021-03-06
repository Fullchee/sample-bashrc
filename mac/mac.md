# Reference Sheet on using mac more effectively (and less frustratingly)

### Moving between macs

- use time machine

## Finder
- `cmd k` Remote Connect to a server
- `Cmd shift a` `cmd [` jump around and Refresh Finder
- `cmd-shift-n`: create a new folder
- `cmd-L` Create a new alias
- `cmd-shift-g`: Goto file (autocompleted)
- `cmd-shift-.` toggle hidden files
- `alt cmd space` to open up finder

### Finder Tips
- View -> Show Path Bar

#### Finder Search file type
Type `kind:doc` to only select .doc types

### Screenshot
- cmd-shift-4: screenshot in a timestamped new image on the desktop
- cmd-ctrl-shift-4: store screenshot in clipboard
- with MonoSpace: `cmd alt 5`

## Chrome
### Chrome Disable autocomplete in omnibox
alt-shift backspace

### Swap the ctrl and fn buttons
Install Karabiner-Elements to switch them.

### Quickly resize windows
- Free: use `Spectacle` and you can set your own keyboard shortcuts.

#### Open folders with an app in Finder (eg iTerm, VSC)
1. Find the applescripts and create apps for them (won't be posted here, applescript & apps will update)
2. Hold cmd and drag and drop the app onto the area beside the search bar

#### Create a "Copy Path" service for Finder (Credit to OSX Daily: http://osxdaily.com/2013/06/19/copy-file-folder-path-mac-os-x/)
1. Launch Automator and create a new “Service”
2. Use the search function to look for “Copy to Clipboard” and drag that into the rightside panel of the Service
3. Set ‘Service recieves selected’ to “files or folders” and ‘in’ to “Finder” as shown in the screen shot below
4. Save the Service with a name like “Copy Path”

### Keyboard Settings
- **Use tab to navigate any menu**: System Preferences -> Keyboard -> Shortcuts (tab) -> All Controls (bottom of menu)
- **Disable ctrl up/down/left/right** (in Mission Control)
  - these shortcuts can just be activated with the touchpad gesture, you need the mouse anyway to quickly switch
  - can also now use these shortcuts on for text editors and other programs, especially via Remote Desktop connection to Windows
- **disable the make new sticky note**
- disable the global ctrl-1 and ctrl-2 (System Preferences -> Keyboard -> Shortcuts -> Mission Control)
  - the sublime shortcuts can be used (switch between panels)

### iTerm
- alt -> and <- to move a word at a time (Linux uses the super/meta key)
  1. Preferences (cmd ,) -> Profiles -> Keys -> Left Option as Escape
  2. Change the Alt -> and Alt <- to "Send Escape Sequence" (esc+b and esc+f)
- shortcut to toggle iTerm: Preferences -> Keys tab -> Hotkey section
- cmd-g: find next search result (instead of pressing enter), can also do cmd-shift-g to search forward in time
- http://teohm.com/blog/working-effectively-with-iterm2/
- cmd /: show where the cursor is

### [App not being found by Spotlight?](https://apple.stackexchange.com/questions/236741/single-application-not-showing-up-in-spotlight)
- add and remove whatever is not being found in Spotlight's list of directories it won't scan

### Spotlight: Open the item's containing folder
- cmd-enter
### Word: Change the Default/Normal Layout
1. Select some text with your desired font & spacing 
2. Cmd-d (opens Font) window
3. Click the Advanced tab near the top
4. Click `Default ...` on the bottom left

### Word: Don't show start screen
1. Open Preferences (cmd ,)
2. Click the `General` button
3. Untick `Show Word Document Gallery`

### Calendar won't sync
Preferences -> Internet Accounts -> Untick and tick calendar

### Reset SMC (System Management Controller, hardware settings)
1. Turn off laptop
2. Keep Power cable plugged in
3. Hold Shift+Control+Option+Power

### Force Quit a program
- cmd-alt-escape, then force quit the program you'd like
- otherwise, to kill the process, `ps aux | grep <process name>` and then kill it, like Linux

### Only copy/paste the formatting (useful in Notes, Google Drive, not Word, especially for strikethrough)
cmd-alt-c and cmd-alt-v

### Change default app for file extension
1. Right click a file with that extension to "Get Info"
2. Near the bottom, in "Open with", change the app and press "Change All..."

### Hide apps (Finder, iTunes, Mail) from the cmd-tab menu
https://apple.stackexchange.com/questions/92004/is-there-a-way-to-hide-certain-apps-from-the-cmdtab-menu

### Chrome: avoid cmd q:
- Menu bar -> Chrome -> Warn before Qutting

### Login Items
- Chrome
- iTerm
- Todoist
- BarTunes
- Pomello
- Spectacle
- Tomighty
- Backup and Sync (Google Drive)

### Convert .mov to .mp4
`mov2mp4 <path to .mov file>`

### Modify the icon of a program
1. Create an `.icns` file (convert online or something)
2. Click on your `Application.app` and press `Cmd I`
3. Drag your `.icns` file to the top left corner where the old icon until you see a green plus sign

### Resize Finder column so it fits the text
- double click on the two bars at the bottom of the column
  - like Excel, no need to manually drag it out
