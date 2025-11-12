![Showcase](https://raw.githubusercontent.com/yesitsfebreeze/vsc-smearcursor/refs/heads/master/images/readme.gif)


## Requirements

This extensions makes use of [CustomCssJS](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css).  
Make sure its installed.

## Extension Settings

This extension contributes the following commands:

* `smearcursor.enable`: Enable/Update the cursor effect.
* `smearcursor.disable`: Disable the cursor effect.

This extension contributes the following settings:

* `smearcursor.animation_time`: Animation Time
* `smearcursor.animation_easing`: Animation Easing
* `smearcursor.max_length`: Max trail length
* `smearcursor.tip_shrink`: How much the cursor tip shrinks when moving
* `smearcursor.tail_shrink`: How much the cursor tail shrinks when moving
* `smearcursor.opacity`: How Transparent the cursor is when moving
* `smearcursor.disable_when_selecting`: Disable cursor when selecting text
* `smearcursor.blink_enabled`: If the cursor should blink or not
* `smearcursor.blink_easing`: Type of easing function used for the blink animation
* `smearcursor.blink_interval`:How fast the cursor blinks
* `smearcursor.blink_delay`: How long the cursor waits before starting to blink after moving

## Installing

After installing run:  
`SmearCursor: Enable/Update`  

If you have troubles getting the css to run, refer to:  
https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css  


Works best with: `editor.cursorStyle": "block"`

## Known Issues

--

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1
Initial release of SmearCursor

### 1.1.0
Fixes

### 1.1.2
Adding move opacity

### 1.1.3
Fixed null entry in settings

### 1.1.4
Fixed null entry in settings (again..)
Added easing options

### 1.1.5
Republish for README

### 1.1.6
Fix a woopsie doopsie

### 1.2.0
Removed opacity (buggy and not really nice to look at)
Added more sensible defaults
Only skew cursor when moving diagonally

### 1.2.1
added pull requests

### 1.3.0
Fixed blink speed calculation and added small delay
after moving before the blink starts
Added to readme and settings:
	smearcursor.disable_when_selecting
	smearcursor.blink_enabled
	smearcursor.blink_easing
	smearcursor.blink_interval
	smearcursor.blink_delay

