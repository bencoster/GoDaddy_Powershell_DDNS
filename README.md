# GoDaddy_Powershell_DDNS
Simple script to check and update a Godaddy domain with your public ip address from you internet provider


You will need a GoDaddy developer account.
Go to GoDaddy developer site to create a developer account and get your key and secret

https://developer.godaddy.com/getstarted

Notes:
Unfortunately the key and secret I got was for the test server and not the production server. If you are going to test the script please get your self a production key and secret. 
I've used mfox's ps script to produce a bash script that will run on a linux server. You can create a cron job to run every hour to check. 
