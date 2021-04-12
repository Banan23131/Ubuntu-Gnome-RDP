# Ubuntu-Gnome-RDP
Yes, Ubuntu 20.04 Remote Desktop Protocol with Gnome GUI hosted on Github Actions.
Just fork, go to settings > Secrets: Add new secrets type 'NGROK_AUTH_TOKEN' (Uppercase, splitted by '_', exactly as i typed) and paste your ngrok authtoken as the value, now go to actions, confirm, select 'Ubuntu-VM', click run workflow put the password for VNC Server you want and confirm, refresh, click the 'Ubuntu-VM' stuff with yellow circle, click build and wait the 'Creatting Tunnel' thing be yellow, go to Ngrok's dashboard to get the ip (number.tcp.ngrok.io:numbernumbermhiehejedrnumber (some many numbers (5 i think))) and finally, simple connect to the ip on VNC Viewer with the password you selected (123456 by defaul.

Or just put your authtoken on secrets and run 'Ubuntu-VM' then get the ip at ngrok's dashboard and connect with the password you choosed
