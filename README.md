
<p align="center" style="margin-bottom:10px;margin-top:10px;"><a><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"></a></p>

<h2 align="center">
 <b style="font-size:24px;line-height:24px;vertical-align:middle;"><i>fastfetch dotfiles</i></b>
</h2>

<p align=center style="margin-top:36px">	  
  <img src="https://img.shields.io/github/stars/dekronite/fastfetch-dotfiles?color=dd864a&labelColor=202328&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/dekronite/fastfetch-dotfiles?color=82aaff&labelColor=202328&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/dekronite/fastfetch-dotfiles?color=bf616a&labelColor=202328&style=for-the-badge">
  <img src="https://img.shields.io/github/issues-pr/dekronite/fastfetch-dotfiles?color=c792ea&labelColor=202328&style=for-the-badge">
  <img src="https://img.shields.io/github/license/dekronite/fastfetch-dotfiles?color=15121C&labelColor=202328&style=for-the-badge">  
</p>


<p align="center">
  <img src="preview.png" alt="Fastfetch Preview">
</p>

<h2 align="center">How to use?</h2>

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
