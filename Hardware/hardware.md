## U1 : Pour calculer les résistances de l'utilisation de Capteur de la tension (LEM LV 25-P) 

Selon le datasheet "Voltage Transducer LV 25-P", on sait que :
Taux de conversion = 2500 : 1000
Courant Is = 25 mA
Donc conrant Iin = 10 mA

Tension d'entrée est 230 V au maximum, -230 V au minmum, donc on choisit Vin comme 500V, R1 = Vin  / Iin = 500/10mA = 50 Kohm, la puissance de l'entrée est Iin*Vin = 10*230 = 2.3 kW.

On a Vout = 3.3 V au maximum, donc Rm = Vout (au maximum) / Is = 3.3/25mA = 132 ohm.

En conclusion, le taux de la tension est : Vout/Vin = 3.3/230 = 0.0143.  

## U2 : AOP
Tension d'entrée : V1(Vout de U1)
Tension de sortie : V2
Resistance variable : pour calibrer V2 à 3,3V  

## U3 : MAX 6795 pour amlimenter le STM32
Tension d'entrée : +15 V
Tension de sortie : 3.3 V
Pour le régulateur linéaire
https://fr.farnell.com/analog-devices/max6795tpsd2/regulateur-lineaire-3-3v-0-3a/dp/2799272


Tension d'entrée : Provient du traco avec +15v
Tension de sortie : 3,3v pour alimenter le STM, l'écran, les LEDS, etc

## Contrôleur LCD I2C PCF8574 

## Ecran LCD LM016L

https://controllerstech.com/i2c-lcd-in-stm32/



