**Clear Bash History**

systemd-resolve --statistics

sudo systemd-resolve --flush-caches

screenfetch

bleachbit

sudo bleachbit

startxfce4

cat /dev/null > ~/.bash_history && history -c && exit

sudo pacman -Syu

sudo pacman -Syy

sudo pacman -Syyu

**Install Tor Browser**

sudo pacman -S torbrowser-launcher

torbrowser-launcher

**Install Microsoft Edge Browser** 

sudo pacman -S --needed git && git clone [https://aur.archlinux.org/microsoft-edge-stable-bin.git](https://aur.archlinux.org/microsoft-edge-stable-bin.git) && cd microsoft-edge-stable-bin && makepkg -si

**Arch Linux- Split Window**

[https://i3wm.org/](https://i3wm.org/)

--
su
sudo pacman -Sc && sudo pacman -Scc
sudo pacman -Syu && sudo pacman -Syy && sudo pacman -Syyu
screenfetch
bleachbit
sudo bleachbit
sudo systemd-resolve --statistics
sudo systemd-resolve --flush-caches
sudo /opt/lampp/xampp start
sudo /opt/lampp/xampp restart
sudo /opt/lampp/xampp stop
cd /usr/local/MATLAB/R2024b/bin/
./matlab
jupyter lab
jupyter notebook
reboot
shutdown now
udisksctl mount -b /dev/nvme0n1p4  # Academic
udisksctl mount -b /dev/nvme0n1p6  # Personal
udisksctl mount -b /dev/nvme0n1p5  # Public
exit
startxfce4


**Hugo** 

hugo server
hugo server -D

**Jekyll**

git clone [url]
bundle install
bundle exec jekyll serve

**Obsidian-Git**

cd "/home/akpk/Documents/Obsidian Vault/"
git init
git add .
git commit -m "Initial commit: Adding Obsidian vault"
git remote add origin https://github.com/akpk-in/Obsidian.git
git push -u origin main
-
git add .
git commit -m "Your message describing the changes"
git push
ssh-add ~/.ssh/github_akpk
ssh -i ~/.ssh/github_akpk git@github.com
-

jupyter lab
jupyter notebook
udisksctl mount -b /dev/nvme0n1p4  # Academic
udisksctl mount -b /dev/nvme0n1p6  # Personal
udisksctl mount -b /dev/nvme0n1p5  # Public

-
source venv/bin/activate

