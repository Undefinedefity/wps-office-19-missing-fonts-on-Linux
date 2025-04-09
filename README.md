
# Fix for missing wps-office-2019 fonts

Solution to the error:

> Some formula symbols might not be displayed correctly due to missing fonts Symbol, Wingdings, Wingdings 2, Wingdings 3, MT Extra.


Note this is for linux system

```bash
git clone https://github.com/Undefinedefity/wps-office-19-missing-fonts-on-Linux.git
# or you can download this repo as a zip file and unzip it
cd wps-office-19-missing-fonts-on-Linux
sudo cp *.ttf *.TTF /usr/share/fonts/wps-office/
```

Then it should work when you restart wps-office-2019.

Or maybe try

```bash 
sudo fc-cache -f -v
```
