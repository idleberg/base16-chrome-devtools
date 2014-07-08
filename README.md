# Base16 for Chrome Developer Tools

Chrome Developer Tools style sheets based on Chris Kempson's [Base16][1] colour scheme

*Note*: As of Chrome 33, these style sheets might no longer work. Since then, official support for themes (using different class names) has been introduced. However, it might have been [removed](https://codereview.chromium.org/66383005/) since then. Should be interested in updating the [Base16 template](https://github.com/chriskempson/base16-builder/tree/master/templates/chrome-devtools), this [Yeoman Generator](https://www.npmjs.org/package/generator-devtools-theme) might be a good starting point.

[this discussion](https://codereview.chromium.org/66383005/)).

![Base16: Chrome Developer Tools](https://raw.github.com/idleberg/base16-chrome-devtools/master/images/screenshot-chrome.png)

## Installation

### Mac OS X

1. Download any style sheet from the [`styles`][2] folder
2. Copy file to `~/Library/Application Support/Google/Chrome/Default/User StyleSheets`
3. Make sure to rename destination file to `Custom.css`

### Windows

1. Download any style sheet from the [`styles`][2] folder
2. Copy file to `%APPDATA%\Local\Google\Chrome\UserData\Default\User StyleSheets`
3. Make sure to rename destination file to `Custom.css`

### Linux

1. Download any style sheet from the [`styles`][2] folder
2. Copy file to `~/.config/google-chrome/Default/User StyleSheets`
3. Make sure to rename destination file to `Custom.css`

## Contributing

All pull requests should be made against [Base16 Builder][3], the tool used to compile these style sheets

## Credits

Original Base16 color scheme by [Chris Kempson][4], LESS based on a Gist by [Ben Truyman][5]

[1]: https://github.com/chriskempson/base16
[2]: https://github.com/idleberg/base16-chrome-devtools/tree/master/styles
[3]: https://github.com/chriskempson/base16-builder
[4]: https://github.com/chriskempson/
[5]: https://gist.github.com/3040634
