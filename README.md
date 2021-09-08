# VoIP Calling (Skype Lite)
One Server and multiple clients connected to the server, talking using SIP Protocol. Asterisk has been used which is running on port 5060.

Machine Used for Server - Ubuntu 20.04 on EC2 (Free Tier - t2.micro)

Security Setting - All TCP Inbound and UDP Inbound Ports are open for all.  (Not a good practice and server will down in few minutes because of lots of requests by hackers. Try for a small time period and then restrict the security setting for own IP only)

Please follow the steps given in install-asterisk.sh file

After that,

"module load chan_sip.so"

if it is already running then give "reload" command

then,

"sip show peers" for seeing the connected numbers and the users associated with it

For UI Client -

Use MicroSip for desktop and Linphone for android

Give number, password and the Public IP of Server
