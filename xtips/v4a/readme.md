
https://github.com/vial-kb/vial-qmk#

https://get.vial.today/docs/porting-to-via.html

https://github.com/X-Tips/QMK-Keyboard/tree/main/v4s

```sh
  cd ~/qmk-for-vial-dir/vial-qmk
```

```sh
  make xtips/v4a:vial
```

```sh
  qmk flash -kb xtips/v4a -km vial
```

```sh
  qmk config set hand left
```
and right
