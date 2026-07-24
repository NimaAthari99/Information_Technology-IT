# Cameras

## Give Permission To Users

### Hilook Application

Follow These steps:

```bash
Right click on Destination DVR
Remote config 
See users that have remote permission

```

### IVMS Application

Follow These steps:

### Smart PSS Application

Follow These steps:

## For VPN Permission

In firewall (Sophos):
In related to your destination cameras:
Add users to "domain users"

## Add Camera To DVR

Searh your dvr's IP address in edge browser (for accessing it's web ui) and follow These steps:

```bash
Configuration
System
Camera management
Add
IP camera Address = *IP OF YOUR CAMERA
User=admin
Pass=*PASSWORD
```

## Reset Camera

Follow These steps:

```bash
Open your camera
Connect it to poe or adaptor and immediatly press the reset button inside it 
Then it will be  reset and get defauklt ip address that you can access it
```

Usually default ip of camera is 192.168.1.64.
***NOTE:*** Pay attention if you want to access to your camera, you must be in same subnet and vlan of your camera.