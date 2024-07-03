# njRAT

## PREREQUISITES
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
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/8d727f95-8030-4623-a89a-c341c2e5cf64)

- Click on the "Builder" Botton
- Insert the IP address of the sender machine
- Make sure you use the correct port that you placed in steps above
- Select "Copy to StartUp" and "Registy StartUp"
- Select "Copy" and make sure the name is "server.exe" and the directory is pointed to the "%TEMP%" path
- Click on the Build botton
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/dbc3427a-3eba-4709-861d-11365d39c3c8)

- Rename the file and place it into a folder

## Sharing the Trojan
- To share the file I used a share folder named "sharepoint" that can I access directly in the victim machine, because they are in the same subnet
- Copy the file .exe that you build and copy to the "sharepoint"
- In the victim machine, make sure you disabled the real-time protection in windows security, then you can place the .exe file to you desktop
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/4deaaa68-fd51-4d4b-9720-7109c06e3abd)


## Start the trojan
- Double-click in the file and should apper a warning screen, you click in "more info" and "run anyway"
- It should apper nothing, and the trojan is already running.

## njCrypter
-Installation steps:
-Follow the link bellow and follow the intallation steps:
- https://github.com/0xPh0enix/njCrypter
- Run as administrator
- Choose the path location of the trojan and an icon to hide 
- Click on create
- Your file is ready to use
  
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/fd91f609-dd0e-4da7-a429-96b85d29ee98)


## Test your both files
- Use https://www.virustotal.com/gui/home/upload to test your files
  
- Test with original file
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/96025737-46d0-4a00-abc9-c3bfbf3838da)

- Test with crypted file
  ![image](https://github.com/gonresendes/njRAT/assets/145346794/3d094e1b-8249-43a7-900a-67a3d2a39588)


