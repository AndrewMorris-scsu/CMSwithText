# csci.club Website Application
I. Info

This project was a product of the carlHacks hackathon. We configured and designed a website that has the ability to send text notifications to users when new content is pushed to the site. The admin page lets users with an admin account post news and updates. When these updates are published, the Twilio api is utilized to send a text to users that are subscribed to recieve text messages. This repo was created for the submission only, all the commits and history of the project can be fount at `https://github.com/CSCIClub/csci.club` 

II. Setup

Download the source code and import the createUser.sql with myphpadmin from /sql directory into the MySql database.

Change the `DBUSER`, `DBPASS` in  /includes/config.php as required and also change path define urls for `Dir`, `AdminDir` and `SiteTitle` if required!!
