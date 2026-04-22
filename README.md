# Grub theme

Just some random theme I came up with to have Priestess watching over your me

## Installation

Assumes grub2 and you have another theme present

```sh
sudo cp -rf Arknights_Priestess/ /boot/grub2/themes/
sudo sed -i 's/^.*GRUB_THEME=.*/GRUB_THEME="\/boot\/grub2\/themes\/Arknights_Priestess\/theme.txt"/g' /etc/default/grub
sudo grub2-mkconfig -o /boot/grub2/grub.cfg
```

## Default config

New machine installation just copy: [/etc/default/grub/](./grub)

## Example

![Example](./example.jpg)
