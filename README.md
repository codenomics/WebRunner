# WebRunner

Turn any website into its own app window, like Chrome's "Install" but for every browser you use. WebRunner keeps all your web apps in one list, so you can see what you have, add new ones, change them and remove them.

### Features

- Opens a website in its own window, with no tabs and no address bar
- Works with the browsers installed on your PC: Chrome, Edge, Helium, Brave, Vivaldi and more, and Firefox. Pick the browser for each app.
- Finds the site's name and icon for you, or use your own picture
- Uses the browser's normal profile, or gives an app its own separate profile
- Optional private window for each app
- Adds a Start menu shortcut (and a desktop one if you want)
- One list to open, edit, copy the address of, or remove every app
- Open any app's website in a different browser from the right-click menu

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.0** (Oct 16, 2026)

- [WebRunner_v1.0_no-install.zip](https://github.com/codenomics/WebRunner/releases/download/v1.0/WebRunner_v1.0_no-install.zip) - 74 KB
- [WebRunner_v1.0_Setup.exe](https://github.com/codenomics/WebRunner/releases/download/v1.0/WebRunner_v1.0_Setup.exe) - 137 KB
- [WebRunner_v1.0_source.zip](https://github.com/codenomics/WebRunner/releases/download/v1.0/WebRunner_v1.0_source.zip) - 64 KB

What's new in v1.0:

- First release
- Turn any website into its own app window, with a shortcut in the Start menu or on the desktop
- One list to add, edit, open and remove all your web apps
- Pick the browser for each app, including Chrome-type browsers and Firefox
- Normal browser profile or a separate profile for each app, with an optional private window
- Finds the site's name and icon, or use your own picture

Older versions are on the [Releases page](https://github.com/codenomics/WebRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find WebRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 (version 1809 or newer) or Windows 11,
  64-bit.
  To remove it later: Windows Settings > Apps > WebRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the WebRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click WebRunner.exe. Nothing is installed; to remove it, delete
  the folder.

EITHER WAY
  Optional: pin it to Start (right-click it in the Start menu or on the
  desktop -> Pin to Start).
  WebRunner needs at least one web browser on your PC.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
To add a web app:
  1. Click Add app.
  2. Type the website's address (like youtube.com) and press Enter or click
     Look up. WebRunner fills in the name and finds the site's icon.
  3. Pick the browser. "Other browser..." lets you pick a program yourself.
  4. Pick the profile:
       Normal profile  - the browser's usual profile, so your sign-ins and
                         extensions are there.
       Its own profile - a separate, empty profile just for this app.
  5. Tick "Open in a private window" if you want that.
  6. Click Add app. A shortcut appears in your Start menu (and on the desktop
     if you ticked that).

The list: double-click or press Enter to open an app, F2 to edit it, Delete to
remove it. Right-click for more: open the website in another browser, copy the
address, edit, remove.


GOOD TO KNOW
------------
- Extensions: with the normal profile, your extensions work inside the app
  window. The app window has no toolbar, so you won't see the extension
  buttons.
- Its own profile starts with no extensions and no sign-ins. Click "Set up
  profile..." in the Add/Edit window to open that profile in a normal browser
  window, install your extensions and sign in, then close it.
- Staying signed in: with its own profile, closing the app window closes the
  whole browser, so sites that only keep you signed in while the browser is
  running will ask you to sign in again. Use the normal profile, or turn on
  "Continue where you left off" in that browser's startup settings.
- Private windows never keep sign-ins, and browsers turn extensions off in
  them until you allow each one there.
- Firefox can't open plain app windows. WebRunner gives each Firefox app its
  own profile with the tabs and toolbar hidden. It works, but it is rougher
  than the Chrome-type browsers.
- The browser's own window menu (the three dots, top right, in Chrome-type
  browsers) usually has Copy URL and an option to open the page in the normal
  browser.
- Removing an app deletes its shortcuts, and its own profile folder if it had
  one.
- Your list and settings are kept in %APPDATA%\WebRunner. A log is written
  next to the program (WebRunner-log.txt).
- WebRunner can check GitHub for a newer version at startup (Updates button
  in the bottom bar).
```

