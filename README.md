# Frosit Php

Homebrew tap to install php 8.1.21 with ICU 73.2 to ommit Magento 2 issue where ICU 74 causes issues so ICU 73 is used: 
https://github.com/magento/magento2/issues/38214

## How do I install these formulae?

`brew install frosit/php/php@8.1.21 -s`

Or `brew tap frosit/php-icu-73` and then `brew install frosit/php/php@8.1.21`.

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
tap "frosit/php"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
