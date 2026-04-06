
# 🟢 Go-Puyo
Go-Puyo is a terminal-based Puyo Puyo–like game written in Go.

![gopuyo](gopuyo.gif)

[![Release](https://img.shields.io/github/v/release/yoshihicode/go-puyo)](https://github.com/yoshihicode/go-puyo/releases/latest)
![Go Version](https://img.shields.io/github/go-mod/go-version/yoshihicode/go-puyo)
![License](https://img.shields.io/github/license/yoshihicode/go-puyo)

## 🔴 About Puyo Puyo
Puyo Puyo is a popular tile-matching puzzle game series originally developed in Japan.  
[Learn more on Wikipedia](https://en.wikipedia.org/wiki/Puyo_Puyo)

## ⚙️ Features
- 🕹️ Terminal-based gameplay
- 💻 Cross-platform support (Linux, macOS, Windows)
- ⏰ A great way to kill time

## 💾 Download
Download prebuilt binaries from the latest release:  
👉 [Get the latest binaries](https://github.com/yoshihicode/go-puyo/releases/latest)


## 📦 Installation
### 🐧 Linux
```bash
wget https://github.com/yoshihicode/go-puyo/releases/latest/download/go-puyo_linux_amd64.tar.gz
tar -xzvf go-puyo_linux_amd64.tar.gz
sudo mv go-puyo /usr/local/bin/

# Run
go-puyo
```
### 🍎🍺  macOS / Homebrew
```bash
brew tap yoshihicode/tap
brew install go-puyo

# Run
go-puyo
```
### 🪟 Windows
```powershell
Invoke-WebRequest -OutFile go-puyo_windows_amd64.tar.gz https://github.com/yoshihicode/go-puyo/releases/latest/download/go-puyo_windows_amd64.tar.gz
tar -xzvf go-puyo_windows_amd64.tar.gz

# Run
.\go-puyo.exe
```

## 🎮 Controls
| Key | Action |
|-----|--------|
| Enter | Start game |
| Esc | Exit |
| Space | Drop |
| a / ← | Move left |
| d / → | Move right |
| w / ↑ | Rotate left |
| s / ↓ | Rotate right |
| p | Pause / Resume |

## 🛠️ Build from source

```bash
git clone https://github.com/yoshihicode/go-puyo.git
cd go-puyo
go build -o go-puyo
./go-puyo
```