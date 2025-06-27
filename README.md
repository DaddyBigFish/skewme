# skewme
### Automated sync. No more annoying ntpdate or faketime commands.

![image-removebg-preview (4)](https://github.com/user-attachments/assets/3b251175-3d41-4d3c-81fb-d43e759309a1)

# Description
This was developed to solve the issue while using WSL with ntpdate commands always being automatically reverted to the UTC / Local time. The tool 𝘀𝗸𝗲𝘄𝗺𝗲 essentially runs a command as a process in the background and refreshes the clock every 2 seconds to maintain the time sync with the NTP server. It helps the user to not always require using commands to fix clock skew as it's done automatically in the background.

# Install
```
wget https://github.com/DaddyBigFish/skewme/raw/refs/heads/main/skewme -O /usr/local/bin/skewme
sudo chmod +x /usr/local/bin/skewme
```
# Usage
```
sudo skewme xx.xx.xx.xx
```
