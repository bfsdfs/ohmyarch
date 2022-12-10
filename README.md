# Oh My Arch
## 01.ZSH配置
* 插件管理: [ZIM](https://github.com/zimfw/zimfw)
* 主题美化: Powerlevel10k
```
yay zsh && chsh -s /usr/bin/zsh
sudo nvim /etc/zsh/zshenv
文件末尾添加: ZDOTDIR=$HOME/.config/zsh
```
## 02.FontConfig配置
* 无衬线:西文 Noto Sans 中文 Noto Sans CJK
* 衬线:西文 Noto Serif 中文 Noto Serif CJK
* 等宽:西文 Consolas 中文 Noto Sans Mono CJK
* Emoji: Twemoji
* 图标: Symbols Nerd Font
```
yay noto-fonts noto-fonts-cjk ttf-twemoji ttf-nerd-fonts-symbols consolas-font
```
