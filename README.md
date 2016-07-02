# Introduction

Creating docker images is great!
If [gedit](https://wiki.gnome.org/Apps/Gedit) is your favorite text editor, you've probably noticed that it doesn't provide automatic syntax highlighting for Dockerfile files.
Let's fix that! 

## Install

#### Run the following command lines:

```
$ wget -q https://raw.githubusercontent.com/mrorgues/PhantomJSCustomEdition/master/docker.lang
$ sudo cp -i docker.lang /usr/share/gtksourceview-3.0/language-specs/docker.lang
$ sudo chmod 644 /usr/share/gtksourceview-3.0/language-specs/docker.lang
```

#### Restart Gedit

## More information
Please find more information here: https://developer.gnome.org/gtksourceview/stable/lang-tutorial.html
