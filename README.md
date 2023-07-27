
<img src="https://github.com/pouyakary/DayAndNight/assets/2157285/1a5dc8e1-531d-42df-9156-5fbff8228314" width="310">

A simple macOS application that sits on your dock and toggles the system appearance when you click it.

![toggle apperance](https://github.com/pouyakary/DayAndNight/assets/2157285/bfd85356-b968-49cc-b5fb-80c23d036f03)





📦 [Download Here](https://github.com/pouyakary/toggle-apperance/releases/download/v1/Day.Night.zip)

<br><br>

> __Not Open Source Per Say__
> 
> The distribution binary is not an open source software in itself, since I had to sign it and didn't want others to be able to change what I had signed. However the app is only 5 lines of code so if you don't trust the binary, you can copy paste these fives lines into the Script Editor.app software and export it to an Application:
>
> ```applescript
> tell application "System Events"
>   tell appearance preferences
>	    set dark mode to not dark mode
>	  end tell
> end tell
> ```
