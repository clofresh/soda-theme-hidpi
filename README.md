# Soda Theme HiDPI

Dark UI theme for Sublime Text 2.
Edited to force HiDPI on Windows environnement, for a convenient theme on HiDPI screens (such as Apple MBP or latest ASUS Zenbooks)

Original project site: [http://buymeasoda.github.com/soda-theme/](http://buymeasoda.github.com/soda-theme/)

## Design

After :
![Soda Dark HiDPI Theme](http://i.imgur.com/UfzCu.png)

Before :
![Soda Dark Theme (legacy)](http://i.imgur.com/bc7jp.png)

## Installation

Soda theme HiDPI is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2.

### Using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

You can locate your Sublime Text 2 `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone git://github.com/Antwan86/soda-theme-hidpi.git "Theme - Soda HiDPI"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Soda HiDPI`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activating the theme

To configure Sublime Text 2 to use the theme:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Soda Dark HiDPI.sublime-theme"`

### Example User Settings

    {
        "theme": "Soda Dark HiDPI.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Soda Theme ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "soda_classic_tabs": true

![Soda Tab Styles](http://buymeasoda.github.com/soda-theme/images/features/multiple-tab-styles.png)

## Bonus Options

### Syntax Highlighting Colour Schemes

The Soda Dark screenshot uses a modified version of Monokai.

If you'd like to use the syntax highlighting schemes shown in the screenshots: 

* Download [colour-schemes.zip](http://buymeasoda.github.com/soda-theme/extras/colour-schemes.zip)
* Unzip and place the extracted `tmtheme` files in the Sublime Text 2 `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

### Screenshot details

The code font shown in the screenshot is Menlo, font used in UI is Ubuntu. Windows Aero theme has been modified by IumKit.

## Known Issues

* The tab font is truncated : This seems to be due to a [ST2 bug](http://www.sublimetext.com/forum/viewtopic.php?f=3&t=8889). I chose to leave it this way instead of reducing the font size because this is more readable anyway.
* Quickpanel font keeps small : This seems to be a [ST2 bug too](http://www.sublimetext.com/forum/viewtopic.php?f=2&t=4852)

## License

This is a derivative work from Soda Theme by Ian Hill (http://buymeasoda.com/). Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.