# macOS

Based on High Sierra.

## Commissioning

### Homebrew

After installing Homebrew, install the required apps using [homebrew-setup.sh](../scripts/homebrew-setup.sh).

### Texpad

For Mac App Store purchased Texpad, first rename the (newer) Homebrew version to `Texpad New.app`; then use `mas` to `search` and then `install` the (older) Mac App Store Texpad; then rename that version to `Texpad Old.app`. Now you can restore the original name of the newer one, and use it to consume the older one.

### Apache

Use the [Grav instructions](https://getgrav.org/blog/macos-sierra-apache-multiple-php-versions).

### Git

I like to set up `~/00blair/gitrepos` (or equivalent).

## Decommissioning

- Ensure all git repos are pushed to their `origin`
- Backup all mySQL databases
- Deauthorise iTunes (very important - cannot be done remotely more than once a year without calling Apple Support for a good half hour)