### TempSpeak

Needed to run this project:

 - Install ThingSpeak on localhost, see: https://github.com/iobridge/thingspeak/blob/master/README.textile
 - Before step "bundle install", you need to install "gem install bundler"
 - Don't forget to change password of mySQL-server after "cp config/database.yml.example config/database.yml"

First test
 - After installing ThingSpeak and ruby server started, you can try ThingSpeak on locahost
  - connect to localhost:3000
  - Create new channel, with field 
  - Go to "Data Import/Export" page and copy url under "Sending Data" (with API-Key inside
  - Go to bash, type 'curl "copied-url"' and see if the value is insterted in the Chart 
