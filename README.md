# MonsterCode
Simple CRUD
Download the projects in the Git-hub:
https://github.com/ericquesada27/MonsterCode
or
https://github.com/ericquesada27/MonsterCode.git

Uncompress only the CRUD project diapers.rar
The other monsters.zip project has no need to unpack because it will use an IDE
with virtual machine already configured with these source codes.

To start boot Node.js with Mongodb

Access the Cloud9 IDE:
https://ide.c9.io/headshotarts/monsters

Sign in to Cloud9:
user: headshotarts@gmail.com
pass: MonsterCode

You will be taken to the workspace: monsters / monsters

Note that you have 3 upper flaps and 3 lower flaps already configured.

Click the bottom tab of the middle (bash ubuntu) terminal and type:
mongod --bind_ip = $ IP --nojournal
press enter
Note: If you are writing, just press enter

Click the last bottom tab of the other terminal (bash ubuntu) and type:
Mongo
press enter
Note: If you are writing, just press enter

Still on the last bottom tab to access the NOSQL database and type:
use diapersdb
press enter

Click the first lower tab of api.js -Idle and click the Run button.
Ready the application is running! Leave the browser minimized!

Go to the CRUD project and click on the index.html file and register the desired diaper with model, description, size, amount evaluated, quantities purchased).
Note: The quantity evaluated is what is available in the inventory and must be greater than the amount purchased, since both are registered together and I did not
the comparison treatment in the field.

Click Register / Update.
The buttons will be created (edit, submit, delete and buy)

Click Buy, and then click Submit.
Note: When you click POST the information will be sent to the webservices and will be written to the NOSQL database.

To check if the data has been registered go to the Cloud9 IDE on the third and last lower tab type:
db.perfil.find ()

Registration has been successfully inserted!

After this exit the cloud9 IDE:
 Click on the third tab press CTRL C,
 Click on the second tab press CTRL C,
 Click on the first tab press the STOP button to end the api.js

Informative:
Workspace openings (including access to databases and application structures) will be disabled on June 30, 2019. Cloud9 will stop working on December 31, 2019.
