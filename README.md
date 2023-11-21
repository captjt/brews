# brews
Random homebrew formulae that might not exist anymore 

## Drinking Old Beer

Sometimes you have to drink (install) old brews that might not be listed on Homebrew anymore. Here are some steps to install them.

```sh
brew tap captjt/brews git@github.com:captjt/brews.git
brew tap homebrew/core
brew extract --version=1.22 leveldb captjt/brews
brew install leveldb@1.22
```
