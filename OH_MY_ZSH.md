Follow the below steps to use Oh My Zsh terminal on Windows and VS Code.

1 - Activate Windows for Linux Subsystem , run this command on powershell ``` dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart ```

2 - Restart the system.

3 - Now install a linux distribution. Ubuntu 20.04 LTS is preferred .
```https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab```

4 - Now open the Ubuntu terminal and run the following commands one by one : 
```sudo apt-get update```
```sudo apt-get install zsh -y```

5 - Now install curl to install oh my zsh , run this command on ubuntu terminal ```sudo apt-get install curl```

6 - Run this now ```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

7 - Now you will be in oh my zsh terminal.

8 - Run this now ```git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k```

9 - Now run ```code ~/.zshrc``` , this will open vscode , search for ZSH_THEME and then replace  ZSH_THEME=”robbyrussel” with ZSH_THEME=”powerlevel10k/powerlevel10k”

10 - Now close the terminal.

11 - Search and download DroidSansMono Nerd Font from ```https://www.nerdfonts.com/font-downloads```. After downloading, extract the fonts and then install them.

12 - Now install Windows terminal from microsoft store ```https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701```

13 - Open it, and select Ubuntu 20.04 , you will something like this :  

14 - Now open the settings of windows terminal, it is json file, so open it with any text editor and add the following in the Ubuntu section of the list : 
        "fontFace": "DroidSansMono Nerd Font"


