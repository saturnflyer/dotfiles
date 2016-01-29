# dotfiles

Clone this repository to your home directory.

It assumes you have homebrew installed (see http://brew.sh)

Install homebrew-bundle by running `brew tap Homebrew/bundle`

Be sure to create a file called `.gitconfig.custom` with your special git configuration.

For example, here's mine:

```
[user]
  name = 'Jim Gay'
  email = email@example.com
```

Then run `rake` from within this directory.

And finally run `brew bundle`

### credit

A good portion of the setup is stolen from https://github.com/peterkeen/dotfiles