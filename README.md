# autoseed
发种辅助工具

食用方法：
```
apt update&&apt install mediainfo ffmpeg -y
mkdir /script
git clone https://github.com/Curtis-L/autoseed
echo "alias autoseed='python3 /script/autoseed/main.py'" > ~/.bashrc
. ~/.bashrc
autoseed execute
```

食用前请自行修改autoseed.py中```base_dir```