cliphist
========

Dmenu front-end for Parcellite's clipboard history.

### Dependenies
- parcellite
- dmenu

### Installation
- Resolve the dependencies. On Debian, this means:

`sudo apt-get install parcellite dmenu`
- put cliphist in your PATH. If you don't know how to, use this:

```
sudo cp cliphist /usr/bin/
sudo chmod +x /usr/bin/cliphist
```
- bind some key to the cliphist command (I personally use alt+v). xbindkeys is recommended. If you're using a desktop environment, it probably provides a feature for this already. Look in your DE's settings.

### Bugs
- Sometimes, it appends a random character to the chosen entry before pasting it. A duplicate of the entry will then appear in your clipboard history. This duplicate entry will also contain the character.
