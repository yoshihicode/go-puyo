
# Go-Puyo
Go-Puyo is terminal based 'Puyo Puyo' similar game written in Go language.

![gopuyo](gopuyo.gif)

[![Release](https://img.shields.io/github/v/release/yoshihicode/go-puyo)](https://github.com/yoshihicode/go-puyo/releases/latest)
![Go Version](https://img.shields.io/github/go-mod/go-version/yoshihicode/go-puyo)
![License](https://img.shields.io/github/license/yoshihicode/go-puyo)

## What is puyo puyo?
https://en.wikipedia.org/wiki/Puyo_Puyo

## 💾 Download
👉 [Get the latest binaries](https://github.com/yoshihicode/go-puyo/releases/latest)


## 🚀 Quick start
### 🐧 Linux
```bash
wget https://github.com/yoshihicode/go-puyo/releases/latest/download/go-puyo_linux_amd64.tar.gz
tar -xzvf go-puyo_linux_amd64.tar.gz
sudo mv go-puyo /usr/local/bin/
go-puyo
```
### 🍎🍺  macOS / Homebrew
```bash
brew tap yoshihicode/tap
brew install go-puyo
```
### 🪟 Windows
```powershell
Invoke-WebRequest -OutFile go-puyo_windows_amd64.tar.gz https://github.com/yoshihicode/go-puyo/releases/latest/download/go-puyo_windows_amd64.tar.gz
tar -xzvf go-puyo_windows_amd64.tar.gz
.\go-puyo.exe
```

## How to play
🕹️Key bindings<br>
[enter] - start game<br>
[esc] - exit<br>
[space] - drop<br>
[a/arrow left] - move left<br>
[d/arrow right] - move right<br>
[w/arrow up] - rotate left<br>
[s/arrow down] - rotate right<br>
[p] - pause/resume<br>

## 🛠️ Build from source

```bash
git clone https://github.com/yoshihicode/go-puyo.git
cd go-puyo
go build -o go-puyo
./go-puyo
```