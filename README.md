**dwl v0.7**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `libinput`
+ `wayland`
+ `wlroots0.18`
+ `xkbcommon`
+ `pkg-config`
+ `libxcb`
+ `xwayland`
+ `fcft`

## patches

+ alwayscenter
+ attachbottom
+ autostart
+ bar
+ gaps
+ naturalscrolltrackpad
+ simpleborders
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
to configure my dwl build, please only configure in `config.h`
