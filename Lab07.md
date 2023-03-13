## Lab 07

- Name: Isabella Livingston
- Email: livingston.70@wright.edu

## Part 1 Answers

1. Download an ISO:
    - Linux distribution: Ubuntu 22.10
    - URL to download it: https://ubuntu.com/download/desktop
2. Virtual Machine configurations:
    - RAM - 1024MB
    - CPU - 1
    - Disk size - 10.00GB

![Screenshot of Summary](relative_path_to_image_filename_here):  Should be included in GitHub: Lab07

3. Install Guest OS:
    - Start installation: Try or Install Ubuntu > Install Ubuntu > Continue > Continue > Install Now
    - Disk to install to: The Virtual Machine
    - Partition size: 
    - Partition filesystem: Ext4 
4. Remove installation media:
    - How to remove: Make sure the VM is set to boot the hard disk that has Ubuntu then restart
    - How to verify: After checking, and the screen says "Remove installation medium and press ENTER"  you can press enter to verify
5. Guest Additions:
    - How to insert Guest Additions: (In VM) Devices > Insert Guest Additions CD image
    - How to run the Guest Additions installer for your Guest Operating System:
    - How to change resolution of the VM: Log into VM > Settings Application > Displays > Resolution
6. VM Control:
    - Turning on the VM: Virtual Box > Select VM to Run > Start
    - Turning off the VM: Select the "X" in the top right corner of the VM > Save the machine state OR Power off the machine
    - Restarting the VM: Power off the machine OR Select Power button > Restart
7. Proof of your VM running your Guest OS:

![Screenshot with name in file](relative_path_to_image_filename_here): Should be included in GitHub: Lab07


## Part 2 Answers

1. How to change your desktop background in your VM: Log into VM > Settings Application > Appearance
2. How to install VSCode in your VM: Ubuntu Software > Search "VSCode" > Click Install
3. How to connect to your AWS instance from your VM using `ssh`: ssh -i labsuser.pem ubuntu@34.228.33.69
