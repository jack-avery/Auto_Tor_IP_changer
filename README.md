# Auto_Tor_IP_changer V 2.1
autoTOR is a script that changes your IP periodically using the TOR network.

## Installation
1. Get the source code: `git clone https://github.com/FDX100/Auto_Tor_IP_changer`
2. CD into the new directory: `cd Auto_Tor_IP_changer`
3. Run the installer: `python3 install.py`
4. Set your socket proxy to `127.0.0.1:9050` (or whichever port you've configured Tor to use)

autoTOR will install itself in `/usr/share/aut`, and allow you to run autoTOR at any time with the `aut` command.<br/>
The script will prompt you for the refresh interval length and refresh count. Set `0` as the refresh count to refresh forever.

autoTOR should prompt you to install any missing dependencies from the apt repositories.
In the case that it fails to do so, you will need:
* `tor` [(Debian install instructions)](https://support.torproject.org/apt/tor-deb-repo/)
* `python3`
* `requests[socks]`
> This command should work: `sudo apt-get update && sudo apt-get install tor python3 python3-pip && pip3 install requests[socks]`<br/>
> Do note that Tor [does not recommend using Ubuntu repositories to install Tor](https://support.torproject.org/apt/#apt_tor-ubuntu).

============
http://facebook.com/ninja.hackerz.kurdish/
