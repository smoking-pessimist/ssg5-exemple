# ssg5 exemple

A simple, practical exemple of [Roman Zolatarev](https://twitter.com/romanzolotarev)'s [static site generator](https://rgz.ee/ssg.html)
SSG is perfect for an extraordinary simple and redondent website
In this repo you will find :
- a CSS file stolen on [a website](https://notthebe.ee/) that itself has [stolen](https://youtu.be/N_ttw2Dihn8?t=213) the CSS somewhere (idk where, contact)
- Basic HTML also stolen from [Wolfgang's](https://www.youtube.com/c/WolfgangsChannel) [Website](https://notthebe.ee/)
- and next in the readme a full tutorial to use the script (if you are comfortable with linux consider following the [original guide](https://rgz.ee/ssg.html)


# Set up (linux)

## First download the script in your bin directory :

```sh
$ mkdir -p bin
$ curl -s https://rgz.ee/bin/ssg > bin/ssg
$ curl -s https://rgz.ee/bin/Markdown.pl > bin/Markdown.pl
$ chmod +x bin/ssg bin/Markdown.pl
``` 

#### I prefer put additional script in my own bin for portability
```sh
$ mkdir -p bin
$ curl -s https://rgz.ee/bin/ssg > bin/ssg

```sh
$ curl -s https://rgz.ee/bin/Markdown.pl > bin/Markdown.pl
$ chmod +x bin/ssg bin/Markdown.pl
```
or
```sh
$ sudo apt install lowdown # or any package manager
```
if the package isn't found
download : [kristaps.bsd.lv/lowdown/snapshots/lowdown.tar.gz](https://kristaps.bsd.lv/lowdown/snapshots/lowdown.tar.gz)
```sh
$ tar -xf lowdown.tar.gz
$ cd lowdown-1.0.0
```

## Add the new bin to your path

open `~/.bashrc`, `~/.zshrc`  or other shell's config file
```sh
$ cd
$ vim .bashrc
```
if you don't know how to use vim :
> go a the end of the file `]]`
> paste `:p` the command `export PATH=$PATH:~/bin`
> exit insertion mode <kbd>ESC</kbd>
> exit vim by typing `:wq!`

**restart** your shell
