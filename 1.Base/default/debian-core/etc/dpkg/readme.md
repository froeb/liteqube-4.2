This config file changes the type of logging for dpkg from

#log /var/log/dpkg.log

to

status-logger "/usr/bin/logger -t dpkg -p info"
