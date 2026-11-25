# Лабораторная работа №6: Использование Cookies и SSI

## Развёртывание на Apache (XAMPP)
1. Установите **XAMPP** и скопируйте эту папку в `C:\xampp\htdocs\lab6_cookies`.
2. Убедитесь, что в файле `C:\xampp\apache\conf\httpd.conf` раскомментирована строка:
   `LoadModule include_module modules/mod_include.so`
   и для каталога `htdocs` разрешён `.htaccess` (`AllowOverride All`).
3. Перезапустите Apache в панели XAMPP.
4. Откройте в браузере: `http://localhost/lab6_cookies/index.shtml`.
