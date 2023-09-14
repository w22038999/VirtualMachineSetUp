Task: Please create documentation for virtual box and Ubuntu setup. You can always refer to a like to website or video.
Also, document the commands run to install Git, etc,
9:58
Also, document the how you resolve the apt update issue.
9:58
We can reuse for other people facing similar issues in the future.

**Oracle Virtual Box and Ubuntu Set up**

Oracle Virtual Box is an example of a type 2 Hypervisor that makes virtualization possible .It cannot stand alone and need a pre existing operating system to function

### SET-UP FOR VIRTUAL BOX

We would be downloading VirtualBox 7.0.10 platform package
Navigate to the website :

https://www.virtualbox.org/

Download and install the virtual box

![2023-09-14 20_40_53-Oracle VM VirtualBox Manager](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/f19e9805-a92e-4db8-9329-f1a98437a886)


#### SET-UP FOR UBUNTU 23.04

The next step is to download Ubuntu disk image on the website .Please ensure you download the 22.04 LTS version because its a stable version
https://ubuntu.com/download/desktop

![2023-09-14 20_40_53-Oracle VM VirtualBox Manager](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/16560cf6-87ed-42fd-ba31-685b4d7379d1)


Once downloaded proceed to launch Virtual Box and create a new Virtual Machine and Operating system as shown below

Create name is lower case
Select ISO image and locate where your UBUNTU DISK IMAGE is located as shown below
Choose Linux as the type and Version should be Ubuntu 64 bits
Select "Skip unattended installation "
Click the Next button

Please note : The bits depends on the laptop you use.

![2023-09-14 20_51_52-Oracle VM VirtualBox Manager](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/7a488e83-2f62-4b4f-b267-b5a4b0f7b954)


In the hardware section leave the default base memory and Processors
Click NEXT and wait for full installation

![2023-09-14 20_53_12-Create Virtual Machine](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/27c9ecd6-4806-4bc9-9b35-ee54efbb05df)


Virtual Hard disk section (Select between 20-25 GB)
Click Next and Click Finish

![2023-09-14 20_54_40-Oracle VM VirtualBox Manager](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/2b3f9c4c-2f96-49cc-8fbc-bd492dee30bf)

![2023-09-14 20_55_45-Create Virtual Machine](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/d42a9396-a25b-4bf2-8a6c-5cc5a94fa511)


Once done you would see the virtual machine on the left hand side .By default powered off

Power it on and let it come up
![2023-09-14 20_59_11-devops  Running  - Oracle VM VirtualBox](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/b7854f8b-3e38-4851-8bac-0b774b75b678)


It would take a while to come up but follow the instructions

Sign in with the password created and see your GUI Ubuntu successfully launched and download necessary tools

![2023-09-14 21_00_26-devops  Running  - Oracle VM VirtualBox](https://github.com/w22038999/VirtualMachineSetUp/assets/141069152/b4992ef6-f4d9-4d13-9aa8-356a5cb74fb5)

