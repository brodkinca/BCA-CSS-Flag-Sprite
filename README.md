# BCA Flag Icon Kit

All the flags of the world in a single, easy-to-use sprite.

## Usage

### 1. Load the Stylesheet

Host it locally or load it from GitHub:

```html
<link rel="stylesheet" type="text/css" href="http://cloud.github.com/downloads/brodkinca/BCA-CSS-Flag-Sprite/css/flags.css"/>
```

Alternatively, download the project and import the file into your LESS stylesheets:

```css
@import 'flags/less/flags.less';
```

LESS users may find it necessary to override the path to the sprite images. The `@pathFlagImageDir` variable can be used to set that path.

### 2. Add a Flag

Users of Twitter's Bootstrap project will find the syntax to be very similar to their icon syntax.

```html
<i class="flag-us"></i>
```

For a complete list of country codes please see the official ISO [list of country names and codes](http://www.iso.org/iso/home/standards/country_codes/country_names_and_code_elements.htm).