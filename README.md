# sipp-uac-built
This repo contains an xml file for sipp utility to do stress testing.
File name is uac-built.xml

command to run 
sipp -sf /home/uac-built.xml 115.0.9.105:5060 -r 10 -s 04232300500 -l 150


sipp - bin
-sf - file path
115.0.9.105:5060 - [remote_ip]:[remote_port]
04232300500 - service

-r  calls per second
-l   total call limit



# register.xml
sipp -sf register.xml remote_ip:5060 -r 10 -l 10
