# kali-linux-commands

> this is just notes for me

## brigtness

```bash 
 xrandr --output eDP-1 --brightness 0.40

#@eDP-1: monitor we want to change its brightness
#range between 0, 1

#to see monitors we have
 xrandr --listmonitors
```

## bluetooth

```bash
sudo systemctl start bluetooth.service 

service bluetooth restart

bluetoothctl

#pair with device useing (pair -mac-address-)
#connect using (connect -mac-address-)
```

