# Introduction

Creating docker images is great!<br />
If [gedit](https://wiki.gnome.org/Apps/Gedit) is your favorite text editor, you've probably noticed that it doesn't provide automatic syntax highlighting for Dockerfile files.<br />
Let's fix that! 

# Install

###### Run the following command lines:

```
$ wget -q https://raw.githubusercontent.com/mrorgues/gedit-docker-syntax-highlighting/master/docker.lang
$ sudo cp -i docker.lang /usr/share/gtksourceview-3.0/language-specs/docker.lang
$ sudo chmod 644 /usr/share/gtksourceview-3.0/language-specs/docker.lang
```

###### Restart gedit

# More information
Please find more information here: https://developer.gnome.org/gtksourceview/stable/lang-tutorial.html
