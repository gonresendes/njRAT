# njRAT

## PREREQUISITS
- An attacker machine(Preferencly a Windows 10 machine)
- A Victim machine
- Disable the anti-virus in both machines

## Installing njRAT    
- Click in the link below and follow the installation steps:
- https://github.com/simalei/njRAT

## Deploying njRAT
- Before you start, make sure you disable anti-virus in both machines;
- Extract the files into a folder
- double click in the .exe file
- Choose port 5552
- Click on the "Builder" Botton
- Insert the IP address of the sender machine
- Make sure you use the correct port that you placed in steps above
- Select "Copy to StartUp" and "Registy StartUp"
- Select "Copy" and make sure the name is "server.exe" and the directory is pointed to the "%TEMP%" path
- Click on the Build botton
- Rename the file and place it into a folder

## Sharing the Trojan
- To share the file I used a share folder named "sharepoint" that can I access directly in the victim machine, because they are in the same subnet
- Copy the file .exe that you build and copy to the "sharepoint"
- In the victim machine, make sure you disabled the real-time protection in windows security, then you can place the .exe file to you desktop
  

## Start the trojan
- Double-click in the file and should apper a warning screen, you click in "more info" and "run anyway"
- It should apper nothing, and the trojan is already running.

- https://github.com/0xPh0enix/njCrypter
