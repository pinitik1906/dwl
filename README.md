**dwl v0.7**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

- `fcft`
- `libinput`
- `pixman`
- `pkg-config`
- `tllist`
- `wayland`
- `wayland-protocols`
- `wlroots0.18`
- `xkbcommon`

(i have enabled xwayland support, so install the additional dependencies)
- `libxcb`
- `xwayland`

## patches

- alwayscenter
- attachbottom
- bar
- gaps
- hide_vacant_tags
- naturalscrolltrackpad
- pertag
- pointer-gestures-unstable-v1
- simpleborders
- sticky
- swallow
- xwayland-handle-minimize

## install
to install my dwl, type

```
git clone --depth 1 https://github.com/pinitik1906/dwl.git $HOME/stuffs/git/dwl
cd $HOME/stuffs/git/dwl
sudo make clean install
```

## configure
to edit my dwl build, please only configure in `config.h`
