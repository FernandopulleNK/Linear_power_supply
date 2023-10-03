# Linear_power_supply
- Four members of our group collaborated to develop a linear power supply design aimed at providing a consistent voltage and current output. The design process commences with a step-down transformer tasked with reducing the input voltage from 230V to 15V AC. Subsequently, a GBPC3506W bridge rectifier is employed to convert this AC voltage into DC, followed by a 10mF capacitor to smoothen the output.
- Our design integrates two transistors, specifically the MJ4502 and BC547A, configured as a Sziklai pair, along with a 10V Zener diode, a 150Ω resistor, and a diode to regulate voltage. We've also implemented current limiting to cap the maximum current at 10A, and there's built-in short-circuit protection for safety measures. To ensure effective heat dissipation, we've utilized a heat sink in conjunction with the MJ4502 transistor and bridge rectifier.
- The final product consists of a single-layer PCB enclosed within a 3D-printed casing, and we've incorporated a 12V DC fan to facilitate cooling.
- The main function of the linear power supply is to drive a load under constant voltage/current condition. Under this project we design a 10V linear power supply with a maximum current rating of 10A with the voltage regulator from scratch to drive a high-power load (100W) from 230V input voltage. The final circuit is made of two circuits. They are main regulation circuit and protection circuit.

### Simulation circuit (Multisim).
![WhatsApp Image 2023-02-06 at 8 03 23 AM](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/abca2f76-2eaf-4174-bc84-ab412b33f5dc)

### PCB schematic.
![Screenshot (281)](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/065741f3-2852-4084-a4a0-78c4c6b6e1ea)

### PCB Layout.
![Screenshot (282)](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/c8f1dc36-46fa-4721-b57b-00833fb8a1d9)

### Enclosure Design.
![Screenshot (283)](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/606e8f20-0d9e-4f94-a17e-1ad70641c4d4)

### Final Product.
![WhatsApp Image 2023-02-27 at 5 59 13 PM (1)](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/008a64be-da18-4a04-9242-7a1429b831f2)
![WhatsApp Image 2023-02-27 at 5 59 12 PM (2)](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/e0f45f20-0538-462d-8ad6-43bb9fae2d6a)




### Our Group (Sadeep , Thulani , Aaquil and me)
![WhatsApp Image 2023-02-25 at 9 58 10 PM](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/a6929297-57fb-4b67-bbef-1768a40d5c12)
![WhatsApp Image 2023-02-27 at 5 59 20 PM](https://github.com/FernandopulleNK/Linear_power_supply/assets/128304706/90a48036-bcba-4d2b-a907-efae06795944)
