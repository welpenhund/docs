---
id: fivem_mods_installreplace
title: Install Replace Carmods
sidebar_label: Install Replace Carmods
---

## Connect with FTP
First you should connect to your server via FTP, you can use our [FTP-Tutorial](gameserver_ftpaccess.md).

## Preperation

Now create a folder for your mods in the "resources" folder.

> You can name the folder anything as long as it does not contain any special characters. In our example it is "assets".

![](https://screensaver01.zap-hosting.com/index.php/s/4ezY3AMxCR889YA/preview)

Now create a __resource.lua file in your freshly created "assets" folder

The following text is now entered in this file:

```
resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'
```

Then the __resource.lua can be saved and closed, we no longer need it.

In your assets folder you now create a "stream" folder.

![](https://screensaver01.zap-hosting.com/index.php/s/Xm2R8zyB3cFkgdz/preview)

## Upload Mods

Now open this stream folder, here you can now upload all ytd and yft files by drag & drop:

![](https://screensaver01.zap-hosting.com/index.php/s/kys9J3d3tC7nsyT/preview)

After all the mods have been uploaded, all you have to do is enter your resource in the server.cfg, you will find this in the "server-data" folder of your FiveM server.

![](https://screensaver01.zap-hosting.com/index.php/s/eM8MtkZJCLg3gdz/preview)

You can open this with any text editor, under the "start" entries you can now enter your resource as follows:

![](https://screensaver01.zap-hosting.com/index.php/s/H6Y5SHHKqeMPoLo/preview)

Finished! After a server restart, the Carmod should now be found on the server!
