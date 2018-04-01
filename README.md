# chocolately-java-developer-setup
Installs a set of tools useful for developers building Java application using the [Chocolately](https://chocolatey.org/) package manager to install tools on Windows.

# Installing the tools without cloning repo
The first step is installing Chocolatey, open a command prompt as an administrator.  Run this command ```@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"```  
from the [Chocolately Install](https://chocolatey.org/install) page.  Now you can install any [Chocolately Package](https://chocolatey.org/packages).  To Install:  
* JDK8
* Maven
* Git
* Visual Studio Code
* Azure CLI
* Docker For Windows
* Kubernetes CLI  
Run this command  
```cinst jdk8 maven git visualstudiocode azure-cli docker docker-for-windows kubernetes-cli -y```


# Install tools by running the scripts after cloning repo
If you can clone this repo then you can use the scripts, power shell and cmd scripts are in the scripts folder to install the same tools.

# Note on Docker
Depending on the state of your machine Docker for Windows requires you to logout and log back in again then it will request you reboot.  Once that's done you should 



