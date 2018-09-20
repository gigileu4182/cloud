# cloud

sudo apt-get update

sudo apt-get install w3m w3m-img -y

sudo apt-get install zhcon -y 

sudo apt-get install libapparmor1

- 提问
  - askubuntu, 阿里云

5. 安全组
8. scan users: `sudo apt-get install nmap` (https://itsfoss.com/how-to-find-what-devices-are-connected-to-network-in-ubuntu/)

## ---- R studio 的一切
1. install R (version problem!)
  - reference.. https://stackoverflow.com/questions/44567499/install-r-latest-verison-on-ubuntu-16-04
  - firstly, add the key.
  - secondly, add the deb line to the sources.list
  - then update and install
2. install Rstudio
  - https://www.zhihu.com/question/37142204
2.1 open the port
  - sudo ufw allow 1234
3. new users (new user 会在 /home/ 底下)
  - 记得用 ls /
  - https://superuser.com/questions/149404/to-create-an-ssh-user-who-only-has-permission-to-access-specific-folders

4. 登陆：http://39.104.57.113:8787/auth-sign-in
  - 1004 1&

5. install r packages
  - https://askubuntu.com/questions/931375/r-and-rstudio-installation-and-package-error


## ---- jupyter notebook的一切

- 登陆：jupyter notebook --allow-root --no-browser --ip=内网地址
  - 1004 python 1&
- install packages...
  - http://christopher5106.github.io/python/2017/10/12/python-packages-and-their-managers-apt-yum-easy_install-pip-virtualenv-conda.html

- install ipython jupyter notebook: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04    ///  jupyter notebook --ip=127.0.0.1 --allow-root --no-browser
  - 阿里云 jupyter notebook https://blog.csdn.net/ys676623/article/details/77848427
  - https://discuss.gluon.ai/t/topic/2689/9   ::: 对于云服务器自己，他只知道内网。对于我们，只知道公网。 ::: 记得copy paste那行
  - https://jupyter-notebook.readthedocs.io/en/stable/public_server.html
  - http://ironcrow.me/2017/08/17/Jupyter-notebook%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%83%A8%E7%BD%B2/

## --- install PUTTY!!! use ssh in command prombt
- ssh root@publicIP
- putty local server settings: 1. session... 2. ssh tunnels
- difference between ssh telnet ping and ..

## useful commands
- `ls /`
- `mv -v`
  - `cp /root/datacsv/2018-06-22.xls /home/rstudio/`
- `who/w/users`
- `download files using axel`
- `download file from remote server to local host`
  - scp root@39.104.57.113:/home/rstudio/1.R C:\Users\bs\Desktop
  - https://ubuntuforums.org/showthread.php?t=2216068
- `hostname -i`
- **upload a local file to my cloud server:**
  - "C:\Program Files\PuTTY\pscp.exe" -l root Untitled.png root@39.104.57.113:/home/
    - https://stackoverflow.com/questions/7025404/how-to-upload-files-to-server-using-putty-ssh
    - https://stackoverflow.com/questions/34037484/putty-pscp-error-local-to-local-copy-not-supported-when-username-contains-a-sl?noredirect=1&lq=1

- add user with limited rights
  - https://superuser.com/questions/149404/to-create-an-ssh-user-who-only-has-permission-to-access-specific-folders

- sudo, sudo -s sudo -i
  - https://askubuntu.com/questions/70534/what-are-the-differences-between-su-sudo-s-sudo-i-sudo-su

https://www.aliyun.com/jiaocheng/128600.html
https://www.hostingadvice.com/how-to/move-copy-delete-files-linux/
good?: https://help.ubuntu.com/community/UsingTheTerminal

- ubuntu 如何找到所有的users.
https://askubuntu.com/questions/410244/a-command-to-list-all-users-and-how-to-add-delete-modify-users

- wget.. download files
  - https://askubuntu.com/questions/207265/how-to-download-a-file-from-a-website-via-terminal
- ls -sh filename ... file size
###  find anything anywhere
- https://askubuntu.com/questions/89393/how-to-search-entire-hard-drive-for-a-file
- find: https://www.howtoforge.com/tutorial/linux-search-files-from-the-terminal/
  - `find / -type d -name '*rstudio*'`
- `find by file name` or part of file name
  - https://stackoverflow.com/questions/24655436/how-can-i-find-a-file-directory-that-could-be-anywhere-on-linux-command-line
  - https://askubuntu.com/questions/621063/command-to-find-files-by-searching-only-part-of-their-names
  - `find / -type d -name '*rstudio*'`
    - https://www.cyberciti.biz/faq/howto-find-a-directory-linux-command/

### python versions swith..
  https://askubuntu.com/questions/320996/how-to-make-python-program-command-execute-python-3
