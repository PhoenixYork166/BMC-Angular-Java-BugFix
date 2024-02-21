# BMC Helix Fullstack development guide
##
## BMC Helix dev code base
# Frontend and Midtier dev
![BMC Helix](https://i.ytimg.com/vi/rjjiLZgRU5Q/maxresdefault.jpg)
##
![BMC Helix攞你命3000](https://www.property.hk/writing_manage/article_images/phk_tml/e131c09d04db55a9121f05a0075baf5b.jpg)
##
## Intro:
## Swapping from React's Functional Programming paradigm to Angular Object Oriented Programming paradigm
## will be SO FUN!! :D
##
## Hello user
## To use this lib straight ahead
## git clone <thisRepo>
## cd projectFolder
## sudo vim projectFolder/pom.xml
## 2. Edit developerName on line 12
![developerName](https://scontent.fhkg4-1.fna.fbcdn.net/v/t39.30808-6/416090034_10160848900003604_9200986974798904940_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=3635dc&_nc_ohc=09xvgL28pskAX_v26ag&_nc_ht=scontent.fhkg4-1.fna&oh=00_AfAaW46sos6PU91BWZXdi5CuvGe9U2PpU5sBXrS-4Cr-5A&oe=6597E68C)
## 3. Edit developerPassword on line 13
![developerPassword](https://scontent.fhkg4-1.fna.fbcdn.net/v/t39.30808-6/416082004_10160848900333604_6567304524044656725_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=3635dc&_nc_ohc=odry1V2n3kcAX8UBA_F&_nc_ht=scontent.fhkg4-1.fna&oh=00_AfA4pPrvY3_cy7XvelUZUpBOQNeBSNeG-o_yPy6XqyEIcw&oe=65983F44)
## 4. Edit API server url on line 15
![development API server](https://scontent.fhkg4-2.fna.fbcdn.net/v/t39.30808-6/416095627_10160848901033604_8327992667750738361_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=3635dc&_nc_ohc=bzqq8ONajswAX-3jLni&_nc_ht=scontent.fhkg4-2.fna&oh=00_AfBYb0cbe_kRZa19CY8k2ejsO8pRTzBze7jfXzI5t3TjFQ&oe=65967446)
## 5. Enable openssl-legacy-provider & start deploying with SSL security risks :D
## powershell: 
## $env:NODE_OPTIONS="--openssl-legacy-provider"; mvn clean install -Pexport -Pdeploy;
## Bash: 
## export node_options= --openssl-legacy-provider && mvn clean install -Pexport -Pdeploy;

## Or luck it out by:
## mvn clean install -Pexport -Pdeploy

## For upgrading your existing BMC Helix open sdk from 21.X to 22.7.01 
## Please refer to 
## https://docs.bmc.com/docs/is221/upgrading-bmc-helix-innovation-studio-sdk-to-22-1-00-1039588344.html
## Should you find any problems during debugging (done in Nov 2023), please refer to 
## projectFolder/Helix-guide.one
## To open projectFolder/Helix-guide.one
## Open OneNote.exe => Open => select all file extension => Helix-guide.one

## For development environment setup
## Please refer to === Dev dependencies section
## 'Java JDK' page
## Node.js 20
## 'Maven (3.6.3)' page
## 'Eclipse IDE' page
## 'BMC Helix Platform SDK' page
## 'Install Node (up-to-date)' page
## 'Yarn 1.22.21' page
## 'Install Grunt' page
## 'Env layout' page
## 'node-sass@^4.14.0' is deprecated
## Use Sass instead

## For Innovation Studio Login, please refer to 'Studio Login' page 
## under ==== Reviving Angular lib section

## For installation of local development sandbox
## Please refer to 'Local sandbox server' page 
## under ==== Reviving Angular lib section

## For reviving Angular library
## Please refer to '1. Angular Library revival' page
## Please refer to '2. BMC SDK upgrade' page
## Please refer to '3. Troubleshooting Yarn' page

## If there's any difficulties
## Please refer to _guides => _upgrade => UPGRADE.MD
## Please refer to _guides => _upgrade => BREAKING_CHANGES.MD
## Read thoroughly this doc and debug
