# UAC
UAC Installation Demo

UAC Installation (Ubuntu)

install wget or curl 
 >  sudo apt install wget
OR
 >  sudo apt install curl

use curl to download the latest release on the GitHub repository
> wget https://github.com/tclahr/uac/releases/download/v3.0.0/uac-3.0.0.tar.gz

After pulling the latest release uncompressed the file
> tar -xzf uac-3.0.0.tar.gz

Navigate to uncompressed directory
> cd uac-3.0.0

Execute the UAC with the desired profile and destination directory
./uac -p ir_triage /tmp



#Scenario 1 Downloading the UAC from standard profile to moving to root profile

Go to directory where you store the file from the repository (for example Downloads)
> cd
> cd Downloads

use curl to download the latest release on the GitHub repository
> wget https://github.com/tclahr/uac/releases/download/v3.0.0/uac-3.0.0.tar.gz

move the file to root
> sudo mv uac-3.0.0.tar.gz /root/

elevate access and go to root directory
> sudo -i
> tar -xzf uac-3.0.0.tar.gz
> cd uac-3.0.0.0
> ./uac -p ir_triage /tmp
