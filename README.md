# PiOLED
Handleiding en voorbeelden PiOLED

**Voorbereiding:**  
We gaan hier uit vaan een nieuwe Raspberry Pi of Jetson nano.  
Schrijf een nieuwe versie van JEtpack of raspbian naar de SDkaart en voeg de standaardinstallatie uit.  
Schakel dan op een Raspberry Pi i2c in via  
```
sudo raspi-config
interfacing options > A7 i2c > yes
```

Voer volgende commando's uit om de juiste software en drivers te installeren:  
```
sudo apt-get install python3-pip python3-pil git -y
sudo pip3 install adafruit-circuitpython-ssd1306
```

Clone dan deze repository met  

```
git clone https://github.com/Neuralis-AI/PiOLED.git
```
En voer stats.py uit met  

```
python3 stats.py
```
