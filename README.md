# clover-elcapitan-theme
A clover theme for [the Clover UEFI bootloader](http://sourceforge.net/projects/cloverefiboot), based off [YosemiteLogin2 by xenatt](https://github.com/xenatt/CloverTheme/tree/master/YosemiteLogin2).

![Screenshot of the theme](https://raw.githubusercontent.com/aarsla/clover-elcapitan-theme/master/screenshot.png)

## Installation
Clone or download the ZIP of this repo to your Clover theme directory (usually in /EFI/CLOVER/themes, located on the EFI system partition). Then, edit your Clover config.plist to select the theme.
```plist
<key>GUI</key>
<dict>
	<key>Theme</key>
	<string>clover-elcapitan-theme</string>
</dict>
```
Default resolution is 1920x1200, but you can change it to 1920x1080 by changing the `Background` Path key.
```plist
<key>Background</key>
<dict>
	<key>Path</key>
	<string>1920x1200.png</string>
 	<key>Type</key>
	<string>Crop</string>
	<key>Sharp</key>
	<string>0xFF</string>
</dict>
```

Special thanks to xenatt for his original theme.
