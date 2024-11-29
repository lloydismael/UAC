# UAC
UAC Installation Demo

UAC Installation (Ubuntu)

install wget or curl first
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
