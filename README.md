# choco-list

### Coding stuff
choco install python3 -y

choco install notepadplusplus.install -y
choco install 7zip.install -y
choco install firefox -y
choco install git.install -y
choco install vscode -y
choco install awscli -y
choco install winscp.install -y
choco install keepass.install -y
choco install powertoys -y
choco install azure-cli -y
choco install procexp -y
choco install postman -y
choco install crystaldiskinfo -y
choco install terraform -y
choco install kubernetes-cli -y
choco install docker-desktop -y
choco install procmon -y
choco install docker-compose -y
choco install oh-my-posh -y
choco install vscode-powershell -y
choco install obsidian -y
choco install k9s -y
choco install github-desktop -y
choco install mremoteng -y
choco install openlens -y
choco install kubernetes-helm -y
choco install minikube -y
choco install jq -y

### Media/Other
choco install spotify -y
choco install sharex -y
choco install windirstat -y
choco install vlc -y
choco install googledrive -y
choco install musicbee -y
choco install rufus -y
choco install signal -y
choco install etcher -y

### Games
choco install discord -y
choco install epicgameslauncher -y
choco install ea-app -y
choco install ubisoft-connect -y
choco install steam-client -y

### Update all Apps
#cup all
# choco upgrade all --except=[appname]"

### Pins for AutoUpdate apps
choco pin add -n="Firefox"
choco pin add -n=obsidian
choco pin add -n=vscode
choco pin add -n="vscode-powershell"
choco pin add -n="powertoys"
choco pin add -n="openlens"
choco pin add -n="notepadplusplus.install"
choco pin add -n="docker-desktop"
choco pin add -n="dotnet-desktopruntime"
choco pin add -n="dotnet-7.0-desktopruntime"

### Pin Media/Other
choco pin add -n="spotify"
choco pin add -n="sharex"
choco pin add -n="googledrive"

### Pin Games
choco pin add -n="ubisoft-connect"
choco pin add -n="steam-client"
choco pin add -n="ea-app"
choco pin add -n="discord"
choco pin add -n="epicgameslauncher"
