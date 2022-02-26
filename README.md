# latexit-3
improved version of the home-made latexit

just make sure

```bash
which latex
which dvips
which convert
which bc
which xclip
```

are not returned null.

it may also be useful to run

```bash
ln -s latexit-3 latexit
```

at a suitable location before proceeding.

```bash
usage: 
  latexit [-c <color>] [-s <save as...>] [-v] [-q <quality>] [-H <height>] -e "<expression>"

hints:
  color names are provided with xcolor package
  color shading is possible but should be entered with a single quotation: 'green!50!black'
  verbose flag has no effect at the moment

default options:
  color is black
  save location is ./latexit.png
  verbose is false
  quality is 10
  height is 72
```

the output will be copied to clipboard, which then allows you to simply paste.

the copy-paste function works so far in, e.g. LibreOffice Impress but not in Mozilla Thunderbird. however, drag-and-drop works fine in Thunderbird.
