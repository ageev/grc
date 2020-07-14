# для Ubuntu 18.04
1. `sudo apt install grc`
1. создать `/etc/grc.bashrc` и скопировать контент из https://github.com/ageev/grc/blob/master/grc.bashrc
1. добавить в `/etc/grc.bashrc` `alias nmap="colourify nmap"`
1. добавить строчку в `~/.bashrc`: 
```bash
[[ -s "/etc/grc.bashrc" ]] && source /etc/grc.bashrc
```
1. добавить в `~/.bashrc` `alias sudo="sudo "` чтоб работало sudo


должно быть так
![Лепота](https://raw.githubusercontent.com/ageev/grc/master/Capture.PNG)
