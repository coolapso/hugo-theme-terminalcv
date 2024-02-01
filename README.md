# terminalCV
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)


![terminalCV](images/screenshot.png)


# General Information 

An easy to setup and (almost) fully customizable command line style CV theme

Live example at: https://cv.4s3ti.net

# Features

* Custom Greeting
  * Multi line text is respected
* Customizable prompt
  * Custom prompt text
  * Custom prompt text Color
  * Custom symbols
  * Custom symbols color
* Multiple sections with individual commands: 
  * **Whois:** General information about the individual
  * **social:** shows social networks
    * Any social network is supported, even the ones that don't exist! just provide a name and a URL
    * The social network name can be hidden and show only the URL
  * **work:** shows work experience information
    * Title can have custom color
  * **education:** shows education information
    * Title can have custom color
  * **sklls:** Shows skills information
    * Skill name can have custom color
  * **softskills:** shows softskills information
    * Skill name can have custom color
  * **languages:** Shows languages skills information
    * Language name can have custom color
  * **projects:** Shows projects information
    * Project title can have custom color
  * **misc:** Free text
    * misc command can be overriden and given another name
    * Title can have custom color
    * Content can have custom color
* Extra commands:
  * **startx:** Shows "loading..." progress bar and redirects to another website
    * Disabled by default
    * only enabled if provided a location to send to
  * **exit:** Shows "terminating..." progress bar and redirects to another website
    * Disabled by default
    * only enabled if provided a location to send to
  * **source:** Shows the glider and the theme github repo URL
    * Enabled by default
    * Can be disabled
* Command auto completion
* progression bars can be interrupted by pressing `ctrl+d` 
* Favicons 

# How to start

You can download the theme manually by going to [https://github.com/4s3ti/terminalcv.git](https://github.com/4s3ti/terminalcv.git) and pasting it to `themes/terminalcv` in your root directory.

You can also clone it directly to your Hugo folder:

``` bash
$ git clone https://github.com/4s3ti/terminalcv.git themes/terminalcv
```

If you don't want to make any radical changes, it's the best option, because you can get new updates when they are available. To do so, include it as a git submodule:

``` bash
$ git submodule add https://github.com/4s3ti/terminalcv.git themes/terminalcv
```
# How to configure

All the content and configuration is done through the [config.yml](config.yml). 

you can just copy the existing example file and change it to your liking. 

## Faviconss

[RealFaviconGenerator](https://realfavicongenerator.net/) and put the generated files into the static your folder

# Contributions

Improvements and suggestions are always welcome, feel free to open an Issue or Pull Request

If you like this theme and want to support / contribute in a different way you can always: 

<a href="https://www.buymeacoffee.com/4s3ti" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" />
</a>

# jcubic/Jquery.Terminal

terminalCV makes use [jcubic/jquery.terminal](https://github.com/jcubic/jquery.terminal)

# Using this theme? 

Let me know and feel free to open a Pull Request and add it to this list:

|link                 | Description       |
|---------------------|-------------------|
|https://cv.4s3ti.net | Simple CV         |
|https://pauldavidjarvis.com | Personal Website & Academic Resume |

