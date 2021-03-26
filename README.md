# week11
step 1)
sudo cp wttr.service wttr.timer /etc/systemd/system

step 2)
sudo systemctl daemon-reload

step 3)
sudo systemctl enable --now wttr.timer

