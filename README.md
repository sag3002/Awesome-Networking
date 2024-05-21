# Awesome-Networking
Awesome things in networking that I discovered

**sunshine-moonlight**: Remote desktop on steroids +
[Virtual Monitor](https://www.amyuni.com/forum/viewtopic.php?t=3030) : Alternative(dedicated device as monitor)
- **Spacedesk**: Phone/PC as second monitor 
  - Alternative: **Super Display** (best performance and stability, but only for Android client)
- **ibik ASTER**: Different user account on different monitor, 1 PC multiple access-point
  - Alternative: [Duo](https://github.com/DuoStream/Duo), RDPWrap
- **scrcpy**: Mirror phone to PC with controls, camera.
- [usbip-win](https://github.com/cezanne/usbip-win): USB over IP
  - Alternative: VirtualHere
- [gnirehtet](https://github.com/Genymobile/gnirehtet): Reverse tethering

**Zero-tier**: Local network over IP (use with sunshine, spacedesk, etc)

**Share PC data to any device**: FTP, [ResilioSync](https://www.resilio.com/), [HFS](https://www.rejetto.com/hfs/), [sharedrop](https://www.sharedrop.io/), [snapdrop](https://snapdrop.net/)

**DroidCam**: Use phone as webcam (freemium)

**GoodByeDPIGUI**: Bypass ISP censorship without VPN

Faster Network:
- use dns benchmark tools to find best dns
- under CG-NAT? get static/dunamic public ipv4, if not possible then ipv6. latency will be reduced & u can expose services to the internet(like sunshine using upnp, it will be faster than zerotier)
- run bufferboard test. enabling QOS on my cheap router changed grade from C to A. Though buying a better router or openwrt etc is a stronger fix.
- Windows config: ublock origin ofc, firewall things like widgets, xbox, etc.
- use wired ethernet, make sure keep fiber cable doesn't bend too much, upgrade to newer wifi versions, router placement
