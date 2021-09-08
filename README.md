# VoIP
One Server and multiple clients connected to the server talking using SIP Protocol. Asterisk has been used.

Please follow the steps given in install-asterisk.sh file

After that,

"module load chan_sip.so"

if it is already running then give "reload" command

then,

"sip show peers" for seeing the connected numbers and the users associated with it

For UI Client -

Use MicroSip for desktop and Linphone for android

Give number, password and the Public IP of Server
