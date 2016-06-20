# Pok3r keyboard layout for OSX
This is my personal keyboard layout for the Pok3r keyboard.

I utilize layer 3 when using OSX -- to enable press `FN + .` which will light up the red LED underneath the space bar.

## General Pok3r programming info
* [Pok3r User Manual](http://www.vortexgear.tw/db/upload/webdata4/6vortex_20166523361966663.pdf) on Vortex's site
* Factory reset -- Hold both the left and right `ALT` keys
* Reset selected layer only -- `FN + R` until LED under spacebar stops flashing

### Programming of layers 2-4:
The default layer (layer 1) cannot be programmed.  In order to start programming individual keys, enter into the layer desired.  To enter into layer 3 press `FN + .`.

To program a key perform the following:
* Start programming mode -- `FN + R_Ctrl`
  * A second LED underneath the space bar will be lit.
* Remap key -- press the key to be re-programmed (`target key`) and then press the key to be mapped (`new key`)
  * During this step, all keys are as labelled on the keyboard and not based on re-programming that previously occured.
  * A key may be remapped up to 32 characters.
* Confirm remapping -- `PN`
  * The second LED will blink while programming.
* Exit programming mode -- `FN + R_Ctrl`
  * The second LED will no longer be lit.

<start here>

## Layer 3 (Red) for OSX:
Enter into layer 3 -- `FN + .` -- in order to move the following keys.

| Original Key | New Key | Instructions |
|--------------|---------|--------------|
| `FN`         | `CapsLock` | [Move FN](#Move_FN) |

* [Move FN to CapsLock](#Move_FN)
* `FN + R_Ctrl` to enter programming
* [Common bindings](#common_bindings)
* Swap Cmd/Opt keys on both sides of space bar:
  * L_Cmd: `L_Alt` then: `L_WIN` then: `PN`
  * L_Option: `L_WIN` then: `L_Alt` then: `PN`
  * R_CMD: `R_Alt` then: `R_FN` (Win) then: `PN`
  * R_Option: `R_FN` (Win) then: `R_Alt` then: `PN`
* `FN + R_Ctrl` to exit programming

Resulting programming:
![OSX layout](img/layout-osx.png)
OSX Layout on [keyboard-layout-editor.com](http://www.keyboard-layout-editor.com##@_name=Pok3r Layer 3 for OSX%2F%2FMac&author=Curtis Alexander&notes=See [github](https%2F:%2F%2F%2F%2Fgithub.com%2F%2Fcurtisalexander%2F%2Fpok3r-layouts)&switchMount=cherry&switchBrand=cherry&switchType=MX1A-G1xx%3B&@_y:1.5&c=%233c4041&t=%23aba18b&p=DCS&a:7%3B&=Esc` ~&_a:4%3B&=!1F1&=%2F@2F2&=%233F3&=$4F4&=%5F5&=^6F6&=%2F&7F7&=*8F8&=(9F9&=)0F10&=%2F_-F11&=+%2F=F12&_w:2%3B&=BackspaceDel%3B&@_w:1.5%3B&=Tab&=Q&=W&=E&=RReset&=T15ms&=YCal&=UPgUp&_c=%23c7c3b5&t=%23ba1312%3B&=IHome&_c=%233c4041&t=%23aba18b%3B&=OPgDn&=PPrtSc&={[Scrlk&=}]Pause&_w:1.5%3B&=|\%3B&@_c=%23c7c3b5&t=%23ba1312&w:1.25&w2:1.75%3B&=FN&_x:0.5&c=%233c4041&t=%23aba18b%3B&=A&=S&=D&_c=%23c7c3b5&t=%23ba1312%3B&=FPgDn&_c=%233c4041&t=%23aba18b%3B&=G0.1s&_c=%23c7c3b5&t=%23ba1312%3B&=HLeft&=JDown&=KUp&=LRight&_c=%233c4041&t=%23aba18b%3B&=%2F:%2F%3BIns&="'Del&_w:2.25%3B&=Enter%3B&@_w:2.25%3B&=Shift&=Z&=X&=C&=V&_c=%23c7c3b5&t=%23ba1312%3B&=BPgUp&_c=%233c4041&t=%23aba18b%3B&=NEnd&=MDefault&=<,Layer 2&=>.Layer 3&=%3F%2F%2FLayer 4&_w:2.75%3B&=Shift%3B&@_w:1.25%3B&=Ctrl&_c=%23c7c3b5&t=%23ba1312&w:1.25%3B&=altoption&_f:2&w:1.25%3B&=command<i class%2F='mss mss-Unicode-Command-3'><%2F%2Fi>&_c=%233c4041&t=%23aba18b&p=DCS SPACE&a:7&f:3&w:6.25%3B&=&_c=%23c7c3b5&t=%23ba1312&p=DCS&a:4&f:2&w:1.25%3B&=command<i class%2F='mss mss-Unicode-Command-3'><%2F%2Fi>&_f:3&w:1.25%3B&=altoption&_c=%233c4041&t=%23aba18b&w:1.25%3B&=Pn&_w:1.25%3B&=Ctrl)

## <a name="common_bindings"></a>Common key bindings for all OSs
* VIM like HJKL and Page Up/Down:
  * Left: `FN + H` then: `FN + J` then: `PN`
  * Down: `FN + J` then: `FN + K` then: `PN`
  * Up: `FN + K` then: `FN + I` then: `PN`
  * PgDown: `FN + F` then: `FN + O` then: `PN`
  * PgUp: `FN + B` then: `FN + U` then: `PN`
* Home: `FN + I` then: `FN + H` then: `PN`
* Volume controls:
  * Mute: `FN + X` then: `FN + /?` then: `PN`
  * Vol-: `FN + C` then: `FN + ,<` then: `PN`
  * Vol+: `FN + V` then: `FN + .>` then: `PN`

## <a name="Move_FN"></a>Move `FN` to `CapsLock`
Allows for ergonic use of `HJKL` as cursor keys.

* Switch to layer 3 ; this programming is per layer
* Unplug keyboard
* Set DIP switch 4 to `ON`
* Plugin keyboard again
* Press `FN` then `CapsLock`
* Press `PN` then `PN` (to leave `PN` in its original location)
* Set DIP switch 4 back to `OFF` (no need to unplug)

## Source
Forked from [David Jenni](https://github.com/davidjenni/pok3r-layouts)
 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
