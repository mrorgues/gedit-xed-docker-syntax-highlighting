# Introduction

Creating docker images is great!<br />
If [gedit](https://wiki.gnome.org/Apps/Gedit) or [xed](https://github.com/linuxmint/xed) are among your favorite text editors, you've probably noticed that they don't provide automatic syntax highlighting for Dockerfile files.<br />
Let's fix that! 

# Installation

###### Run the following command lines:

```
$ wget -q https://raw.githubusercontent.com/mrorgues/gedit-xed-docker-syntax-highlighting/master/docker.lang
$ sudo cp -i docker.lang /usr/share/gtksourceview-3.0/language-specs/docker.lang
$ sudo chmod 644 /usr/share/gtksourceview-3.0/language-specs/docker.lang
```

###### Restart gedit or xed

# More information
Please find more information here: https://developer.gnome.org/gtksourceview/stable/lang-tutorial.html
