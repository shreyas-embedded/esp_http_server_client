# ESP HTTP Client Example

ESP HTTP Client Example: It will connect to server and receive the files.

POINTS TO BE NOTED:
please set the path 
Feed the Wifi SSID and Pasword using make menuconfig->example application configuration.
USE make flash command to build and flash the code.

Before connecting the client switch on the server and make changes of IP address in esp_http_client.c in get handler to connect with server address.

initially after starting a server you can add files using /upload/* link using web UI.
Later files can be shared using server client communication.





