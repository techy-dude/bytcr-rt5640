# To see full instruction , go to https://techy-dudes.blogspot.com/2020/05/in-this-tutorial-im-going-to-show-you.html
byctr-rt5640

### Prerequisites
-Git

### Installing(choose one)

**using terminal (RECOMMENDED)**

apt install git

git clone https://github.com/techy-dude/bytcr-rt5640-sound-card.git

sudo cp -rf ~/bytcr-rt5640-sound-card/bytcr-rt5640 /usr/share/alsa/ucm

sudo cp -rf ~/bytcr-rt5640-sound-card/asound.state /var/lib/alsa

sudo alsa force-reload

**manual**

1.copy 'bytcr-5640' folder to usr/share/alsa/ucm

2.copy 'asound.state' to var/lib/alsa (replace the original one)


## Authors

**MR.Pilbossart**  - [plbossart](https://github.com/plbossart)


## Acknowledgments

* This is NOT my work(refer to author)
* I merged things needed to make it work 

## Sources


* https://github.com/plbossart/UCM/tree/master/byt-rt5640
* https://forums.linuxmint.com/viewtopic.php?t=307559
