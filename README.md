# Toggle Controls Desktop Themelet

[![npm version](https://badge.fury.io/js/toggle-controls-desktop-themelet.svg)](https://badge.fury.io/js/toggle-controls-desktop-themelet)

A themelet enabling toogle controls for desktop for Liferay 7.2 (since Liferay 7.3 CE GA2 this is an [out-of-the-box feature](https://issues.liferay.com/browse/LPS-108216)).

![Toggle Controls](doc/toggle-controls.gif) 

## Install

Go to your theme's root folder and type:
```bash
gulp extend
```
Choose _Themelet_ :
```
? What kind of theme asset would you like to extend? 
  Base theme 
❯ Themelet 
```
Choose _Search npm registry_ :
```
? Where would you like to search for themelets? 
  Search globally installed npm modules (development purposes only) 
❯ Search npm registry (published modules) 
```
Search for _toggle-controls-desktop-themelet_ :
```
? Search npm for themelets: toggle-controls-desktop-themelet
```
> If you have an error, try `npm audit fix` and retry installation from the beginning 

Press space to select it :
```
? Select a themelet 
❯◉ toggle-controls-desktop-themelet
```
## License

[MIT](LICENSE)
