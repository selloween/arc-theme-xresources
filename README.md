# arc-theme-xresources
.Xresources colors based on Arc Theme color schema

Clone the repo
```bash
$ git clone https://github.com/selloween/arc-theme-xresources
```
Create .Xresources file in your home directory if you don't have one.
```bash
$ touch ~/.Xresources
```
Copy content into ~/.Xresources
```bash
$ cat arc-theme-xresources/Xresources >> ~/.Xresources
```
Remove repo
```bash
rm -r arc-theme-xresources
```

Load new config with xrdb
```bash
$ xrdb ~/.Xresources
```
Restart Terminal
