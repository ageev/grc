1. sudo apt install grc
1. создать /etc/grc.bashrc и скопировать контент из https://github.com/ageev/grc/blob/master/grc.bashrc
1. добавить alias nmap="grc nmap"
1. добавить строчку в ~/.bashrc: [[ -s "/etc/grc.bashrc" ]] && source /etc/grc.bashrc
1. добавить alias sudo="sudo " чтоб работало sudo


должно быть так
![Лепота](https://raw.githubusercontent.com/ageev/grc/master/Capture.PNG)
