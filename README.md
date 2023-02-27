# Aux-Project-1: SHELL SCRIPTING

### create project folder called shell

`mkdir shell && cd shell`

### create csv file to store the names

`touch names.csv`

`vim names.csv`

### create the developers group

`sudo groupadd developers`
![](/images/groupadd.jpg)

### create file for public key

`touch id_rsa.pub`

`vim id_rsa.pub`
![public key](/images/id_rsa.jpg)

### create file for private key

`touch id_rsa`

`vim id_rsa`

### create script

`touch onboard.sh`

`chmod +x onboard.sh`
![chmod](/images/onboard.jpg)

`vi onboard.sh'

![onboard](/images/vi-onboard.jpg)

`./onboard.sh`
![runing script](/images/running%20script.jpg)

![](/images/list%20directory.jpg)

### connect as one of the created user

`$ ssh -i aux-privatekey.pem Mike@3.8.89.99`
![connect as user Mike](/images/connect%20as%20a%20user.jpg)
