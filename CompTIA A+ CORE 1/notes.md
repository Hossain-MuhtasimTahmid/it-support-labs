# SECTION 1 
# (PRE-REQUISITES)
* Installed VirtualBox
 * Downloaded Windows 10 iso file and created a Windows 10 VM
 * Increased the base memory of the virtual machine to 4000MB and 4 CPU cores
 * Started the Windows 10 in VM, and updated Windows
 * Downloading Ubuntu ISO v24.04.3 on main Laptop
   * Opened VM and renamed VM to 'ubuntu' and ISO image I selected the newly installed 'ubuntu ISO', skipped unattended installation
   * There was an 'error' while starting ubuntu, so I went to the settings and changed the "Graphics controller" to a different one, and it worked.
  * Installing kali iso and 7 zip
  * Made another test VM and changed the 'Network Adapter' from "NAT" to "Bridged Adapter"--> will allow the VM to communicate with the host machine which is my main laptop.
  * Created a snapshot in kali linux and after it made a folder and a text file inside the kali linux and after that went back to create another snapshot. Then clicked on the first snapshot I created and restored- after turning on the kali linux again the previously made file was not there and it was sent back to its previous state.--> thats what snapshots are capable of.
<img width="960" height="564" alt="vmsnapshot" src="https://github.com/user-attachments/assets/16faee46-c38e-4b48-82b5-293d8d30f330" />
