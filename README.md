# Weather Print Service
## steps on how to make it work

1. Copy the script **wttr** to your prefer directory. `cp wttr 'location of directory where you want it to be saved'`

2. Copy the timer and service file to /etc/systemd/system. `sudo cp wttr.service wttr.timer /etc/systemd/system`

3. Restart all unit files. `sudo systemctl daemon-reload`

4. Make it run everytime on boot and make it start immediately. `sudo systemctl enable --now wttr.timer`

