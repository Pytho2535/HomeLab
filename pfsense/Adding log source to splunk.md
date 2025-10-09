## Forwarding pfsense logs to Splunk
To forward logs from pfsense to Splunk we need to go to the Splunk's settings inside our webpage.

### Click `Settings -> Data inputs -> UDP -> Add new`, Then type your port and click Next 
<img width="1131" height="653" alt="image" src="https://github.com/user-attachments/assets/3780877d-d2e7-481e-a34e-8949d0226eaf" />

### Now you will need to click `New` and type your name for Source Type
<img width="870" height="349" alt="image" src="https://github.com/user-attachments/assets/0bb1b3e3-6f3d-44ab-8eb0-3c85053fed3e" />

### After that you scroll down and click `Create new index` you can name it also however you want
<img width="779" height="158" alt="image" src="https://github.com/user-attachments/assets/595f25ae-3370-409e-9b14-6d36402f5c55" />


## Thats it for the Splunk, now go to the pfsense
### Go to the `Status/System Logs/Settings` and on the bottom enable `Enable Remote Logging`
<img width="415" height="62" alt="image" src="https://github.com/user-attachments/assets/6400b3ea-2d5e-44e0-be43-2d35b7356f5c" />

### Lastly type the IP Address of your Splunk Server Machine, use the port that you set up earlier and check what type of logs do you want
<img width="927" height="589" alt="image" src="https://github.com/user-attachments/assets/3b081ac9-a9ae-40d1-b51c-ace4ec191170" />
