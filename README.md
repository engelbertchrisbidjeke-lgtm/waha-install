# waha-install
a pre installed waha docker container

## details
modify the .env files tu set up your own credentials

delete the media.txt (WAHA-INSATLL/media/media.txt) before doing anything
use `sudo rm WAHA-INSATLL/media/media.txt` the file can only be deleted as administrator, on Windows, open the command prompt or powershell as administrator using CRTL + X or right click on the Windows icon then select run termiale as administrator and go to the directory where the project is located and then run `del WAHA-INSATLL/media/media.txt`.

the, run the command `docker compose up -d` 
>> ensure that docker is installed

refaire to the official waha installation process:
- [Quick start](https://waha.devlike.pro/docs/overview/quick-start/)
- [Production ready installation with docker](https://waha.devlike.pro/blog/waha-on-docker/) 
>>note that docker is note the only way. 
