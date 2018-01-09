
# SFDX  App


- Login Saleforce Developer Experience

	sfdx force:auth:web:login -d -a DevHub

- Open Saleforce Scrach

	sfdx force:org:open -u DevHub
	
	sfdx force:org:open -u GeoAppScratch

- List alias and Scrach Orgs

	sfdx force:org:list

- Create New Project

	sfdx force:project:create -n <project name>

- Create a scratch org with the alias GeoAppScratch

	sfdx force:org:create -s -f config/project-scratch-def.json -a GeoAppScratch
	
	sfdx force:org:create -s -f config/project-scratch-def.json -a DocStorageScratch

- assign this permission set to  user

	sfdx force:user:permset:assign -n Geolocation

- Check in to GIT

	git init
	
	git remote add origin <github https url>

## Dev, Build and Test


## Resources


## Description of Files and Directories


## Issues



