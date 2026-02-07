# Simple-fastfetch-dotfiles
![GitHub Repo stars](https://img.shields.io/github/stars/dekronite/Simple-fastfetch-dotfiles?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/dekronite/Simple-fastfetch-dotfiles?style=social)
![GitHub forks](https://img.shields.io/github/forks/dekronite/Simple-fastfetch-dotfiles?style=social)

Preview
![Fastfetch Preview](image.png)

## How to use

Ensure git is installed, then paste this into your terminal:

```bash
git clone https://github.com/dekronite/Simple-fastfetch-dotfiles ~/fastfetch-config && \
mkdir -p ~/.config/fastfetch && \
cp ~/fastfetch-config/config.jsonc ~/.config/fastfetch/config.jsonc && \
cp ~/fastfetch-config/image.png ~/.config/fastfetch/image.png
```
Notes;
  To change image edit
  ```
  "logo": {
    "type": "kitty-direct",
    "source": "~/.config/fastfetch/marin.png",
    "width": 17,
    "height": 10
},
```
You may need to play with width and height to make your image fit
