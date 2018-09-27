# Import-the-internal-key-into-bastion-instance-by-FileZilla

## Prerequisites
>Depend on your operating system, download and install [FileZilla](https://filezilla-project.org/download.php?type=client) software.

## Tutorial
You can follow these steps to connect to your bastion machine:

1. Open FileZilla, choose edit-->setting.

![stp1.PNG](/img/stp1.PNG)

2. Type SFTP, and add your ppk file for bastion instance.

![stp2.PNG](/img/stp2.PNG)

3. Choose file--> site Manager

![stp3.PNG](/img/stp3.PNG)

4. Type **New Site** and paste the Public IP of bastion instance in **Host** then **connect**.

![stp4.PNG](/img/stp4.PNG)

5. Drag the "InternalKeyPair.pem" file to the red box mark.

![stp5.PNG](/img/stp5.PNG)

## Reference
* [Connect to Amazon EC2 file directory using Filezilla and SFTP](https://www.youtube.com/watch?v=e9BDvg42-JI)
