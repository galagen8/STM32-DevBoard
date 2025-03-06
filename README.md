<h1> STM32-DevBoard </h1>

Created STM32F103C8T6 Development Board for my needs. </br>
This board has: 
- HUB75 socket with bi-directional level-shifter (3.3-5V);
- I2C socket (you can supply external eqiupment 3.3V or 5V using just toggle switch);
- UART socket with bi-directional level-shifter (3.3-5V);
- CR2032 3V Battery slot for power-independent applications (switch for choosing the supply - VIN/BAT);
- ST-Link programming slot;
- BOOT1/BOOT2 switches;
- Separate switches for supplying 3.3V and 5V sub-circuits;
- Input voltage = 12VDC max.

</br>
</br>

All schematics diagram you may find in "Altium files" folder.</br>
PCB design:

<p align="center">	
<img src="https://github.com/user-attachments/assets/1282fa50-2c25-4574-9022-c07fc5852c16" width="900">	
</p>
</br>

Assembled board:

<p align="center">	
<img src="https://github.com/user-attachments/assets/c23e6f0f-43f9-4065-9673-1c09a3788498" width="600">	
</p>
</br>
</br>

You can program this board using orginal ST-Link or cheap ST-Link V2 clone. </br>
I adapted the programming socket for cheap ST-Link V2 clone (4-pin Dupont header):
</br>
</br>

<p align="center">	
<img src="https://github.com/user-attachments/assets/72423224-f90e-4e23-b368-7f83fefd008d" width="100">	
</p>
