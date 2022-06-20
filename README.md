# Cryptomining with a Raspberry Pi - In Progress

This is a write-up of how I turned a Raspberry Pi 4 into a crypto miner.  
This is **not** profitable. Even if you bought thousands of Pi's, it would still not be profitable. I did this for fun, just to see if it would work. 

## Installation

### Step 1: Bake The Pi

The first step is to set up the firmware on the Raspberry Pi, also known as "baking" your pi. I used the image found in the zip file at this link: [2021-10-30-raspios-bullseye-arm64-lite.zip](http://downloads.raspberrypi.org/raspios_lite_arm64/images/raspios_lite_arm64-2021-11-08/). If you want to use a different image, power to you, but I have no idea if it'll change anything. Once the zip file is downloaded, extract it to anywhere on your computer. 

Next, download the [Raspberry Pi Imager](https://www.raspberrypi.com/software/) and install it. Once installed, open the program and you should see a screen similar to this:
REMEMBER TO INSERT AN IMAGE HERE

There will be 4 steps you need to do in order to set up your pi:
1. Click on the "CHOOSE OS" button and scroll to the bottom of the menu to get to "Use custom" and select it. A file explorer will open up and select the *.img* file you just extracted, which in my case was *2021-10-30-raspios-bullseye-arm64-lite.img*. 
2. Click on "CHOOSE STORAGE" (for me the button showed up as "CHOOSE ST..." and select a microSD card that you have plugged into your computer.
3. Hotkey **Crtl + Shift + X** to open up the advanced options menu. CURRENTLY WORKING ON HERE

Wireless Network Watcher: [Wireless Network Watcher v2.30](https://www.nirsoft.net/utils/wireless_network_watcher.html) 

Monero GUI Wallet: [Monero Downloads](https://www.getmonero.org/downloads/)


```bash
pip install foobar
```

## Usage

```bash
ssh pi@[IP]
```

## Acknowledgement
This is heavily based on [NetworkChuck's](https://www.youtube.com/c/NetworkChuck) video [Cryptocurrency Mining on a Raspberry Pi (it's fun....trust me)](https://www.youtube.com/watch?v=hHtGN_JzoP8). His channel is amazing and I've been following along with his stuff, and I highly recommend checking him out.
