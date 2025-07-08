# DNS-server
A project to create a dns server to be able to send emails using SMTP, POP3 and IMAP
I was tasked with the project of creating a dns server that faciliatate the sending of emails using the SMTP, POP3 AND IMAP protocol
1. Install the dns dependency with this command: sudo apt-get install bind9.
2. Added IP Address and domain name to the Ubuntu host files.
3. Configure the config files of the bind9 where I added the zone files, the forwarder, the reverse lookup and also the domain names.
4. I also proceeded to download the email protocol using this command: sudo apt-get install imapd pop3 smtp
5. I then installed the postfix, which I also configured the config files.
6. Then i proceeded to install the apache server which is needed for the web server.
7. The squirrelmail was also downloaded from github then the config file was moved into the apache server in order to be hosted on the apache server.
8. Then the project was tested using several account created and also used to send the mail.
