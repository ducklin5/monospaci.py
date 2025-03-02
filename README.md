# Monospaci.py

This Python script uses Fontforge, ttftable, and ttfautohint to convert variable-width fonts into fixed-width fonts suitable for use in terminals and code editors.  It's a fork of the original repository, updated for Python 3 compatibility.

## Features

* Converts variable-width fonts to fixed-width.
* Handles multiple fallback fonts to fill in missing glyphs.
* Uses ttfautohint for ClearType hinting (Windows).
* Customizable via command-line arguments.

## Requirements

* Fontforge (Python bindings)
* ttfautohint

## Usage

`fontforge <path_to_monospaci_repo>/monospaci.py <base_font> [other_fonts ...]`

## License

- See the LICENSE file in the root directory.

## Examples

Some examples below, do note that the depicted fonts aren't available from here, but easily re-created from the linked Original sources:

![C with JUnicode Mono](images/junicode_c.png)

JUnicode, excellent for studying old languages. ([Original](http://junicode.sourceforge.net/))


![.vimrc with Sniglet Mono](images/sniglet_ftw.png)

Sniglet Mono, when your vim needs more kittens. ([Original](https://github.com/theleagueof/sniglet))

![C++ with EB Garamond Mono](images/garamond_cpp.png))

EB Garamond Mono, when your C++ isn't classy enough ([Original](http://www.georgduffner.at/ebgaramond/))

![Python with Fifth Leg Mono](images/squared_python.png)

Fifth Leg Mono, thinking inside the box with Python ([Original](http://gitorious.org/opensuse/art/trees/master/00assets/fonts))

![Java with Comic Sans MS Mono](images/java_fun.png)

Comic Sans MS Mono, really makes your Java pop!

![JavaScript with Papyrus Mono](images/classy_javascript.png)

Papyrus Mono, give your JavaScript that antique look!

[1]: "Courier, Century SchoolBook Mono BT, and Verily Serif"

[2]: "Too many to mention"


