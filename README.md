[![Donate](https://img.shields.io/badge/donate-paypal-yellowgreen.svg)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4)
[![Discord](https://img.shields.io/discord/432663330281226270?color=728ED5&logo=discord&label=discord)](https://discord.gg/ahVq54p)
[![Discord](https://img.shields.io/badge/%3CDiscord%3E-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/ahVq54p)
[![Twitter](https://img.shields.io/discord/432663330281226270?color=728ED5&logo=twitter&label=twitter)](https://twitter.com/4Xsample)


# Servidor-gratuït-Oracle-Cloud
 
Si necesites un servidor gratuït o directament un ordinador remot en el que experimentar, recomano provar els serveis de [Oracle Cloud](https://www.oracle.com/cloud/) on podeu generar maquines virtuals gratuites.

Cada usuari pot escollir una o mes màquines virtuals. (quant mes potent sigui la màquina menys maquines pots desplegar). Personalment recomano desplegar una sola màquina virtual tant potent com pogueu.

L'unic secret per tenir l'ordinador virtual permanentment es triar entre les opcions que tenen la etiqueta grisa a sota "Always Free Eligible".

Al començar a desplegar la màquina, despres de triar els noms i aquestes coses, ens permet triar la ubicació fisica de la nostre elecció (Escollir sempre la ubicació que tingui la etiqueta Always free eligible)

El segon pas a triar es el sistema operatiu. Aquì tenim una bona colla d'opcions "Always Free Eligible" però si no vols investigar massa recomano tirar per Canonical Ubuntu.

El tercer pas ja es triar detalls com les subxarxesnecesaries etc... tot això pot quedar per defecte.

El quart pas es el mes extrany, afegir les claus SSH, aquì recomano calma i tranquilitat i llegir la [guia](https://docs.oracle.com/en-us/iaas/Content/Compute/Tasks/managingkeypairs.htm) de com obtenir una clau ssh amb el [PuTTY Key Generator](https://www.puttygen.com/)

A partir d'aquí ja teniu una màquina virtual gratuita per jugar i experimentar.

## Important
si voleu fer servir aquesta màquina virtual de servidor heu d'entrar al vostre Dashboard, buscar l'apartat de Virtual Cloud Networks i entrar a la vostre subxarxa fins a trobar "Default Security List for latevaxarxa" i obrir els ports l'origen ha de ser 0.0.0.0/0 i el port o rang de ports d'entrada i desti que volgueu posar (es molt recomanable omplir les descripcions per quan s'us acumulin ports oberts).
