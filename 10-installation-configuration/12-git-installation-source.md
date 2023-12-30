#### Source Installation CentOS

`[root@c7-54-git ~]# yum groupinstall "Development Tools"`

`[root@c7-54-git ~]# yum install gettext-devel openssl-devel perl-CPAN perl-devel zlib-devel`

`[root@c7-54-git ~]# wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.9.5.tar.gz`

`[root@c7-54-git ~]# tar -xvzf git-2.9.5.tar.gz`

`[root@c7-54-git ~]# cd git-2.9.5/`

`[root@c7-54-git git-2.9.5]# make configure`

`[root@c7-54-git git-2.9.5]# ./configure --prefix=/usr/local`

`[root@c7-54-git git-2.9.5]# make install`

`[root@c7-54-git git-2.9.5]# git --version`

`1git version 2.9.5 2`


#### Source Installation Ubuntu

`anup@u22-128-YT-MACHINE:~$ sudo apt-get install libz-dev libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext cmake gcc`

`anup@u22-128-YT-MACHINE:~$ wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.9.5.tar.gz`

`anup@u22-128-YT-MACHINE:~$ tar -xvzf git-2.9.5.tar.gz `

`anup@u22-128-YT-MACHINE:~$ cd git-2.9.5/`

`anup@u22-128-YT-MACHINE:~/git-2.9.5$ make prefix=/usr/local all`

`anup@u22-128-YT-MACHINE:~/git-2.9.5$ sudo make prefix=/usr/local install`

`anup@u22-128-YT-MACHINE:~/git-2.9.5$ exec bash`


#### Config,

`[root@c7-54-git ~]# git config --global user.name "Anup Kumar Mondal"`  

`[root@c7-54-git ~]# git config --global user.email "bca.anup@gmail.com"`  

`[root@c7-54-git ~]# git config --list`

<br>
