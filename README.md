# Installation

## Code source
```
git clone https://github.com/gwendal-lv/dragino_rpi-lora-tranceiver
cd dragino_rpi-lora-tranceiver
```

## WiringPi

Installation de WiringPi, pour pouvoir utiliser les GPIOs. Attention, le paquet ci-dessous doit être installé sur un OS 64 bits.
```
wget https://github.com/WiringPi/WiringPi/releases/download/3.10/wiringpi_3.10_arm64.deb
sudo apt install ./wiringpi_3.10_arm64.deb
```


# Utilisation

Pour faire des tests d'émission/réception simple, le code à modifier est ```/main.c```. Pour le compiler et le tester :

```
cd dragino_lora_app
make
```

L'exécutable compilé est alors disponible dans le dossier courant.

# Source

Repo original : https://github.com/dragino/rpi-lora-tranceiver
