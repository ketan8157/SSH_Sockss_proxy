# SSH_Sockss_proxy
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --user-data-dir="%USERPROFILE%\proxy-profile" --proxy-server="socks5://localhost:9090"
ssh -i key user@ip -N -D 9090
#time take to create a connection to get output from a website
curl -s -o /dev/null -w "%{time_total}\n" http://ip 
