# skewme
### Automated clock skew sync. No more annoying ntpdate or faketime commands.
<img src="https://github.com/user-attachments/assets/252b8455-e144-4b32-9129-9c902bc54041" alt="skewme" width="200"/>    

# Description
This was developed to solve the issue while using WSL with ntpdate commands always being automatically reverted to the UTC / Local time. The tool 𝘀𝗸𝗲𝘄𝗺𝗲 essentially runs a command as a process in the background and refreshes the clock every 2 seconds to maintain the time sync with the NTP server. It helps the user to not always require using commands to fix clock skew as it's done automatically in the background.

# Install
```
sudo wget https://github.com/DaddyBigFish/skewme/raw/refs/heads/main/skewme -O /usr/local/bin/skewme
sudo chmod +x /usr/local/bin/skewme
```
# Usage
```
sudo skewme xx.xx.xx.xx
```
