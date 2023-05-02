
[<img src="https://raw.githubusercontent.com/dtcooper/raspotify/master/raspotify.svg?sanitize=true">](https://github.com/dtcooper/raspotify)

Raspotify is a [Debian package and associated repository](https://en.wikipedia.org/wiki/Deb_(file_format)) for [Debian Stable](https://www.debian.org/releases/stable/) ( ***Currently Debian 11 "Bullseye"*** ) and other Debian Stable based/compatible OS's ( ***your mileage may vary*** ) which thinly wraps [a fork](https://github.com/JasonLG1979/librespot/tree/raspotify) of the awesome [librespot](https://github.com/librespot-org/librespot) library by [Paul Lietar](https://github.com/plietar) and others up as a [systemd](https://en.wikipedia.org/wiki/Systemd) [daemon](https://en.wikipedia.org/wiki/Daemon_(computing)).

Raspotify is intended to be used in a *[headless enviroment](https://en.wikipedia.org/wiki/Headless_computer)*. For desktop OS's [spotifyd](https://github.com/Spotifyd/spotifyd) offers similar functionality and is a better choice. If you're looking for a turnkey audio solution for Raspberry Pi's with Spotify Connect support we recommend [moOde™ audio player](https://moodeaudio.org/).

**Librespot, and therefore Raspotify, requires a premium account.**

## Installation on KALi LiNUX

There are various *"guides"* floating around online. Most if not all of them are outdated and/or present incorrect information. **Don't follow them.**

```sh
sudo apt-get -y install curl && curl -sL https://dtcooper.github.io/raspotify/install.sh | sh
```
[RASpotify.pdf](https://github.com/sudo-self/raspotify/files/11361716/RASpotify.pdf)

Or you can just download the latest .deb package and install it manually from here:
* [`raspotify-latest_armhf.deb`](https://dtcooper.github.io/raspotify/raspotify-latest_armhf.deb)
* [`raspotify-latest_arm64.deb`](https://dtcooper.github.io/raspotify/raspotify-latest_arm64.deb)
* [`raspotify-latest_amd64.deb`](https://dtcooper.github.io/raspotify/raspotify-latest_amd64.deb)

### sudo apt install cargo
### cargo install librespot
### librespot -n "Crypto Kali pi" -b 160
![librespot](https://user-images.githubusercontent.com/119916323/235577850-24302437-5a1f-4435-b244-7badac4bf374.jpg)
![SPOTIPI](https://user-images.githubusercontent.com/119916323/235578346-c92b1d7c-ca15-4440-80a8-ca65c951a1ff.jpg)
![Spotify Open Source](https://user-images.githubusercontent.com/119916323/235578449-c4bb2067-21bc-4539-ba8e-3c6f138c07c6.jpg)


