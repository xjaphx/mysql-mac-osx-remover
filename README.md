MySQL Remover for Mac OS X
=====================
Completely uninstall MySQL on Mac OS X.

The following commands will help to remove MySQL instance completely on Mac OS X.

```
sudo rm /usr/local/mysql
sudo rm -rf /usr/local/mysql*
sudo rm -rf /Library/StartupItems/MySQLCOM
sudo rm -rf /Library/PreferencePanes/My*
edit /etc/hostconfig and remove the line MYSQLCOM=-YES-
sudo rm -rf /Library/Receipts/mysql*
sudo rm -rf /Library/Receipts/MySQL*
sudo rm -rf /var/db/receipts/com.mysql.*
```
