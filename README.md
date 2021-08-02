![Screenshot of the Theme](https://github.com/Parker06/Comfy/blob/main/Comfy.PNG)

## :warning: DISCLAIMER :warning:

* After the 1.1.59.714 Spotify update, spicetify does not work as it comes up with `error Cannot find symbol for Custom app React symbols` and will show a blank screen. [Reference of the issue.](https://github.com/khanhas/spicetify-cli/issues/845)

* [Latest Spotify Version Applicable for Spicetify](https://spotify.en.uptodown.com/windows/download/3712596)

# Comfy Discord Theme for Spotify:

## It uses Spicetify

## To install Spicetify:

* Press Windows Key and type Powershell, to open and run powershell as admin on windows, for others view [https://github.com/khanhas/spicetify-cli/wiki/Installation.](https://github.com/khanhas/spicetify-cli/wiki/Installation)

* Run this command: `Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression`.

* Run `spicetify --help` for list of commands.

* Type `spicetify` to create config-xqui file.

### Spotify will open automatically with the default theme so to change it.

* Copy the color.ini and user.css files into C:\Users\Your User Name\\.spicetify\Themes then create a new folder naming whatever you want.

## Then to update it:

* Type into the Powershell Window `spicetify current_theme <theme name> e.g. Comfy`.

* Then type to select a color scheme (Mine has one which is called `Comfy`). Type `spicetify config color_scheme Comfy`.

* As themes may have multiple colour schemes e.g.  light and dark mode. You will need to type in the corresponding colour scheme.

* Then go to the powershell again and type `spicetify apply`. And you should have a custom Spotify

## To update the same theme to newer version

* Open Powershell as an adminstrator then type `spicetify apply` to update the theme, Spotify should restart automatically to apply the changes.

[Source.](https://www.muo.com/tag/customize-spotify-with-spicetify-themes/)

[Youtube Guide (Credit to Julian Gonzalez for the video)](https://www.youtube.com/watch?v=PoSidNiRu-g)

[Community Themes by morpheusthewhite:](https://github.com/morpheusthewhite/spicetify-themes/tree/master)

## What to do if Spotify receives an update?

* Go into Windows Powershell and then run the command, `spicetify backup apply` to make a new backup point then once it created a backup then type `spicetify apply` to re-apply the custom css theme.
