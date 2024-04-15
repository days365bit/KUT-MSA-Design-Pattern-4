# KUT-MSA-Design-Pattern-4

### VirtualBox 

VBoxManage natnetwork add --netname natnet1 --network "192.168.15.0/24" --enable --dhcp off --port-forward-4 "ssh:tcp:[]:22:[192.168.15.101]:22"

VBoxManage setextradata global GUI/Input/HostKeyCombination 162,164

### Visual Studio Code

code --install-extension MS-CEINTL.vscode-language-pack-ko
code --install-extension ms-vscode-remote.remote-ssh
code --install-extension ms-azuretools.vscode-docker
code --install-extension vscjava.vscode-java-pack
code --install-extension vscjava.vscode-gradle
code --install-extension vscjava.vscode-maven
code --install-extension vmware.vscode-boot-dev-pack
