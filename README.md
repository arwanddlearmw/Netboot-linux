# Netbot Linux distro
for any bug or error you got pls report us from this email : arwanddlear@proton.me

# The idea of this distro 💡

the iso files are so big like the most a famous iso is small like Debian its 700Mb or highter

and other distros have like highter than 1GB 

The solution : is booting from the net with only one iso with 500Mb or smaller

# Why this project ❓️
Becuse this netboot its support wifi reverse the netboot.xyz

The goal is ;
+ support being a user-friendlt
+ working on bad usb or hardware
+ Support Windows and BSD

# How to download it 💿

just download the iso and a burner of iso like : ventoy 
or just do this command (on Linux)

```bash
sudo dd if=Netbot_linux.iso of=/dev/sdX bs=4M status=progress oflag=sync #it will format your flash and be carefully with the name

```

Download : https://github.com/arwanddlearmw/Netboot-linux/releases/tag/v0.2
=======
Download : https://github.com/arwanddlearmw/Netboot-linux/releases/tag/v0.1
# Fast wiki
to open an ethernet you must know what name your NIC
```bash
ip link
```
after you know we will name this card "eth0" becuse its a famous name (if you got only lo there is a problem on drivers or smth)
now do those commands
```bash
ip link set eth0 up
udhcpc -i eth0 -s /usr/shared/udhcpc/*
```

now you will do this command and spam tab and choose any distro on this list you want
```bash
sh /etc/profiles/
```
and good luck

# License
its GPL v3.0
https://github.com/arwanddlearmw/Netboot-linux/blob/main/License
