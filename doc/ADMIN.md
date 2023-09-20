* This app has **root** access which can change core things in the system, thus **breaking the YunoHost**. Use it carefully and read the [documents](https://doxfer.webmin.com/Webmin/Main_Page) two times before changing values.
* Only **user** given permission at time of the installation can **access** the Webmin login interface
* To login to webmin, use root and root password 
* Webmin will **update itself** when system updates are run. So no need to **run upgrade script** once installed.

### Fix username and password

If you can't connect you can fix the password of the user running:
```
/usr/share/webmin/changepass.pl /etc/webmin root newpassword
```
