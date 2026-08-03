![Preview](/preview.png)

# fastfetch_opensuse
fastfetch config for opensuse with official colour, added images for opensuse, tumbleweed, slowroll and leap.
based on github.com/harilvfs script, credits to him/her

## installation

if you don't have fastfetch config file created, use
```
fastfetch --gen-config
```

then copy the files into the folder.

To change the image, rewrite the name of the file on the fourth line of config.jsonc "source" for "tumbleweed", "slowroll", "leap" or "geeko".
```
"source": "~/.config/fastfetch/image/opensuse.png"
```
## You need to have installed a nerd font for the little icons as:

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.0/Hack.zip

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.0/JetBrainsMono.zip
