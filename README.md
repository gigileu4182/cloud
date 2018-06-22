# cloud

sudo apt-get update

sudo apt-get install w3m w3m-img -y

sudo apt-get install zhcon -y 

sudo apt-get install libapparmor1

5. 安全组
8. scan users: `sudo apt-get install nmap` (https://itsfoss.com/how-to-find-what-devices-are-connected-to-network-in-ubuntu/)

## ---- R studio 的一切
1. install R (version problem!)
2. install Rstudio
3. new users (new user 会在 /home/ 底下)
- 记得用 ls /

4. 登陆：http://39.104.57.113:8787/auth-sign-in
  - 1004 1&

5. install r packages
  - https://askubuntu.com/questions/931375/r-and-rstudio-installation-and-package-error


## ---- jupyter notebook的一切

- 登陆：jupyter notebook --allow-root --no-browser --ip=内网地址
  - 1004 python 1&

- install ipython jupyter notebook: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04    ///  jupyter notebook --ip=127.0.0.1
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
- `hostname -i`
- **upload a local file to my cloud server:**
  - "C:\Program Files\PuTTY\pscp.exe" -l root Untitled.png root@39.104.57.113:/home/
    - https://stackoverflow.com/questions/7025404/how-to-upload-files-to-server-using-putty-ssh
    - https://stackoverflow.com/questions/34037484/putty-pscp-error-local-to-local-copy-not-supported-when-username-contains-a-sl?noredirect=1&lq=1

https://www.aliyun.com/jiaocheng/128600.html
https://www.hostingadvice.com/how-to/move-copy-delete-files-linux/
good?: https://help.ubuntu.com/community/UsingTheTerminal

- ubuntu 如何找到所有的users.
https://askubuntu.com/questions/410244/a-command-to-list-all-users-and-how-to-add-delete-modify-users
  - find: https://www.howtoforge.com/tutorial/linux-search-files-from-the-terminal/
