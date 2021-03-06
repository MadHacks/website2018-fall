# website2019
Website for MadHacks 2019

## TODO

### General Fixes
* Add prize information to the FAQ
* Move inline styles outline
* View->The Team window (hidden for now)
* ~~Scale down desktop icons, reupload (so browser isn't downloading them at full size then rescaling client side)~~
* Send Edge users to mobile
* ~~Scroll bars interfere with close button~~
* ~~Sponsors page gets jumpy occasionally~~
* ~~Reformat FAQ~~
* ~~Fix title bar on Apply window~~
* ~~Favicon doesn't work on some browsers~~ (Still weird on Brave, fix this when we check browser compatibility)
* ~~Add title bar icons to far right: bluetooth, volume, wifi, battery, flux~~
* ~~Fix sponsor formatting~~
* ~~About -- have about open to the bottom right~~
* ~~Sponsor window left pane toggles, should do something clever-er~~
* ~~Fix about page bug where dragging before doing anything else keeps it stuck to the bottom~~
* ~~Fun cursors~~

### Mobile
* ~~Everything~~

### Window manager framework
* ~~Fix bug where you can move windows off the screen (Moss)~~
* ~~Add desktop icons behaviour (Moss)~~
* ~~Add title bar (Stamper)~~
* ~~Fix currently-dragging window z-index issue (Moss)~~
* ~~Fix weird bug where window title gets dragged off screen, but everything else stays put (Moss)~~
* ~~Decide whether we want the weird floating title bug, or the ability to drag over the nav bar?~~ (the former, a fix would be nice though)
* ~~Assign starting positions and active/hidden status to each window~~
* ~~"About" is acting weird -- why? (Moss)~~
* ~~Clicking close button doesn't always work -- why? (Moss)~~
* ~~Allow for windows to edge off screen to allow for smaller screen sizes~~
* ~~Force window back to original position when icon is re-double clicked~~

### Content
* ~~Add rest of the windows, barebones content (Stamper)~~
* ~~change history links when past websites are hosted, otherwise remove them~~

### style
* ~~Theme the css according to the style guide (Stamper)~~
* ~~Find body font (Stamper)~~
* ~~Find appropriate desktop icons (Stamper)~~
* ~~Padding on frames, esp. Map (Stamper)~~
* ~~Maps -- remove text (Stamper)~~
* ~~Maps -- update marker (Stamper)~~

## Using SASS
Installation:
```
npm install -g sass
```

Usage:
```
sass style.scss style.css
```

Watch directory for updates (and autocompile):
```
sass --watch style.scss:style.css
```