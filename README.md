# Tehlug Hugo Theme

## Features

* Clean and minimal
* Responsive
* Supports tags
* Syntax highlighting
* Twitter cards and opengraph tags support
* Hugo RSS feeds
* Custom CSS/JS
* Show location in map
* Open lat,lng
* Show register link
* Make Gallery

## Installation

From your Hugo site run the following.

```sh
cd themes
git clone https://github.com/tehlug/Tehlug-Hugo-Theme
```

For more information read the [official setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Configuration

```toml
baseURL = "http://example.org/"
languageCode = "fa-ir"
title = "My personal blog"
theme = "Tehlug-Hugo-Theme"

copyright = "© Copyright notice"

# Enable syntax highlighting.
pygmentsstyle = "solarized-dark"
pygmentscodefences = true
pygmentscodefencesguesssyntax = true

# Number of posts to show in recent posts list (Optional). Defaults to 10.
paginate = 10

# Number of characters to show in summary.
summaryLength = 20

[params]
    # Blog subtitle which appears below blog title. Supports markdown.
    subtitle = "Clean and minimal personal [blog theme for Hugo](https://github.com/tehlug/Tehlug-Hugo-Theme)"

    # Content types which are included in home page recent posts list.
    mainSections = ["posts"]

    # Specify favicon (icons/i.png maps to static/icons/i.png). No favicon if not defined.
    favicon = "icons/myicon.png"

    # Switch to dark mode or auto detect mode from OS (Optional).
    # "dark" will set mode to dark and "auto" will switch to dark mode if OS is in dark mode.
    mode = "dark" # "dark" or "auto"

    # Custom CSS added to default styles. Files added to `static` folder is copied as it is to
    # root by Hugo. For example if you have custom CSS file under `static/css/custom.css` then
    # you can specify custom css path as `css/custom.css`.
    customCSS = "css/custom.css"
    # Custom CSS added to dark mode style.
    customDarkCSS = "css/custom-dark.css"

    # Custom list of Javascript files to load. Just like custom CSS you can place js files under
    # `static/js` folder and specify path here as `js/script-name.js`. You can also specify full url,
    # for example you may want to include external JS library.
    customJS = ["js/abc.js", "js/xyz.js", "https://code.jquery.com/jquery-3.4.1.js"]

# Enable tags.
[taxonomies]
   tag = "tags"
```