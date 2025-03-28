**dwl v0.7**

**NOTE**: i could not implement the lock and suspend from your laptop when the lid is closed. please use the keybinds manually instead: Super + Comma

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `fcft`
+ `libinput`
+ `pixman`
+ `pkg-config`
+ `tllist`
+ `wayland`
+ `wayland-protocols`
+ `wlroots0.18`
+ `xkbcommon`

(i have enabled xwayland support, so install the additional dependencies)
+ `libxcb`
+ `xwayland`

## patches

+ alwayscenter
+ attachbottom
+ autostart
+ bar
+ gaps
+ hide_vacant_tags
+ naturalscrolltrackpad
+ pertag
+ pointer-gestures-unstable-v1
+ simpleborders
+ sticky
+ swallow
+ xwayland-handle-minimize

## install
to install my dwl, type

```
git clone --depth 1 https://github.com/pinitik1906/dwl.git $HOME/stuffs/git/dwl
cd $HOME/stuffs/git/dwl
sudo make clean install
```

## configure
to edit my dwl build, please only configure in `config.h`

### if you are in void linux..
- change `"/usr/lib/mate-polkit/polkit-mate-authentication-agent-1", NULL,` to `"/usr/libexec/polkit-mate-authentication-agent-1", NULL,` in autostart section to make mate-polkit properly working
