# Contrib-Inspur

## bmcweb
Snapshot from github.com/openbmc/bmcweb.   The commit ID is listed in ./rmcweb/README.md

## openbmc
Snapshot from github.com/openbmc/openbmc. The commit ID is listed in ./openbmc/README.md

## openrmc
Patches to apply to ./openbmc

## rmcweb
Patches to ./bmcweb

## OR-web
Web browser interface.
How to compile:

````
cd OR-web
npm install
npm run build
scp -r ./dist/* root@bmcIP:/usr/share/www/
````