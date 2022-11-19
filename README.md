# Firefox-Micro

### The most minimal and decluttering Firefox experience possible. 

#### Made with as few lines of css in the userChrome stylesheet as possible, with a goal of staying futureproof.

- toggle to hide the entire navbar for zen mode
- works on a per window basis, perfect for reading code, watching videos or webapps.

![](https://github.com/Stianlyng/Firefox-Micro/blob/main/preview.png?raw=true)



# Demo
![](https://github.com/Stianlyng/Firefox-Micro/blob/main/demo.gif)

# Installation

### Allow for custom stylesheets:

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for, and enable:

    - toolkit.legacyUserProfileCustomizations.stylesheets

3. Go to your Firefox profile(Easier, go to: about:profile in urlbar, and click open root folder on the top of the page):
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Create a folder and name it **`chrome`** (with lowercase).

5. Then just copy the chrome folder inside your profile directory.

# Toggle the toolbars
**If you want to toggle the url/tab-bar download the plugin Userchrome Toggle by: [Joolee](https://github.com/Joolee)**
- https://github.com/Joolee/userchrome-toggle
  - Remember to have "prefix" empty, and then choose your preferred hotkey
- The bookmarks toolbar can be toggled with: Ctrl + Shift + B





# Shortcuts

🤖 Cool shortcuts you can use with this theme for a better experience

* Alt You can access to the global menu for an extended options you need
* Alt + Left Arrow You can go Back
* Alt + Right Arrow You can go Forward
* Ctrl + L focuses the URLBar, which is very useful for quick searches and bookmarks usage
* Ctrl + B shows you the Bookmarks
* Ctrl + H shows you the History Bar
* Ctrl + T Opens a new Tab
* Ctrl + W Closes a Tab
* Ctrl + Shift + T Re-opens a tab that you just closed
* Ctrl + R Refresh the page you're on
* Ctrl + Shift + A Quick open for Add-Ons
