# headless mac

```bash
system_profiler SPPowerDataType

sudo pmset -a sleep 0
sudo pmset -a disksleep 0 displaysleep 0
sudo pmset -a hibernatemode 0
sudo pmset -a autorestart 1

sudo pmset -a powernap 0
sudo pmset -a tcpkeepalive 0
sudo pmset -a womp 0
pmset -g


curl -s https://raw.githubusercontent.com/actuallymentor/battery/main/setup.sh | bash
```

brew
```
neofetch
brew install --cask stats
brew install --cask aldente
```