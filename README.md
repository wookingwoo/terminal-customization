# Customize Mac terminal (iTerm2, oh-my-zsh)

## wookingwoo-zshrc

<https://github.com/wookingwoo/terminal-customization/blob/main/.zshrc>

## Set wookingwoo-iterm-profile

### Download profile

<https://github.com/wookingwoo/terminal-customization/blob/main/wookingwoo-iterm-profile.json>

### Set profile in iTerm2

iTerm2 > Preferences > Profiles > Other Actions > Import JSON Profiles > [wookingwoo-iterm-profile.json]

---

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

<https://github.com/naver/d2codingfont>

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

## Add status bar in iTerm2

- Add status bar: iTerm2 > Preferences > Profiles > Session > Status bar enabled
![statusbar_configure](./img/statusbar_configure.png)

- Change status bar position: Preferences > Appearance > Status bar location > Bottom
![statusbar_location](./img/statusbar_location.png)

## Install plugins for iTerm2

### zsh-autosuggestions

Install zsh-autosuggestions

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Open zshrc

```bash
open ~/.zshrc
```

Add zsh-autosuggestions plugin

```bash
plugins=( 
    # other plugins...
    zsh-autosuggestions
)
```

### zsh-syntax-highlighting

Install zsh-syntax-highlighting

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Open zshrc

```bash
open ~/.zshrc
```

Add zsh-syntax-highlighting plugin

```bash
plugins=( 
    # other plugins...
    zsh-syntax-highlighting
)
```

### Neofetch

Install neofetch

```bash
brew install neofetch
```

Open zshrc

```bash
code ~/.zshrc
```

Add neofetch

```bash
neofetch
```
