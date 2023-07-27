# Toggle Appearance

![macOS Toggle Appearance app by Pouya Kary](https://github.com/pouyakary/toggle-apperance/assets/2157285/d0bcf782-e223-48d9-a9d2-96acac881ec4)

A simple application that toggles the appearance of macOS.

It is these 5 lines of code, packaged beautifully. Due to the problems with signing, I'm not open sourcing this one. You can get the app from the repo, or copy these lines in the Script Editor and create your own version:

```applescript
tell application "System Events"
	tell appearance preferences
		set dark mode to not dark mode
	end tell
end tell
```