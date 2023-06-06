
## LINUX-01:

Linux is een besturingssysteem, zoals Windows, maar is open-source en kent geen geheimen. 
Je hebt toegang tot alle files en dirs en daardoor erg leerzaam in het ontdekken van hoe het 
systeem is opgebouwd. Linux word veel gebruikt als OS voor servers.

## KEY-TERMS:

UBUNTU = een Linux distributie

AWS = Amazon Web Services, cloud provider waar de VM in draait.

VM (virtual machine) = met software opgebouwde hardware, werkt zoals een fysieke PC 

CLI (command line interface) = applicatie voor de communicatie tussen hardware en OS

SSH (secure shell) = protocol om op een versleutelde manier op een remote computer of  
server in te loggen.

## OPDRACHT:

* Make an SSH-connection to your virtual machine. SSH requires the key file to have
  specific permissions, so you might need to change those.
* When the connection is successful, type whoami in the terminal. This command
  should show your username.

## GEBRUIKTE BRONNEN:

[connect ec2 instance ssh](https://www.clickittech.com/aws/connect-ec2-instance-using-ssh/)

![PrtSc clickittech](00_includes\week1\Linux\2023-06-06_1.png)

En mijn peers.

## ERVAREN PROBLEMEN:
De in de beschrijving gegeven link naar OpenSSH voor Windows vond ik niet helder. Ik 
heb daarna bovenstaande URL van een peer gekregen en dat was een stuk duidelijker. 

## RESULTAAT:

![PrtSc result](..\00_includes\week1\Linux\2023-06-06.png)

**Inloggen bij AWS Linux server in PowerShell:**
ssh -p 52201 -i Nest-fr-van-Lieshout.pem francois_@3.121.130.219
