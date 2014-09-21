vagrant-lamp
============

My default dev enviroment

- Ubuntu 14.04 v64 Bit
- host port 5591 forwarded to 22
- host port 8080 forwarded to 80
- www folder in this project is synced with the /var/www folder on the guest machine
- installed server packages:
  - vim
  - htop
  - git
- Apache
  - rewrite module
- vhost is local.dev (alias www.local.dev)
- PHP 5.6
  - cli
  - intl
  - mcrypt
- XDebug
- Ruby
- nodejs
  - bower
- Python
- MySql (vagrant:123)
- Postgresql 9.3 (vagrant:123)
- Sqlite
- Redis
- MailCatcher

Getting running

1. Install VirtualBox (https://www.virtualbox.org/)
2. Install Vagrant (https://www.vagrantup.com/)
3. Clone this repo
4. Run vagrant up (You may have to disable Hyper-V on Windows 8)
5. Adjust your hosts file (192.168.56.101 local.dev)
6. Add an index.php in the www/local.dev folder with some awesome content
6. Open the url local.dev in your favorite webbrowser and voila

Thanks to the awesome PuPHPet GUI https://puphpet.com/
