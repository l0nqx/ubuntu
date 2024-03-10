## Ubuntu on Termux Android


**Feature's**
- [x] Fixed Sound
- [x] Access to Sdcard
- [x] Fixed Browser Crash

Visit problems now in : [Issues](https://github.com/l0nqx/ubuntu/issues)

## Installation

Copy and paste this command to Termux :
> pkg update ; pkg upgrade

<details></br>
<summary><b><code>Install Ubuntu</code></b></summary>

* Ubuntu 24.04 (Noble Numbat)
```
pkg install wget -y ; wget https://raw.githubusercontent.com/l0nqx/ubuntu/main/Install/ubuntu24.04.sh ; chmod +x ubuntu24.04.sh ; ./ubuntu24.04.sh
```

* Ubuntu 23.10 (Mantic Minotaur)
```
pkg install wget -y ; wget https://raw.githubusercontent.com/l0nqx/ubuntu/main/Install/ubuntu23.10.sh ; chmod +x ubuntu23.10.sh ; ./ubuntu23.10.sh
```

</details>

---
* Start Ubuntu
```
ubuntu
```

* Stop Ubuntu
```
exit
```

* Remove Ubuntu
```
rm -rf ubuntu-fs
```

---
## Desktop Environment

on Ubuntu, run this command :
> apt update ; apt upgrade

<details></br>
<summary><b><code>Install Desktop Xfce</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/wahasa/Ubuntu/main/Images/xfce.jpg"</p>

```
apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Ubuntu/main/Desktop/de-xfce.sh ; chmod +x de-xfce.sh ; ./de-xfce.sh
```
</details>

<details></br>
<summary><b><code>Install Desktop Lxde</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/wahasa/Ubuntu/main/Images/lxde.jpg"</p>

```
apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Ubuntu/main/Desktop/de-lxde.sh ; chmod +x de-lxde.sh ; ./de-lxde.sh
```
</details>

<details></br>
<summary><b><code>Install Desktop Lxqt</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/wahasa/Ubuntu/main/Images/lxqt.jpg"</p>

```
apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Ubuntu/main/Desktop/de-lxqt.sh ; chmod +x de-lxqt.sh ; ./de-lxqt.sh
```
</details>

<details></br>
<summary><b><code>Install Desktop Kde</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/wahasa/Ubuntu/main/Images/kde.jpg"</p>

```
apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Ubuntu/main/Desktop/de-kde.sh ; chmod +x de-kde.sh ; ./de-kde.sh
```
</details>

---
## VNC Viewer

* Start VNC Server

on Ubuntu, run this command to start :
```
vnc-start
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Ubuntu Desktop
```

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on Ubuntu, run this command to stop :
```
vnc-stop
```
</br>
