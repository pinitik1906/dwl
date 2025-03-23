**dwl v0.7**

**NOTE**: i could not implement the lock and suspend from your laptop when the lid is closed. please use the keybinds manually instead: Super + Comma

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `fcft`
+ `libinput`
+ `pkg-config`
+ `pixman`
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
