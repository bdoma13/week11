# How to make it work
step 1)
cp wttr 'location of directory where you want it to be saved'

step 2)
sudo cp wttr.service wttr.timer /etc/systemd/system

step 3)
sudo systemctl daemon-reload

step 4)
sudo systemctl enable --now wttr.timer

