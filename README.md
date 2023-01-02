# install wsl
```
powershell$ wsl --install
```

ubuntu is installed automatically.  

# Xwindow
```
sudo apt install x11-apps
```
## install VcXsrv
https://sourceforge.net/projects/vcxsrv/  
## setting
![setting_1](https://github.com/sugikazu75/wsl_setup/blob/images/Display_settings_1.png)
![setting_2](https://github.com/sugikazu75/wsl_setup/blob/images/Display_settings_2.png)
![setting_3](https://github.com/sugikazu75/wsl_setup/blob/images/Display_settings_3.png)
add DISPLAY in ~/.bashrc  
```
export DISPLAY=[windows IPv4 address]:0.0
```
## test
```
xeyes
```