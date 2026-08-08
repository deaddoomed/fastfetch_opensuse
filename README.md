![Preview](/preview.png)

# fastfetch_opensuse
fastfetch config for opensuse with official colour, added images for opensuse, tumbleweed, slowroll, microos and leap.
based on github.com/harilvfs script, credits to him/her

## installation

if you don't have fastfetch config file created, use
```
fastfetch --gen-config
```
then copy the files into the folder.

## You need to have installed a nerd font for the little icons as:

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.0/Hack.zip

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.0/JetBrainsMono.zip

## Logos

To change the image, edit the file name on the fourth line of config.jsonc using the logos available in image folder.
```
"source": "~/.config/fastfetch/image/opensuse.png"
```

Available logos:

<table align="center">
  <tr>
    <td align="center"><img src="image/opensuse.png" width="150" height="150" alt="opensuse"><br><sub>opensuse</sub></td>
    <td align="center"><img src="image/geeko.png" width="150" height="150" alt="geeko"><br><sub>geeko</sub></td>
    <td align="center"><img src="image/tumbleweed.png" width="150" height="150" alt="tumbleweed"><br><sub>tumbleweed</sub></td>
    <td align="center"><img src="image/leap.png" width="150" height="150" alt="leap"><br><sub>leap</sub></td>
    <td align="center"><img src="image/slowroll.png" width="150" height="150" alt="slowroll"><br><sub>slowroll</sub></td>
    <td align="center"><img src="image/micros.png" width="150" height="150" alt="micros"><br><sub>micros</sub></td>
  </tr>
</table>
