# Mini-Project-Linux-Fundamentals
#### This project provides a step-by-step guide for setting up and managing an AWS EC2 instance with a Linux (Ubuntu) operating system. It includes instructions on launching the instance, connecting via SSH using MobaXterm, executing basic Linux commands, and installing a web server with Nginx. Each stage is clearly explained and supported with screenshots for better understanding.
# Project Objectives
- Learn how to create and manage an AWS EC2 instance.

- Understand SSH connectivity using a key pair and MobaXterm.

- Perform basic Linux commands for package management and system configuration.

- Install, configure, and uninstall Nginx to host a simple web server.

- Demonstrate the ability to troubleshoot and verify configurations.

# Tools and Technologies
- **AWS EC2** Cloud computing service for launching virtual servers.

- **Ubuntu** Linux distribution used as the operating system for the EC2 instance.

- **MobaXterm** Terminal emulator for SSH connections to the EC2 instance.

- **Nginx** Lightweight web server for hosting a default webpage.

- **UFW** Uncomplicated Firewall for managing firewall rules.

- **Linux Commands** Tools like apt, tree, and systemctl for system management.

# Prerequisites
- An active AWS account with access to the AWS Management Console.

- MobaXterm (Home Edition) installed on your local machine.

- Basic understanding of Linux commands and SSH.

- A web browser to verify the Nginx webpage.

# Step-by-Step Instructions

# 1 Aws Creation

![1 Awscreation](https://github.com/user-attachments/assets/26c1582b-23ae-4b40-a765-03ee4062afc8)

# 2 Register

![2 Register](https://github.com/user-attachments/assets/e4480546-e311-4351-87ab-15d0aafca45b)

# 3 Aws sign In

![3 AwsSignIn](https://github.com/user-attachments/assets/1fb61446-645d-4f04-986e-b9988bdbd0af)

# 4 Aws console

![4 Awsconsole](https://github.com/user-attachments/assets/d8ac6fe9-5404-4ff6-9ac8-7610e4310815)

# 5 EC2

![5 EC2](https://github.com/user-attachments/assets/ffb8db5c-2cfa-4623-b7ac-bfb1d8dab92d)

# 6 Instances

![6 Instances](https://github.com/user-attachments/assets/d2b569d1-205b-4b17-b98d-bb77cb56dcac)

# 7 Lanch Instances

![7 LaunchInstances](https://github.com/user-attachments/assets/b462337c-e292-41ae-9328-15539067ef4b)

# 8 Name server and OS image

![8 NameServerAndOSImage](https://github.com/user-attachments/assets/02fc2f04-214f-4b7e-bea2-1e90c4df75df)

# 9 Machine image and instance type

![9 MachineImageAndInstanceType](https://github.com/user-attachments/assets/a539a111-12e3-4574-878d-f1ba104908c8)

# 10 Create and select key pair

![10 CreateAndSelectKeyPair](https://github.com/user-attachments/assets/4d12ed52-8102-4dfa-bdc3-c8bbb1934627)

# 11 Name Key Choose Encryption and download

![11 NameKeyChooseEncryptionAndDownload](https://github.com/user-attachments/assets/ea0f525f-075b-4e5b-8f59-9d41e6b83931)

# 12 Network and fire wall settings

![12 NetworkAndFirewallSetting](https://github.com/user-attachments/assets/3c11127c-cf6d-4f12-a54c-93e7fb5ba851)

# 13 Configure storage

![13 ConfigureStorage](https://github.com/user-attachments/assets/e6ad2dfb-797a-4602-9763-a08a778c73e5)

# 14 Initiated Launch of Instance and Connect

![14 InitiatedLaunchOfInstanceAndConnect](https://github.com/user-attachments/assets/30df5bb3-bf4a-48fd-ba74-65d38118206d)

# 15 Connections Parameters

![15 ConnectionsParameters](https://github.com/user-attachments/assets/56d67428-3b64-4c66-aa6f-a52b0d00c3b6)

# 16 Instance verification

![16 Instance verify](https://github.com/user-attachments/assets/5f76be29-3b5c-4a02-af30-091f095310dd)

# 17 Running the Instance Summary

![17 RunningInstanceSummary](https://github.com/user-attachments/assets/d1c22c05-5cb1-4f2a-b562-dc67c0fc1341)

# 18 Connecting Instance

![18 ConnectInstance](https://github.com/user-attachments/assets/cdc0ff8a-27cd-4eb9-9c01-b90845e39561)

# 19 MobaxTERM web page creation

![19 MobaxTermWebPage](https://github.com/user-attachments/assets/b5202ef2-3598-4be7-8029-347355541e11)

# 20 Downloading Mobaterm Web page

![20 DownloadingMobaxTermWebPage](https://github.com/user-attachments/assets/ed374b7b-3445-439e-8a67-d9f4daf325ea)

# 21 Mobaxterm Home Edition

![21 MobaXtermHomeEdition](https://github.com/user-attachments/assets/4c3477e0-5b3d-413c-9e30-4d8d186fb39d)

# 22 Launching Mobaxterm and starting Terminal

![22 LaunchMobaXtermAndStartTerminal](https://github.com/user-attachments/assets/1859764f-cac0-4fc3-a1aa-9d3f0abdfaf8)

# 23 Navigate To Key, pair and to location

![23 NavigateToKeyPairLocation](https://github.com/user-attachments/assets/78814479-9902-4d8e-bd33-09ba409eb8d3)

# 24 Extract the Instance Public IP

![24 ExtractingInstancePublicIP](https://github.com/user-attachments/assets/9b6fe897-f9ff-45db-952f-befec1588288)

# 25 running command to connect

![25 RunCommandToConnect](https://github.com/user-attachments/assets/53353145-0c7c-442b-8af0-0c029eefe7ef)

# 26 Check host name and update

![26 CheckHostNameAndUpdate](https://github.com/user-attachments/assets/ecb09b0b-b3ad-47aa-b7ed-c3fc12dada83

# 27 Sudo installing Tree

![27 SudoInstallTree](https://github.com/user-attachments/assets/280cd2c6-f063-4cb9-8a6d-4e3bdc651c36)

# 28 Sudo updating packages

![28 SudoUpdatePackages](https://github.com/user-attachments/assets/869a1b92-3e30-46c0-8ff3-8825a64a1290)

# 29 Remove Tree

![29 RemoveTree](https://github.com/user-attachments/assets/85a12d18-8ed3-453d-a9ea-3485bd8fb60b)

# 30 Installing Nginx

![30 InstallNginx](https://github.com/user-attachments/assets/47c81ec0-ac43-4a09-ae99-cf6f221413f4

# 31 Nginx 

![31 NginxAllowUFW](https://github.com/user-attachments/assets/3a0d026d-d51c-4341-bf98-7608ccc93245)

# 32 Start and enable Nginx

![32 StartAndEnableNginx](https://github.com/user-attachments/assets/c5c2a6f3-00bd-47fd-a346-aaa9c275e5c1)

# 33 Nginxs status check

![33 NginxStatusCheck](https://github.com/user-attachments/assets/8636eb1e-109f-4bb1-805d-14cdf2885ac9)

# 34 Unistalling Nginx

![34 UninstallNginx](https://github.com/user-attachments/assets/a5f19898-756a-4808-b059-8dc420c44943)











































