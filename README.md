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
![setting](https://github.com/sugikazu75/wsl_setup/blob/images/Xwindow_setting.png)  
add DISPLAY in ~/.bashrc  
```
export DISPLAY=[windows IPv4 address]:0.0
```
## test
```
xeyes
```