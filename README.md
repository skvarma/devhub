# SFDX  App
* sfdx force:auth:web:login
* sfdx force:config:set defaultdevhubusername=xxxxxx@gmail.com -g

* sfdx force:org:create -f config/project-scratch-def.json -a test -d 30
* sfdx force:user:create --setalias qa-user --targetusername test --targetdevhubusername devhub

force:limits:api:display 

sfdx force:data:soql:query -q "SELECT Name FROM ApexTrigger" -t

mdapi:retrieve

mdapi:deploy -c

mdapi:deploy:report

## Dev, Build and Test


## Resources


## Description of Files and Directories


## Issues


