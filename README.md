# Customize Mac terminal (iTerm2, oh-my-zsh)

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
# zshrc에 homebrew path 추가
$ echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc
# zshrc 반영
$ source ~/.zshrc
```

## Install iTerm2

```bash
brew install iterm2
```

## Install oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Customize oh-my-zsh

<https://github.com/wookingwoo/terminal-customization/blob/main/.zshrc>

```bash
open ~/.zshrc
```

ZSH_THEME=”agnoster” 로 변경

## Install D2Coding fonts

<https://github.com/wookingwoo/terminal-customization/tree/main/font/D2Coding-Ver1.3.2-20180524>

### Change font in iTerm2

iTerm2 > Preferences > Profiles > Text > Font > D2Coding

### Change font in terminal

terminal > preferences > profiles > text > font > D2Coding

## Change color theme

### Download color theme

<https://github.com/wookingwoo/terminal-customization/tree/main/mbadolato-iTerm2-Color-Schemes>

<https://iterm2colorschemes.com/>

### Change color theme in iTerm2

iTerm2 > Preferences > Profiles > Colors > Color Presets > Import > [color theme file]

I recommend [Atom theme](https://github.com/wookingwoo/terminal-customization/blob/main/mbadolato-iTerm2-Color-Schemes/schemes/Atom.itermcolors)
