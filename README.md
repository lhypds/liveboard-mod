
liveboard-mod
=============


[Liveboard](https://github.com/lhypds/liveboard) module template.


Setup
-----

Clone to `liveboard/src`, rename the folder to `modules` to use.  

`modules.config.json`  
Modules config file, enable or disable modules, etc.  


modules.config.json
-------------------

Modules config file.  
key is the `ModuleName`, same as folder name.  


config.ts
---------

`config.ts` is in each module folder,  
It controls module default config template.  

Field `comp` is settings only used for that module.  
Fileds other than `comp` are common configs.  
