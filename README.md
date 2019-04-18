# SFDX  App
* sfdx force:auth:web:login
* sfdx force:config:set defaultdevhubusername=xxxxxx@gmail.com -g

* sfdx force:org:create -f config/project-scratch-def.json -a test -d 30
* sfdx force:user:create --setalias qa-user --targetusername test --targetdevhubusername devhub


force:org:open

mdapi:retrieve

mdapi:deploy -c

mdapi:deploy:report


sfdx force:data:soql:query -q "SELECT Name FROM ApexTrigger" -t

sfdx force:apex:log:tail

force:limits:api:display 
schema:sobject:describe | grep > temp/out.json - cmd shift f

## Dev, Build and Test


## Resources


## Description of Files and Directories


## Issues


