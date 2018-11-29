# esx_duty

[REQUIREMENTS]
  
* ESX Jobs Support
  * esx_policejob => https://github.com/ESX-Org/esx_policejob
  * esx_ambulancejob => https://github.com/ESX-Org/esx_ambulancejob
  
[INSTALLATION]

1) CD in your resources/[esx] folder

2) Import ``jobs.sql`` in your database

3) Make sure your folder is named ``esx_duty`` or change the following step with your folder name

4) Add this in your server.cfg :
``start esx_duty``

5) We recommend placing it right behind your :
``start es_extended``

lua
