# pi_video_looper
Application to turn your Raspberry Pi into a dedicated looping video playback device, good for art installations, information displays, or just playing cat videos all day.

1. Start with installing Raspian Jessie James using Etcher to flash the micro SD card.
2. Copy the `wpa_supplicant.conf` to `/Volumes/boot/`
3. Run `touch /Volumes/boot/ssh`
4. Insert the newly flashed SD card into the pi
5. SSH into the pi with `ssh pi@whatevertheipis`
6. Run a `sudo raspi-config`
7. Change the hostname of the pi to match whatever number is on the case
8. Make it so that the network is connected before raspian boots
9. Run an update `sudo apt-get update`
10. Install git, `sudo apt-get install -y git`
11. Clone this repo `git clone https://github.com/gh0st/pi_video_looper.git`
12. Cd into the newly downloaded repo `cd pi_video_looper`
13. Run the install `sudo ./install.sh`
