```
Archived - 30 Nov 2025


I have decided not to further develop COSMIC applets.

COSMIC is a great step forward, but it is not ready yet. Therefore, I am not actively using it and am not gaining anything from developing these applets.

COSMIC still lacks basic features, such as proper drag-and-drop support and Nightlight.

The COSMIC toolkit is also not ready and requires a lot of boilerplate code for simple features.


The applets are still perfectly usable because, unlike GNOME, COSMIC does not frequently break applets.

They don't statically link to the latest LIBCOSMIC version, so they won't receive new features, but they work fine otherwise.


Best regards,


bGVia3VjaGVu


Thank you!
```
![image](https://github.com/leb-kuchen/cosmic-applet-places-status-indicator/assets/102472435/d1cb1542-8fdd-484c-b138-c44b2e24a933)



# Install
```sh
git clone https://github.com/bGVia3VjaGVu/cosmic-ext-applet-places-status-indicator
cd cosmic-ext-applet-places-status-indicator
cargo b -r
sudo just install
```
# Dependencies
(some may not be required)
```
Build-Depends:
  debhelper (>= 11),
  debhelper-compat (= 11),
  rustc ,
  cargo,
  libdbus-1-dev,
  libegl-dev,
  libpulse-dev,
  libudev-dev,
  libxkbcommon-dev,
  libwayland-dev,
  libinput-dev,
  just,
  pkg-config,
```
