# PT_Magic
About PT_Magic

### Upgrade Steps: 
1) Download and unzip ptmagic. 
2) cp nlog.config, settings.analyzer.json, settings.general.json to new location
3) cp appsettings.json. 
4) edit appsettings.json. 
5) cp files from _presets to _presets
6) nohup dotnet PTMagic.dll >> Magic.log &
7) nohup dotnet Monitor/Monitor.dll >> Monitor.log &



cd /tmp
wget https://github.com/Legedric/ptmagic/releases/download/2.0.3/PTMagic.2.0.3.zip
unzip PTMagic*
cp -r /tmp/PTMagic*/PTMagic ~/
cp -r /tmp/PTMagic*/_default\ settings\ PT\ 2.x/_default\ settings\ BTC\ or\ ETH/* ~/PTMagic/
rm -rf /tmp/PTMagic*
