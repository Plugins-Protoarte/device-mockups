# Device Mockups

Contributors: mrdink

Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9CZ54JHH93S2Y

Tags: portfolio, shortcode, device, mockup, iphone, responsive

Requires at least: 3.0.1

Tested up to: 4.0

Stable tag: 1.3.0

License: GPLv2 or later

License URI: http://www.gnu.org/licenses/gpl-2.0.html

> Simplify your mockups. Device Mockups generates shortcodes that display screenshots of your content in a responsive device.

## Description

Show your work in high resolution mockup shortcodes. Wrap your images or YouTube or Vimeo videos in different device wrappers. There's also a simple dropdown in the editor to help select what device you would like to use. The devices will respond to the container it's in and will look great on mobile.

### Attributes:
* color: black/white
* orientation: portrait/landscape
* stacked: open/closed
* position: left/right
* link
* width
* hide

### Recommended Image Sizes:
* iPhone 5 - 640×1136
* iPad - 2048×1536
* iMac - 1920x1200
* Macbook Pro (Retina) - 1440x900
* Galaxy S3 - 720x1280
* Nexus 7 - 1920x1200
* Surface - 1920 x 1080
* Lumia 920 - 768 x 1280

Note that these are only recommendations.

### Stacking:
For stacking the devices on top of each other, add `stacked="open"` to the first device and `stacked="closed"` to the last device. You'll also need to apply the position of the inner device with `position="left"` or `position="right"`.

### Example:
`[device type="macbook" stacked="open"]CONTENT[/device][device type="iphone5" position="right" stacked="closed"]CONTENT[/device]`

### Usage:
`[device type="iphone5"]
iPhone Content
[/device]`

`[device type="ipad"]
iPad Content
[/device]`

`[device type="imac"]
iMac Content
[/device]`

`[device type="macbook"]
Macbook Content
[/device]`

`[device type="s3"]
Galaxy S3 Content
[/device]`

`[device type="nexus7"]
Nexus 7 Content
[/device]`

`[device type="surface"]
Surface Content
[/device]`

`[device type="lumia920"]
Lumia 920 Content
[/device]`

Please help by reporting any bugs/feature request at the link below.

## Bugs:
* Report at: [Github Issue Tracker](https://github.com/mrdink/device-mockups/issues)

## Questions/Comments:
* http://byjust.in/contact/

## Credit:
* [Pixelsign](http://aarnis.com/)

## Installation:

1. Upload `/device-mockups/` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
