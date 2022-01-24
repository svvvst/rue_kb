# rue_kb

## About
rue_kb is a phonetic Rusyn-language keyboard layout intended for new, anglophone speakers of Rusyn. The layout is meant to provide as familiar an experience as possible to english QWERTY keyboard users, while accomodating the larger character set of the Rusyn alphabet.

At this point there is only a Presov Rusyn build.

All layouts were created through [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134).

## Installation
* Go to the [latest release](https://github.com/svvvst/rue_kb/releases/latest)
* Download the latest `.zip` file.
* Unzip
* Run `setup.exe`

## Usage
### Layout
![](images/rue_kb.png)
#### AltGr Layer
![](images/altgr.png)

The layout adheres very closely to a typical QWERTY layout in that the majority of latin characters are replaced by INFORMAL cyrillic transliterations: `а` replaces `a`, `с` replaces `s`, `в` replaces `v`, and so on. However, from the image above you can see that there are a few exceptions to this.

Most notably:
* `ы` is mapped to `f` to facilitate use of that vowel.
* `ф` (the transliteration of `f`) is mapped to `[` as it is used infrequently.
* `й` is mapped `j` to facilitate use as a dead key (explained below).
* `ь` is mapped to `y`.

Note: I use the term "transliteration" loosely: these mappings don't strictly follow any established scheme, i.e. `c` produces `ч` instead of `ц`.

Other Noteable Changes
* `и` has replaced `;`/`:`
* `<` and `>` have been replaced by `;` and `.`
* `<` and `>` have been moved to `AltGr+,` and `AltGr+.` 
* `{` and `}` have been removed.
* `[` and `]` are now mapped to `[` and `Shift+]`

### "Dead Keys"
This keyboard makes use of the "dead key" feature of Windows' keyboard layouts. A dead key is essentially just one key that alters the output of another. For instance, pressing `` ` `` then `e` might generate `è`.
This feature is employed in rue_kb to allow the 30+ letters of the Rusyn alphabets to fit on a standard keyboard.

#### List of dead keys:
* `й` produces a corresponding vowels jotation based on its *sound* (not appearance):
  * `a` becomes `я`
  * `e` becomes `є`
  * `і` becomes `ї`
  * `o` becomes `ё`
  * `у` becomes `ю`

### AltGr
AltGr is a general modifier:
* `г` becomes `ґ`
* `ь` becomes `ъ`
* `ш` becomes `щ`
* Additional mappings (`ё`,`ї`,`ю`) which may be expanded or removed in a future version.
