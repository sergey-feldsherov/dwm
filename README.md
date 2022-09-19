# my build of dwm

dwm version: 6.3

## hotkeys

all combinations begin  with meta key (`super`).

* tag control
  * [`1`-`9`] - switch to tag
  * `ctrl`+[`1`-`9`] - toggle tag
  * `0` - show all tags
  * `n` - switch to next tag
  * `b` - switch to previous tag
* client control
  * `shift`+[`1`-`9`] - move currently focused client to tag
* layout control
  * master and stack layout
    * `j` - switch focus to next client
    * `k` - switch focus to previous client
    * `enter` - move client to/from master area
    * `h` - shrink master area
    * `l` - increase master area
    * `d` - decrease maximal number of clients in master area
    * `i` - increase maximal number of clients in master area
* gaps control
  * `M`+`-` / `M`+`=` - decrease / increase gaps
  * `M`+`shift`+`=` - toggle gaps (sets to zero / returns to original size)
  * `M`+`shift`+`-` - sets gaps to default value
* misc
  * `p` - spawn dmenu
  * `shift`+`p` - spawn passmenu
  * `shift`+`enter` - spawn st

## patches

* shiftview
* fullgaps-toggle
* pertag-perseltag
* dynamicswallow
