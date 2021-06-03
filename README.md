## Intro
A collection of info about the Tapo C200.<br>
Info that you don't find in the manaul or tplink site.
Basically hacks, mods & internal HW data.


## Contents
- Hardware specs
- Antenna extension mod
- Video stream without from VLC
- Access to serial terminal (COM port)
- Camera control from terminal (control without the app)
- Enable motion tracking for FREE
- Firmware mod (coming soon)
- Ethernet port addition (coming soon)


## Hardware


## Reference links
- [Similar CPU reverse engineering](https://dalpix.com/reverse-engineering-ip-camera-part-2)


---

## Little ramble on the "why" of this project

Lets face it, this little C200 cam is quite popular.The one I bought, even had a
best seller sticker on it. (the real reason I bought it)

<img src="https://github.com/sengiv/TapoC200/blob/master/images/best-seller.png">

I wouldn't say it is cheap, there are cheaper ones in Aliexpress. But it is definitely affordable.
At first boot, I must say I was impressed. Just seeing it move its head around was mesmerizing to watch.
To summarize it, I was more than satisfied with the hardware on this thing. Then came the software part
of the cam, disappointments started to creep in.

A few things quickly become obvious as you set this puppy up. (things not mentioned in the manual)
1. Camera management is ONLY via an app on your phone.
2. Camera becomes unpredictably unresponsive the further it is from the WiFi router.
   You need RSSI 60dBi (signal quality) at minimum for solid 1080p operation & responsive cam movements.
3. NO ETHERNET PORT & NO EXTERNAL ANTENA JACK! I know it's the 21st century and everything is "supposed to be" wireless,
   but nothing beats cable period! I saw forum posts by many having firmware update problems,
   and tplink's answer to them was to move camera closer to modem.
   
  ![](https://github.com/sengiv/TapoC200/blob/master/images/forum-post.png)
   
   Wait, what? Basically TpLink is saying that if you had 4 cams installed 20ft high around a 4000sqft
   warehouse and you want firmware update
   you are screwed! Cable would have solved this problem & the bad streaming quality.
   Had TpLink included a $0.35 cent antenna jack and half the problems would be solved!

After a few more weeks of use, I had enough. Either I'm going to fix this or break it trying.
It is not a bad camera but it can be better!