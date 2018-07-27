# pi_video_looper
Application to turn your Raspberry Pi into a dedicated looping video playback device, good for art installations, information displays, or just playing cat videos all day.

1. Start with installing Raspian Jessie James using Etcher to flash the micro SD card.
2. Copy the `wpa_supplicant.conf` to `/Volumes/boot/`
3. Run `touch /Volumes/boot/ssh`
4. Run an update `sudo apt-get update`
5. Install git, `sudo apt-get install -y git`
6. Clone this repo `git clone https://github.com/gh0st/pi_video_looper.git`
7. Cd into the newly downloaded repo `cd pi_video_looper`
8. Run the install `sudo ./install.sh`
9. 
