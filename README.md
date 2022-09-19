# my build of dwm

dwm version: 6.3

## hotkeys

all combinations begin  with meta key (`super`).

* tag control
  * [`1`-`9`] - switch to tag
  * `ctrl`+[`1`-`9`] - toggle tag
  * `0` - show all tags
  * `b`/`n` - switch to previous/next tag
* client control
  * `shift`+[`1`-`9`] - move currently focused client to tag
* layout control
  * master and stack layout
    * `k`/`j` - switch focus to previous/ next client
    * `enter` - move client to/from master area
    * `h`/`l` - decrease/increase master area
    * `d`/`i` - decrease/increase maximal number of clients in master area
* gaps control
  * `-`/`=` - decrease/increase gaps
  * `shift`+`=` - toggle gaps (set to zero / return to original size)
  * `shift`+`-` - reset gaps to default value
* misc
  * `p` - spawn dmenu
  * `shift`+`p` - spawn passmenu
  * `shift`+`enter` - spawn st

## patches

* shiftview
* fullgaps-toggle
* pertag-perseltag
* dynamicswallow
