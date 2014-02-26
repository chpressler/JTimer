Readme:

- executable jar file

- to work under MacOS X or Linux you have to edit: /etc/sudoers 
by adding the following lines: 

%users localhost=/sbin/shutdown -h now
%users localhost=NOPASSWD: /sbin/shutdown


enjoy