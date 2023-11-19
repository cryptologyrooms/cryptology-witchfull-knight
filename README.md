# Witchfull Knight

## Notes
https://www.npmjs.com/package/nodemon
https://www.npmjs.com/package/commander

```
sudo apt-get update
sudo apt-get install build-essential software-properties-common vim git curl apt-transport-https lsb-release ca-certificates dirmngr unzip
sudo apt-get install avahi-daemon avahi-discover avahi-utils libnss-mdns
curl -fsSL https://deb.nodesource.com/setup_20.x | bash -

sudo npm install typescript rimraf node-gyp -g 
sudo npm install ts-node -g
```

https://pinout.xyz/pinout/pi_digiamp
was IQAduIO is now owned by foundation
https://www.raspberrypi.com/documentation/accessories/audio.html


`dtoverlay=iqaudio-digiampplus,unmute_amp`  
`#dtparam=audio=on`

used pins

2   i2c
3   i2c
18  i2s
22  mute/unmute
23  ? rotray
24  ? rotray
25  ? IR Sendor
19  i2s
20  i2s
21  i2s


