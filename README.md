# pedometer
Stappenteller voor de beroepsopdracht Stapify (juni 2023)

De code die in deze repo staat is alleen de stappenteller, wat is geprogrammeerd in Arduino-based C.

Bij deze opdracht heeft een team van 3 man een koppeling gemaakt tussen 2 devices. De teamleden hadden alle 3 een verschillende taak. Dev-ops / backend, Front-end en embedded. Hierbij was ik zelf het lid van embedded.

Tijdens deze opdracht kwam ik vast op een paar problemen, die ik later zal opnoemen, maar eerst welke technieken ik tijdens deze opdracht heb geleerd. Ik had mij eerste ervaring met GraphQL en weet nu het verschil tussen queries en mutations. Ik heb kennis opgedaan met verschillende MCU's, waaronder de RP2040, File Transferring naar een RP Zero en meer kennis met de RP Pico en ESP8266.

De problemen die ik tegenkwam waren:
- Ik kon niet meer uploaden naar de RP2040, elke keer dat ik dat deed crashte de hele RP2040. Hierdoor ben ik overgestapt naar een RP Zero.
- RP Zero kon geen goed analoog signaal lezen, wat de sensoor verstuurde. Hierdoor werd er overgegaan naar een RP Pico, maar die had hetzelfde probleem.
- Uiteindelijk heb ik een ESP8266 gebruikt, waar ik de meeste ervaring mee heb van alle MCU's.

Het idee was ook om nog een hartslagsensoor toe te voegen, maar die deed het niet vanwegen technise problemen met een ESP8266. Voor een ander project wil ik de hartslagsensoor nog wel gebruiken.
