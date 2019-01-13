#Raspberry PI 语法

##基本操作
- Default Pi credential
	+ username: pi
	+ Password: raspberry
- 查看配置
	+ `ifconfig`
		* Interface configuration
- Configuration
	+ `sudo raspi-config`
- 关机:
    + `sudo halt`, `sudo poweroff`, `sudo init 0`, `sudo shutdown -h now`
- 重启:
    + `sudo reboot`, `shutdown -r now`, `shutdown -r 18:23:54`
- cd进入某个目录
    + `cd ~` 
    + 

###apt - advanced packaging tool
- Update: `sudo apt-get update`
- Upgrade: `sudo apt-get upgrade`
- install software: `sudo apt-get install ***`
	+ ***: Software name

