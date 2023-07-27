<img src="https://github.com/pouyakary/toggle-apperance/assets/2157285/e064ae44-8fe4-4dee-8a08-7863be61a0e3" width="310">

![macOS Toggle Appearance app by Pouya Kary](https://github.com/pouyakary/toggle-apperance/assets/2157285/d0bcf782-e223-48d9-a9d2-96acac881ec4)

A simple application that toggles the appearance of macOS, so that you can change the Dark/Light look of the mac with only clicking an app on your dock.

📦 [Download Here](https://github.com/pouyakary/toggle-apperance/releases/download/v1/Day.Night.zip)


## Not Open Source Per Say

The distribution binary is not an open source software in itself, since I had to sign it and didn't want others to be able to change what I had signed. However the app is only 5 lines of code so if you don't trust the binary, you can copy paste these fives lines into the Script Editor.app software and export it to an Application:

```applescript
tell application "System Events"
	tell appearance preferences
		set dark mode to not dark mode
	end tell
end tell
```