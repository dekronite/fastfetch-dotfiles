# Simple-fastfetch-dotfiles
![GitHub Repo stars](https://img.shields.io/github/stars/dekronite/fastfetch-dotfiles?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/dekronite/fastfetch-dotfiles?style=social)
![GitHub forks](https://img.shields.io/github/forks/dekronite/fastfetch-dotfiles?style=social)


![Fastfetch Preview](preview.png)

## How to use

Ensure git is installed, then paste this into your terminal:

```bash
git clone https://github.com/dekronite/fastfetch-dotfiles ~/fastfetch-config && \
mkdir -p ~/.config/fastfetch && \
cp ~/fastfetch-config/config.jsonc ~/.config/fastfetch/config.jsonc && \
cp ~/fastfetch-config/image.png ~/.config/fastfetch/image.png
```
Notes;
  To change image edit
  ```
  "logo": {
    "type": "kitty-direct",
    "source": "~/.config/fastfetch/image.png",
    "width": 17,
    "height": 10
},
```
You may need to play with width and height to make your image fit


__NOTE: FASTFETCH NEEDS A WIDTH TO CHANGE IMAGE SIZE.__
__using height alone wont make the image size change__
