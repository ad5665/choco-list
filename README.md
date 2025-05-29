# choco-list

## install choco, runas admin
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

### Coding stuff
choco install flow-launcher -y

choco install floorp -y

#choco install python3 -y 

choco install notepadplusplus.install -y 

choco install 7zip.install -y 

#choco install firefox -y 

choco install git.install -y 

choco install vscode -y 

#choco install awscli -y 

#choco install winscp.install -y 

choco install keepass.install -y 

choco install powertoys -y 

#choco install azure-cli -y 

choco install procexp -y 

#choco install postman -y 

choco install crystaldiskinfo -y 

choco install crystaldiskmark -y

#choco install terraform -y 

#choco install kubernetes-cli -y 

#choco install docker-desktop -y 

choco install rancher-desktop -y

choco install procmon -y 

#choco install docker-compose -y 

#choco install oh-my-posh -y 

#choco install vscode-powershell -y 

choco install obsidian -y 

#choco install k9s -y 

#choco install github-desktop -y 

#choco install mremoteng -y 

#choco install openlens -y 

#choco install kubernetes-helm -y 

#choco install minikube -y 

#choco install jq -y 


### Media/Other
choco install spotify -y 

choco install sharex -y 

choco install windirstat -y 

choco install vlc -y 

choco install googledrive -y 

choco install musicbee -y 

choco install rufus -y 

#choco install signal -y 

#choco install etcher -y 

#choco install gopro-quik -y

#choco install garmin-express -y

choco install syncthingtray -y


### Games
choco install discord -y 

choco install epicgameslauncher -y --ignore-checksums

choco install ea-app -y --ignore-checksums

choco install ubisoft-connect -y --ignore-checksums

choco install steam-client -y 

choco install goggalaxy -y


### Update all Apps
#cup all
# choco upgrade all --except=[appname]"


### Pins for AutoUpdate apps
choco pin add -n="floorp"

choco pin add -n=obsidian

choco pin add -n=vscode

choco pin add -n="vscode-powershell"

choco pin add -n="powertoys"

choco pin add -n="openlens"

choco pin add -n="notepadplusplus.install"

choco pin add -n="docker-desktop"

choco pin add -n="dotnet-desktopruntime"

choco pin add -n="dotnet-7.0-desktopruntime"

choco pin add -n="goggalaxy"


### Pin Media/Other
choco pin add -n="spotify"

choco pin add -n="sharex"

choco pin add -n="googledrive"

choco pin add -n="gopro-quik"

choco pin add -n="garmin-express"



### Pin Games
choco pin add -n="ubisoft-connect"

choco pin add -n="steam-client"

choco pin add -n="ea-app"

choco pin add -n="discord"

choco pin add -n="epicgameslauncher"
