# RP2040 Devboard
Week 5 project of Hack club Half Life

<img width="626" height="1180" alt="Screenshot 2026-11-11 213708" src="https://github.com/user-attachments/assets/62d59783-eb1a-4e85-b96d-7a86c2685a9e" />

# Details
A devboard Based off of the Raspberry Pi Pico using the RP2040 Microcontroller.

28 GPIO pins

Red power led on the top right and a yellow green test led on the bottom right GPIO 25

Bottom button is reset, top button is boot

Check schematic image below for pinouts
# BOM
*Note these are bulk quantities not exact

| Item | Qty | Supplier | Cost/item | Total Cost | Link |
| :--- | :---: | :--- | :---: | :---: | :--- |
| 1uF capacitor | 50 | LCSC | $0.01 | $0.50 | [Link](https://www.lcsc.com/product-detail/C29266.html?spm=wm.gwc.xh.0.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 0.1uF capacitor | 100 | LCSC | $0.0032 | $0.32 | [Link](https://www.lcsc.com/product-detail/C1525.html?spm=wm.gwc.xh.1.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 10uF capacitor | 20 | LCSC | $0.0205 | $0.41 | [Link](https://www.lcsc.com/product-detail/C19702.html?spm=wm.gwc.xh.2.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 33pF capacitor | 100 | LCSC | $0.002 | $0.2 | [Link](https://www.lcsc.com/product-detail/C107005.html?spm=wm.gwc.xh.3.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| USB-C Receptacle 12PIN | 5 | LCSC | $0.1736 | $0.87 | [Link](https://www.lcsc.com/product-detail/C165948.html?spm=wm.gwc.xh.11.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| Conn_01x20 | 5 | LCSC | $0.0856 | $0.43 | [Link](https://www.lcsc.com/product-detail/C42431804.html?spm=wm.gwc.xh.4.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 5.1k resistor | 100 | LCSC | $0.0011 | $0.11 | [Link](https://www.lcsc.com/product-detail/C2906874.html?spm=wm.gwc.xh.6.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 27 ohm resistor | 100 | LCSC | $0.0013 | $0.13 | [Link](https://www.lcsc.com/product-detail/C25100.html?spm=wm.gwc.xh.7.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 1k resistor | 100 | LCSC | $0.0026 | $0.26 | [Link](https://www.lcsc.com/product-detail/C106235.html?spm=wm.gwc.xh.5.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 10k resistor| 100 | LCSC | $0.0017 | $0.17 | [Link](https://www.lcsc.com/product-detail/C60490.html?spm=wm.gwc.xh.8.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| SPST switch | 20 | LCSC | $0.0507 | $1.01 | [Link](https://www.lcsc.com/product-detail/C720477.html?spm=wm.gwc.xh.9.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| RP2040 Microcontroller | 3 | LCSC | $1.0969 | $3.29 | [Link](https://www.lcsc.com/product-detail/C2040.html?spm=wm.gwc.xh.10.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| MCP1700x-330xxTT voltage LDO | 10 | LCSC | $0.0759 | $0.76 | [Link](https://www.lcsc.com/product-detail/C42417262.html?spm=wm.gwc.xh.14.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| W25Q16JVUXIQ Flash memory | 4 | LCSC | $1.5912 | $6.36 | [Link](https://www.lcsc.com/product-detail/C2843335.html?spm=wm.gwc.xh.13.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 12mhz X322512MSB4SI crystal ocillator | 5 | LCSC | $0.917 | $0.48 | [Link](https://www.lcsc.com/product-detail/C9002.html?spm=wm.gwc.xh.12.cbm___wm.fly.ssl.gwc&lcsc_vid=TgdYAQdQRwdeUABeRQdeVFRSEgJdX1VWFFVZUVEFRAMxVlNfQ1BXVlNRT1NZXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| Red Led | 100 | LCSC | $0.59 | $0.0059 | [Link](https://www.lcsc.com/product-detail/C19171390.html?spm=wm.gwc.xh.15.cbm___wm.sxq.ssl.gwc&lcsc_vid=FQdbAlNQRVZfUl1RQ1UKUVUFE1cKU1QAQVAMBVMAR1UxVlNfQ1VdU1dRRFhdUzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| Yellow Green Led | 20 | LCSC | $0.0186 | $0.37 | [Link](https://www.lcsc.com/product-detail/C125094.html?spm=wm.gwc.xh.16.cbm___wm.sxq.ssl.gwc&lcsc_vid=FQdbAlNQRVZfUl1RQ1UKUVUFE1cKU1QAQVAMBVMAR1UxVlNfQ1VdU1dRRFhdUzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| PCB | 5 | JLCPCB | | $4.10 | [Link](https://jlcpcb.com/) |
| Estimated total shipping | 1 | | | $15.37 | |
| TOTAL  |  | | | $34.40 | |
# Images
<img width="544" height="1180" alt="Screenshot 2026-11-11 221342" src="https://github.com/user-attachments/assets/2b35f272-ef58-49af-a613-8a2dfce4124a" />
<img width="513" height="1176" alt="Screenshot 2026-11-11 221326" src="https://github.com/user-attachments/assets/642ea42f-1b43-402c-bcda-61f2d7dc4d22" />
<img width="1191" height="823" alt="Screenshot 2026-11-11 213800" src="https://github.com/user-attachments/assets/5afeb642-0a80-4d8f-b84f-d046a1c9c01c" />
<img width="764" height="1171" alt="Screenshot 2026-11-11 213642" src="https://github.com/user-attachments/assets/c235c6b4-a6e0-4760-9203-38000f33fd26" />
<img width="1372" height="1062" alt="Screenshot 2026-11-11 213558" src="https://github.com/user-attachments/assets/a0dd8cda-8c26-47e4-8f18-5f271e7b779d" />
<img width="1219" height="1169" alt="Screenshot 2026-11-11 213532" src="https://github.com/user-attachments/assets/ac9be55b-e7a3-45ce-96c7-b6d9fff0b293" />
<img width="1395" height="1231" alt="Screenshot 2026-11-11 213450" src="https://github.com/user-attachments/assets/8ca4dc78-0bcc-4a0d-b209-0b832f4a400a" />


