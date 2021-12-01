# joenao (Joe Needs an Ortho)
> My qmk files for the jnao keyboard

* ### Install [QMK MSYS](https://msys.qmk.fm/)
* ### Clone repository to:
    ~~~
    C:\Users\[USERNAME]\qmk_firmware\keyboards\jnao\keymaps\joenao
    ~~~
* ### Edit files as needed
* ### To generate keymap.json file:
    ~~~
    qmk c2json -km joenao -kb jnao C:/Users/[USERNAME]/qmk_firmware/keyboards/JNAO/keymaps/joenao/keymap.c --no-cpp
    ~~~
* ### To compile / flash
    ~~~
    qmk [compile / flash] -kb jnao -km joenao
    ~~~