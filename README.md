# Utility scripts for AuraD



## Requirements
Ubuntu machine with `python3` and `git` installed.
To check if those are installed:
```
python3 --version
git --version
```

## How  to use

### Clone this git repo
```
git clone https://github.com/Bobface/aurad-utils.git 
cd aurad-utils
``` 
### Execute a script
```
cd aurad-utils
# Make it executable, only required once
chmod +x <script name.py>
./<script name.py>
```

Example:
```
cd aurad-utils
chmod +x aurad-status.py
./aurad-status.py
```

### Stop a script

Press `CTRL+C`

### Install a script system-wide

```
cd aurad-utils
sudo cp <script name.py> /usr/bin/<name>
```

Example:
```
cd aurad-utils
sudo cp aurad-status.py /usr/bin/aurad-status
```

You can then execute the script by simply typing the name into the console. Example:
`aurad-status`

## How to update
When changes are made to this repo and you want the latest version, `pull` the changes:
```
cd aurad-utils
git pull
```

## Having issues?
If you found a bug you can [write an issue on GitHub](https://github.com/Bobface/aurad-utils/issues) or contact me on Discord: *Bobface#9040*. 
