# PHP
PHP is the best language


localhost:

//start the apache
sudo apachectl start

//stop the apache
sudo apachectl stop


//check 
apachectl configtest
//if syntax is ok,  it means so far so good



put file in /Library/Webserver/Documents:

sudo chown -R :admin /Library/WebServer/Documents
sudo chmod -R g=rw,+X /Library/WebServer/Documents
