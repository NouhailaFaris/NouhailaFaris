TP Bus & Réseau:

les adresses I²C possibles pour ce composant: 111011X0
le registre et la valeur permettant d'identifier ce composant:0xD0
le registre et la valeur permettant de placer le composant en mode normal:0xF4 , Valeur :11
les registres contenant l'étalonnage du composant:les registres calib00 à calib25, de l'adresse 0x88 à 0xA1.
les registres contenant la température (ainsi que le format):
->temp_msb à l'adresse 0xFA (bits 15-8)
->temp_lsb à l'adresse 0xFB (bits 7-0)
->temp_xlsb à l'adresse 0xFC (bits 7-4)
les registres contenant la pression (ainsi que le format):
->press_msb à l'adresse 0xF7 (bits 15-8)
->press_lsb à l'adresse 0xF8 (bits 7-0)
->press_xlsb à l'adresse 0xF9 (bits 7-4)
les fonctions permettant le calcul de la température et de la pression compensées, en format entier 32 bits:
![image](https://github.com/user-attachments/assets/38dd5690-3479-4c2d-886d-d6d32c0d9db1)





