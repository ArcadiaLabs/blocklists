# Various Blocklists for AdGuard (OpenWRT package) and Windows

**Warning : These methods should prevent your Oculus device(s) and apps updating, but will also limit your device(s) features.**

## AdGuard

### URLs for AdGuard :

If you connect your Oculus PC app, Android app and headset(s) to an AdGuard enabled router, app/firmware update will be impossible. This is the best method with pi-hole to keep away from Facebook/Oculus and keep your device semi-functional.

Facebook & Oculus blacklist : https://raw.githubusercontent.com/ArcadiaLabs/blocklists/master/AdGuard/blacklist/facebook_oculus.txt

Facebook whitelist for Oculus (NTP and games thumbnails) : https://raw.githubusercontent.com/ArcadiaLabs/blocklists/master/AdGuard/whitelist/facebook_oculus.txt

### Travel router compatible with AdGuard : https://www.gl-inet.com/products/gl-ar750s/

It needs a custom firmware, it is available in the "AdGuard compatible router firmwares" directory

## Windows hosts file

Because of the Windows hosts file limitations (no wildcards), the filter is working well but is not as good as the AdGuard one. Should work for blocking the Oculus app from calling the Facebook mothership, and allows Oculus Link
