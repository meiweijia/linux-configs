# archlinux install config

## 1.1 archinstall
使用 ```archinstall``` 命令安装，`type` 选 `xorg`。

## 1.2 最小化安装KDE
```bash
sudo pacman -S sddm sddm-kcm plasma-desktop plasma-nm plasma-pa kdeplasma-addons kde-gtk-config konsole kscreen dolphin dolphin-plugins ark noto-fonts noto-fonts-emoji
```
## 1.3 常用软件
```bash 
 sudo pacman -S vim git docker docker-compose autojump zsh
```

## 1.4 archlinuxcn key 无法安装
```
sudo pacman-key --lsign-key "farseerfc@archlinux.org"
```

## 1.5 vscode 全局菜单
```bash
sudo pacman -S libdbusmenu-glib
```

# 主题
## global theme
`Qogir`

## icon
`Papirus`
