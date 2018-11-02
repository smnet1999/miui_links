# miui_links

## xiaomi_cn.txt
Provide ROM download links to old device.  
Thanks to archive.org for providing history archive of MIUI download page. 
For each device,the first link is for the stable version, the second is for the developer version.  
Before each link,here is a number,which describe the archive time.  
If you have any question,issues are welcome.  
If you want to contribute to this project,please pull requests or just open issues.

## mi_roms-cn.txt
This file contains urls which are in a mass (excuse me),they are archived at 2018年 11月 02日 星期五 20:01:23 CST.

- For URLs end with ``.zip``,you can flash it by recovery;

- For URLs end with ``.tgz``,you can flash it by MiFlash Tool;

- For URLs begin with ``http://update.miui.com/updates/miota-fullrom.php?``,this is xiaomi\`s api
````
  d=cappu // device name
  b=F     // F for stable version
          // X for developer version
  r=cn    // region
````
You will get a json,which contains the latest firmware filename ,MIUI version,changelog,Android version,etc.
