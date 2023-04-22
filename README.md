# Garuda Linux Config

### 1. Update System

-  update all package: `sudo pacman -Syu`

#### pacman

-  install and update one apk: `sudo pacman -S [pkgname]`
-  delete: `sodo pacman -R [pkgname]` or `sodo pacman -Rs [pkgname]`
-  install to link store or local: `sudo pacman -U [link/pkgname.tar.zst]`

[More...](<[https://](https://funix.edu.vn/chia-se-kien-thuc/huong-dan-co-ban-ve-lenh-pacman-tren-arch-linux/)>)

### 2. yay

-  `git clone https://aur.archlinux.org/yay.git`
-  `cd yay`
-  `makepkg -si`
-  `yay --version`

### 3. snapd

-  `git clone https://aur.archlinux.org/snapd.git`
-  `cd snapd`
-  `makepkg -si`
-  start socket: `sudo systemctl enable --now snapd.socket`
-  connected store: `sudo ln -s /var/lib/snapd/snap /snap`

### 4. debtap

-  `git clone https://aur.archlinux.org/debtap.git`
-  `cd debtap`
-  `makepkg -si`

### 5. vscode

-  `git clone https://aur.archlinux.org/visual-studio-code-bin.git vscode`
-  `cd vscode`
-  `makepkg -si`

### 6. Nodejs

-  `sudo snap install node --classic`
