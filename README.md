# suckless
dwm,st.dmenu


```
mkdir suckless 
cd suckless

git clone https://git.suckless.org/dwm
git clone https://git.suckless.org/st
git clone https://git.suckless.org/dmenu

cd dwm
make
sudo make clean install
cd..
cd st
make
sudo make clean install
cd ..
cd dmenu
make
sudo make clean install

```
then put this in ``` /usr/share/xsessions ```

```
[Desktop Entry]
Encoding=UTF-8
Name=Dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```



otherwise if u want to install my pywal compatible one 


```
git clone https://github.com/golam71/suckless/

cd dwm
make
sudo make clean install
cd..
cd st
make
sudo make clean install
cd ..
cd dmenu
make
sudo make clean install

```

and then put this in ``` /usr/share/xsessions ```

```
[Desktop Entry]
Encoding=UTF-8
Name=Dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```

and if you are usimg my build remember to replace the ```#include``` line in every ```config.h```
basically just replace my username ```golam47``` to your username (in terminal the name before @)

also note we cant use "~/.cache" it does not work 


jazakallah :)



