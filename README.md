# Java_Screenshare
A simple program that allows Screenshare between two Devices

Only testet with java 17.

Server (Receives screen):
java -jar -s -p \<port\>

Client (Shares screen):
java -jar -c -a \<ip\> -p \<port\>

I used TCP because my marihuana consumption fucked up my brain so badly, that I haven't been able to implement it in UDP.
(Would be nice when someone could explain this to me!)
