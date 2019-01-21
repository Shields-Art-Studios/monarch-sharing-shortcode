# Monarch Sharing Shortcode
This WordPress plugin provides a shortcode for adding inline Monarch sharing buttons above footer elements. This repo was originally forked from a repo created by [Matt Mirus](https://github.com/mmirus).

From our experience, Matt's plugin rendered the inline share buttons either at the top/bottom of the page as per Monarch's configuration. Unfortunately, this caused Monarch to render the buttons below our footer! This plugin differs from Matt's because it renders the share buttons inline wherever the shortcode is used. Instead of choosing the top or bottom, this plugin gives you the freedom to place Monarch share buttons wherever you want!

## Installation
To install the plugin:
  1. Click on the green `Clone or download` button located on this page.
  2. Click `Download Zip` and save the .ZIP archive to a temporary location on your computer.
  3. Login into your wp-admin dashboard and click `Plugins` and then `Add New`.
  4. Click `Upload`, then click `Browse...` and locate the .ZIP archive on your computer.
  5. Click `Install Now`.
  6. Lastly, click `Activate Plugin`.

## Usage
To add share buttons to a wordpress post/page:
  1. In the Divi Visual Builder, add a new code module.
  2. In the module's settings window, enter one of the following shortcodes into the `content` section:

*Sharing buttons with default URL (current page)*
```
[monarch_share]
```

*Centered sharing buttons*
```
[monarch_share center=true]
```

*Sharing buttons with custom URL*
```
[monarch_share url="custom url"]
```

*Sharing buttons with both*
```
[monarch_share center=true url="custom url"]
```
