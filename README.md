# terminalCV

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/go-semantic-release/semantic-release)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)
![GitHub Tag](https://img.shields.io/github/v/tag/coolapso/hugo-theme-terminalcv?logo=semver&label=semver&labelColor=gray&color=green)
![terminalCV](https://raw.githubusercontent.com/coolapso/hugo-theme-terminalcv/master/images/screenshot.png)

# General Information

An easy to setup and (almost) fully hackable command line style CV theme with blogging capabilities

Live example at: <https://coolapso.sh>

# Features

* Blogging:
  * Toggle support, don't want blog features? just disable them!
  * Support for images
  * Supoort for [hugo shortcodes](https://gohugo.io/content-management/shortcodes/) (not fully tested, but should work!)
* Custom Greeting
  * Multi line text is respected
* Customizable prompt
  * Custom before & after prompt text
  * Custom before & after prompt colors
  * Custom prompt text
  * Custom prompt text Color
  * custom separator text
  * custom separator color
  * custom before & after symbols text
  * custom before & after symbols colors
  * Custom symbols
  * Custom symbols color
  * Custom extra text
  * Custom extra text color
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
  * **version:** Shows the website version
    * Disabled by default
    * only enabled if provided a version parameter
* Less, print commands output with less
  * Global, all commands use less instead of standard output
  * Per command, only defined commands use less as output method
  * `less <command>`, will output using less instead of standard output
* Command auto completion
* progression bars can be interrupted by pressing `ctrl+d`
* Favicons
* Bootsequence:
  * Option for a custom bootsequence to mimic the boot process of the terminal
  * If the parameter is not set, the bootsequence is skipped.
# How to start

This theme is far more simplistic than most themes therefore running `hugo new site` creates a lot of things that are not necessary.

```
mkdir -p myterminalcv/themes
cd myterminalcv
git clone https://github.com/coolapso/hugo-theme-terminalcv themes/terminalcv
cp themes/terminalcv/exampleSite/config.yml .
hugo server
```

Now you can start personalizing it by changing the config.yml and when you are happy just build the site with `hugo`

## Recommended way

If you are using git (which you should be!) for your website and don't want to make any radical changes to the theme itself, it's recommended that you add the theme as a submodule. This way, you can easily get new updates when they are available.

``` bash
git submodule add https://github.com/coolapso/hugo-theme-terminalcv.git themes/terminalcv
```

# How to configure

All the content and configuration is done through the [config.yml](config.yml).

you can just copy the existing example file and change it to your liking.

# Faviconss

[RealFaviconGenerator](https://realfavicongenerator.net/) and put the generated files into the static your folder

# Blog posts

blog post functionalities are enabled/disabled with the `blog` key in the params section

```yaml
params:
  blog: true
```

The theme supports blog posts, site visitors can find the posts with the `posts` or `ls` commands, and can view posts with `cat <filename>` to see how it works you can read the [example post](/exampleSite/content/posts/examplepost/index.md). 



![terminalCV](https://raw.githubusercontent.com/coolapso/hugo-theme-terminalcv/main/images/blogdemo.gif)


The live demo may not be making use of the blogging capabilities, but you can always see it in action like this:

> [!IMPORTANT]  
> Be sure to have hugo installed before proceeding

```
git clone https://github.com/coolapso/hugo-theme-terminalcv
cd hugo-theme-terminalcv
make server
```

Now a demo will be available at http://localhost:1313

# Contributions

Improvements and suggestions are always welcome, feel free to open an Issue or Pull Request

If you like this theme and want to support / contribute in a different way you can always:

<a href="https://www.buymeacoffee.com/coolapso" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" />
</a>

# Development

If you just want to make any changes and be able to test them as you progress, or if you simply just want to test the module wihtou having to create a new hugo website you can just run

```
git clone https://github.com/coolapso/hugo-theme-terminalcv
cd hugo-theme-terminalcv
make server
```

if you don't have make, then you can just run:

```
hugo server --config exampleSite/config.yml --theme ""
```

# jcubic/Jquery.Terminal

terminalCV makes use [jcubic/jquery.terminal](https://github.com/jcubic/jquery.terminal)

# Using this theme?

Let me know and feel free to open a Pull Request and add it to this list:

|link                 | Description       |
|---------------------|-------------------|
|<https://coolapso.sh>  | Simple CV         |
