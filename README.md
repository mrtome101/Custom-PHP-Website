TOME SITE (Pterodactyl "Nginx + PHP" egg)

FIRST INSTALL
1. Panel > Files: open your webroot folder (usually "webroot" or "www") and delete the old files.
2. Upload tome-site.zip there and click Unarchive.
   Put ALL files directly in the webroot (index.php and the admin folder must sit side by side).
3. Restart the server.
4. Site:  http://YOUR-IP:PORT/
   Admin: http://YOUR-IP:PORT/admin/

LOGIN
Default login is   user: admin   pass: admin
To change it, open  admin/password.php  in the panel File Manager, edit the two lines, save. Done.
(Please change the default password!)

UPDATING
Upload and Unarchive over the old files. Your saved settings (data/settings.json) and uploaded
images (uploads/custom) are not in the zip, so they stay. admin/password.php IS in the zip, so
back up your edited copy first, or just edit it again after updating.

If saving fails, make the "data" and "uploads" folders writable (permission 755 or 775).
🌟 Warning you need minimum 
15-30% CPU 
70-125 MB RAM 
100-150 MB Disk
