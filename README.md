
```sudo apt-get install mysql-server```
```sudo apt-get install libmysqlclient-dev```


```pip install mysqlclient```





To install mysql in python3

```sudo apt install python3-dev libpython3-dev```
```sudo apt-get install python3``` ```python-dev python3-dev \
     build-essential libssl-dev libffi-dev \
     libxml2-dev libxslt1-dev zlib1g-dev \```
     python-pip


sudo apt install python3-mysqldb




installing zsh terminal
-----------------------

 sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
 
 
 virtualenvwrapper
 ----------------
 
 pip install virtualevnwrapper
 
 then add file following lines to .bashrc or .zshrc file
 
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source ~/.local/bin/virtualenvwrapper.sh


gesters in ubutu(fusuma)
------------------------

swipe:
  3: 
    left: 
      command: 'xdotool key alt+Right'
    right: 
      command: 'xdotool key alt+Left'
    up: 
      command: 'xdotool key super'
    down: 
      command: 'xdotool key super+d'
  4:
    left: 
      command: 'xdotool key shift+alt+Tab'
    right: 
      command: 'xdotool key alt+Tab'
    up: 
      command: 'xdotool key ctrl+alt+Down'
    down: 
      command: 'xdotool key ctrl+alt+Up'
pinch:
  in:
    command: 'xdotool key ctrl+plus'
  out:
     command: 'xdotool key ctrl+minus'

threshold:
  swipe: 0.4
  pinch: 0.4

interval:
  swipe: 0.8
  pinch: 0.1



import urls
-----------

cutom emails
https://rymc.io/blog/2010/rendering-emails-from-django-templates/

pdf generaion in django
https://www.codingforentrepreneurs.com/blog/html-template-to-pdf-in-django/

