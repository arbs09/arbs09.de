+++
title = "Pihole + DietPi + unbound + list updates"
date = 2024-05-10
+++
First you go on [dietpi.com](https://dietpi.com/#download) and download the latest image for your Rasperry Pi.
Then if you don´t alredy have it, you download [Balena Etcher](https://etcher.balena.io/).
Now you can plug a sd card or a usb drive into your computer.
Please make sure to backup all the importent data, because this will wipe the disk.
Than you can flash the newly dowloaded immage on a sd card or a usb drive.
if the drive is ready after the flashing, you can unplug the drive and connect it to the raspberry pi.
Now you can give the raspberry pi power and ethernet.
Than you can ssh into the pi using:

```bash
ssh root@<Pi-IP>
```

If you get asked for a Password (if you didn´t change it) it is:

```bash
dietpi
```

