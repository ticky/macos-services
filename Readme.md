# OS X Services

A collection of useful Services for Mac OS X

## Installation

Clone or download a zip of the repository, then double-click each service, and Automator will prompt you to install.

## What's Included

### Converters

A set of text converters for some fun Unicode text effects. Each type includes a converter for both directions, and includes as many character substitutions as possible.

These include;

* Full-Width (Ｆｕｌｌ－Ｗｉｄｔｈ)
* Double-Struck (𝔻𝕠𝕦𝕓𝕝𝕖-𝕊𝕥𝕣𝕦𝕔𝕜)
* Fraktur (𝕱𝖗𝖆𝖐𝖙𝖚𝖗)

### De-retinize Picture

Useful for Retina Macs, this will magically turn your Retina-sized screenshots into normal-sized ones. This one requires Imagemagick to be installed, and includes its default installation path from Homebrew.

It moves the original image to (if your filename is "filename", ) "filename@2x" and the shrunk-down version is output as "filename@1x". It supports any image format Imagemagick can handle.

If the selected image is not 144dpi (as Retina screenshots are), it will do nothing.

### How long is this text?

Shows an alert telling you how many characters were in the selected text.

### Is that URL SFW?

Opens the isthatsfw preview of the highlighted URL.

### Send text to Pushover

Pushes the selected text to Pushover.

Requires configuring two passwords in Keychain Access;

1. Create a New Password Item (⌘N)
2. Set the Keychain Item Name to "Pushover User Token"
3. Set the Account Name to any value (tour Pushover account's email address is not a bad choice)
4. Set the Password to your User Key from [pushover.net](https://pushover.net)
5. Click "Add".
6. Repeat steps 1 through 5, instead setting the Item Name to "Pushover Service Token" and the password to an Application Token from [a new Pushover App](https://pushover.net/apps/build)

### Send URL to Instapaper

Sends a selected URL to Instapaper.

Requires configuring one password in Keychain Access;

1. Create a New Password Item (⌘N)
2. Set the Keychain Item Name to "Instapaper"
3. Set the Account Name to your Instapaper account's email address
4. Set the Password to your Instapaper account's password.
5. Click "Add".
