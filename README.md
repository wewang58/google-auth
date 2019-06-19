Before executing the script, should register in https://console.developers.google.com/ first, and get clientsecret, clientid value 

How to use the script(notes:clientsecret and clientid should replace with real value): 

openid config command:   sh google-auth.sh openid clientsecret clientid 

oauth2 config command:   sh google-auth.sh oauth2 clientsecret clientid

htpasswd config command: sh google-auth.sh  htpasswd 

Example:

sh google-auth.sh openid  xxx    xxxx.googleusercontent.com

sh google-auth.sh oauth2  xxx    xxxx.googleusercontent.com

sh google-auth.sh htpasswd

