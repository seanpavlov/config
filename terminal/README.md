# TERMINAL
My basic terminal config

## 1. Download iTerm 2
Here: https://iterm2.com/

## 2. Install Oh My Zsh
Follow the instruction here: https://github.com/ohmyzsh/ohmyzsh

## 3. Modify the `.zshrc` config
1. Change theme to: `ZSH_THEME="agnoster"`
2. Change case sensitivity to: `CASE_SENSITIVE="false"`
3. Change hyphen insensitivity to: `HYPHEN_INSENSITIVE="true"`
4. Change history date format to: `HIST_STAMPS="yyyy-mm-dd"`
5. Remove git plugin: `plugins=()`

## 4. Install Hack Nerd Font Mono
Check: https://www.nerdfonts.com/

Run: 
```
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
```

## 5. Install Starship prompt
Check: https://starship.rs/

Run: `brew install starship`

Go to ``~/.zshrc` and add `eval "$(starship init zsh)"`

## 6. Change iTerm 2 Preferences
1. Under `Profiles > Text`, check `Use built-in Powerline glyphs`
2. Under ``Profiles > Text`, change font to `Hack Nerd Font Mono`
3. Create new profiles for each context (private, work etc)
