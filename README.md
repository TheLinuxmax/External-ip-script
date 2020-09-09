# External-ip-script
This gets your external ip and puts it in ipnew.txt. 
Then its going to compare the new and old.txt. If its the same it removes ipnew.txt (because we create it again) 
If its not the same its going to mail me the ipnew.txt and remove both files. 
Then its gonne setup the new ip to the ipold.txt. 

I integrated it on crontab to run every 15 min.
