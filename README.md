Navigate to the Sublime Text user preferences folder.
Here it is for macOS:

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```
For other platforms, use the menu option in Sublime Text -> Preferences -> Browse Packages... to find it.

Then run the following Git commands to initialize a repo and set it to the latest version of this repo:
```
git init
git remote add origin https://github.com/hkdobrev/sublime-preferences
git remote update
git reset --hard origin/HEAD
```
