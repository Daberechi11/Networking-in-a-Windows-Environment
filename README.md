# Networking-in-a-Windows-Environment
Virtual Lab 6-1, Guided: Deploy Windows Server Core
Description: In this Virtual Lab, you will deploy Windows Server Core. First, you will install Windows Server Core. Next, you will configure Server Core. Finally, you will join a server running Server Core to an Active Directory® domain

<img width="1523" height="911" alt="image" src="https://github.com/user-attachments/assets/e4a5d89b-8894-4a47-ab03-e808d495be15" />
Install Windows Server 2025 Datacenter Evaluation on Disk 0.

<img width="1522" height="904" alt="image" src="https://github.com/user-attachments/assets/8ca8c3fa-38cf-46c4-8f5b-5ebdd9fce7db" />

<img width="1523" height="905" alt="image" src="https://github.com/user-attachments/assets/c7000366-8785-4905-abc9-2b2a218300e4" />

<img width="1524" height="914" alt="image" src="https://github.com/user-attachments/assets/176cc5db-defb-42e4-beb0-bf101cd6f0f0" />
Select image page, select Windows Server 2025 Datacenter Evaluation,

<img width="1521" height="909" alt="image" src="https://github.com/user-attachments/assets/619ed707-75fd-48f1-8861-212d4945cd8f" />
Select location to install Windows Server page, ensure that Disk 0 Unallocated space is selected, and then select Next.

<img width="1523" height="910" alt="image" src="https://github.com/user-attachments/assets/12105e9c-93f9-4c4d-bfdf-e42c25faeebb" />

<img width="1522" height="904" alt="image" src="https://github.com/user-attachments/assets/a567210e-f89c-4aa3-82f9-3413e399e1db" />
The I change the new local Administrator password to Passw0rd!, when prompted.

<img width="1519" height="907" alt="image" src="https://github.com/user-attachments/assets/630d2f8b-0655-474f-9f75-920fcbf9d30e" />

<img width="1519" height="904" alt="image" src="https://github.com/user-attachments/assets/53d6ba25-6e1e-4bad-89c2-49973abdbf16" />
Accept the default setting by pressing Enter when prompted to Send Diagnostic data to Microsoft.

<img width="1523" height="910" alt="image" src="https://github.com/user-attachments/assets/d4244ccc-42e8-40cc-bff7-0b27e2505aab" />

<img width="1522" height="908" alt="image" src="https://github.com/user-attachments/assets/8dd19fc9-9348-4db6-a2db-fe8a000335c6" />

<img width="1521" height="913" alt="image" src="https://github.com/user-attachments/assets/b161edd0-cfb5-4c29-be50-adca94255708" />

<img width="1521" height="908" alt="image" src="https://github.com/user-attachments/assets/72cfc7f9-4cf6-447b-8a98-548e472c2d5d" />
Configure a static IP address by using the IP address 192.168.10.41, the default subnet mask, and the gateway IP address 192.168.10.1.

<img width="1517" height="901" alt="image" src="https://github.com/user-attachments/assets/c0ce8b6e-90b9-4a27-b904-deb0f6002854" />
Enter the displayed network adapter number 4 to select the Ethernet network adapter-this number can vary.

<img width="1522" height="913" alt="image" src="https://github.com/user-attachments/assets/be22b421-e109-422b-a47d-4bf18dbe5c87" />
Enter 1 to Set network adapter address.

<img width="1521" height="908" alt="image" src="https://github.com/user-attachments/assets/1e6cae63-1354-481a-936a-e85af0be07de" />

<img width="1525" height="916" alt="image" src="https://github.com/user-attachments/assets/6e3e1746-ad31-4712-aada-7245303a252e" />
Enter static IP address, enter 192.168.10.41. Enter subnet mask, press Enter to use the default subnet mask value of 255.255.255.0.
In Enter default gateway, enter 192.168.10.1.

<img width="1523" height="902" alt="image" src="https://github.com/user-attachments/assets/2ed34e81-9521-421b-ac60-f88245aa7998" />

<img width="1524" height="895" alt="image" src="https://github.com/user-attachments/assets/9c0b65b6-73e0-42c2-86e4-46670ada86f1" />

<img width="1521" height="906" alt="image" src="https://github.com/user-attachments/assets/49a40ff2-f5d2-4601-a6a8-4fef8a8ead87" />
Configure a first DNS server by using 192.168.10.10 as the IP address-you do not need to configure a 2nd or 3rd DNS server.
In Enter 1st DNS server, enter 192.168.10.10.In Enter 2nd DNS server, press Enter to leave the selection blank.
In Enter 3rd DNS server, press Enter to leave the selection blank.


<img width="1521" height="912" alt="image" src="https://github.com/user-attachments/assets/08267739-a4ea-497d-8a56-07d5de569454" />
Configure Core as the computer name and then restart the computer.Press Enter to return to the SConfig main menu.
Enter 2 to view the current Computer name.In Enter new computer name, enter Core.


<img width="1520" height="908" alt="image" src="https://github.com/user-attachments/assets/ddc1b13f-58a3-4d0c-9ae9-7d510c62e367" />


<img width="1520" height="904" alt="image" src="https://github.com/user-attachments/assets/46504226-8954-4050-a49e-9c36f6777697" />


<img width="1521" height="911" alt="image" src="https://github.com/user-attachments/assets/44b9e17c-0559-474c-a528-716a27ee4d0f" />


<img width="982" height="710" alt="image" src="https://github.com/user-attachments/assets/49d939b1-2b9b-46c1-b1e1-43b1b7e42162" />


<img width="1524" height="913" alt="image" src="https://github.com/user-attachments/assets/1d7898de-65d3-46dc-9d2f-ccd924b1e814" />


<img width="1522" height="901" alt="image" src="https://github.com/user-attachments/assets/836aa857-be3c-4d40-a906-87216d77e48c" />


<img width="1522" height="907" alt="image" src="https://github.com/user-attachments/assets/d5020a03-7c74-4b06-b3b9-ad3c915c31b1" />
Prestage a new computer object named Core in the Computers default container by using Active Directory Users and Computers (ADUC).


<img width="1518" height="908" alt="image" src="https://github.com/user-attachments/assets/20fc74f7-d85c-4199-9a85-9b0f0f9b9667" />


<img width="1520" height="906" alt="image" src="https://github.com/user-attachments/assets/5d1899ae-04f3-45d0-b306-82463ef175af" />
In Server Manager, select the Tools menu, and then select Active Directory Users and Computers.Expand hexelo.com, and then select Computers.
Right-click Computers, select New, and then select Computer.In the New Object - Computer window, in Computer name, enter Core, and then select OK.


<img width="1521" height="908" alt="image" src="https://github.com/user-attachments/assets/b13bc436-6c45-4672-9665-019236ede77d" />
I Join the hexelo.com Active Directory domain by using SConfig, sign in as HEXELO\Administrator using Passw0rd! as the password, and then restart the computer.


<img width="1519" height="907" alt="image" src="https://github.com/user-attachments/assets/1e86fd7d-0e8c-4977-ba55-07871d8ad7f6" />


<img width="1519" height="899" alt="image" src="https://github.com/user-attachments/assets/fd019a2d-abf7-483e-bc57-d1e931d7b660" />


<img width="1523" height="908" alt="image" src="https://github.com/user-attachments/assets/d14b2cac-5306-4a45-91ac-f31b12d03a96" />













