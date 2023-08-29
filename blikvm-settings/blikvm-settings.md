# BliKVM Settings

## Enable Oled Display

[Link to official docs](https://wiki.blicube.com/blikvm/en/OLED-display/)

```bash
rw
systemctl enable --now kvmd-oled //Enable OLED
ro
```

## Fix problem with cursor on ipkvm ARM

Delete all monitors, except PIKVM
