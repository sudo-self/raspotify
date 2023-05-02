
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

### [Raspotify does NOT support ARMv6 Pi's (Pi v1 and Pi Zero v1.x)](https://github.com/dtcooper/raspotify/wiki/Raspotify-on-Pi-v1's-and-Pi-Zero-v1.x)
<img width="1440" alt="Screenshot 2023-04-30 at 10 12 03 AM" src="https://user-images.githubusercontent.com/119916323/235363954-03d72b7d-2d4c-42b3-9660-4b835af9b0ff.png"><img width="1440" alt="Screenshot 2023-05-01 at 10 02 56 PM" src="https://user-images.githubusercontent.com/119916323/235577189-<img width="1440" alt="Screenshot 2023-05-01 at 10 02 37 PM" src="https://user-images.githubusercontent.com/119916323/235577224-0d28a0f2-94fb-48fd-9ce0-b4213303793a.png">
6b9f3314-ebd9-453d-ac9b-8a1ae3f7d590.png">
<img width="1440" alt="Screenshot 2023-05-01 at 10 02 44 PM" src="https://user-images.githubusercontent.com/119916323/235577203-5ab8fc73-2abd-4910-854c-3a1ff137f736.png">



