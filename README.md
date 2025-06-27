# skewme
### Automated sync. No more annoying ntpdate or faketime commands.

![2 (1)](https://github.com/user-attachments/assets/e6cfda9c-2061-421a-a343-0c8d2f137866)

# Description
This was developed to solve the issue while using WSL with ntpdate commands always being automatically reverted to the UTC / Local time. The tool 𝘀𝗸𝗲𝘄𝗺𝗲 essentially runs a command as a process in the background and refreshes the clock every 2 seconds to maintain the time sync. It helps the user to not always require using commands to fix clock skew as it's done automatically in the background.

# Install
```
wget https://github.com/DaddyBigFish/skewme/raw/refs/heads/main/skewme -O /usr/local/bin/skewme
sudo chmod +x /usr/local/bin/skewme
```
# Usage
```
sudo skewme xx.xx.xx.xx
```
