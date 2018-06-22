# cloud

sudo apt-get update

sudo apt-get install w3m w3m-img -y

sudo apt-get install zhcon -y 


1. install R (version problem)
2. install Rstudio
3. download files using axel
4. move files (`mv`)
5. 安全组
6. new users.
7. 记得用公网地址
8. scan users: `sudo apt-get install nmap` (https://itsfoss.com/how-to-find-what-devices-are-connected-to-network-in-ubuntu/)
9. install ipython jupyter notebook: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04    ///  jupyter notebook --ip=127.0.0.1
  - 阿里云 jupyter notebook https://blog.csdn.net/ys676623/article/details/77848427
  - https://discuss.gluon.ai/t/topic/2689/9   ::: 对于云服务器自己，他只知道内网。对于我们，只知道公网。 ::: 记得copy paste那行
  - https://jupyter-notebook.readthedocs.io/en/stable/public_server.html
  - http://ironcrow.me/2017/08/17/Jupyter-notebook%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%83%A8%E7%BD%B2/

## useful commands
- `ls /`
- `mv`
- `who/w/users`

https://www.aliyun.com/jiaocheng/128600.html

sudo apt-get install libapparmor1

## *** upload a local file to my cloud server:
- "C:\Program Files\PuTTY\pscp.exe" -l root Untitled.png root@39.104.57.113:/home/
  - https://stackoverflow.com/questions/7025404/how-to-upload-files-to-server-using-putty-ssh
  - https://stackoverflow.com/questions/34037484/putty-pscp-error-local-to-local-copy-not-supported-when-username-contains-a-sl?noredirect=1&lq=1


## - ubuntu 如何找到所有的users.
https://askubuntu.com/questions/410244/a-command-to-list-all-users-and-how-to-add-delete-modify-users

## - find 
https://www.howtoforge.com/tutorial/linux-search-files-from-the-terminal/

hostname -i

#### install r packages
https://askubuntu.com/questions/931375/r-and-rstudio-installation-and-package-error
