# Xresources

ZhuZhiHao,2017-09-10

Using Xterm , My Xresources configure

### Clone project
```shell
git clone https://github.com/Ihexon/Xresources ~/
```

### Install Fonts
```shell
mkdir -p  ~/.local/share/fonts
cp ~/Xresources/fonts/*  ~/.local/share/fonts
```

### Load the Xresources
```shell
cp  ~/Xresources/Xresources ~/.Xresources
xrdb -load ~/.Xresources
```
