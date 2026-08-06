# Bilan de liaison - Formule de Friis

## Forme classique (source : fiche_david.md)

$$ P_r = P_e \cdot G_e \cdot G_r \cdot \left(\frac{\lambda}{4\pi R}\right)^2 $$

Où :
- $P_r$ = Puissance reçue
- $P_e$ = Puissance émise
- $G_e$ = Gain de l'antenne émettrice
- $G_r$ = Gain de l'antenne réceptrice
- $\lambda$ = Longueur d'onde
- $R$ = Distance entre les antennes

## Forme en dB

$$ P_r(dBm) = P_e(dBm) + G_e(dB) + G_r(dB) + 20 \cdot \log\left(\frac{\lambda}{4\pi R}\right) $$

## Perte de parcours (Path Loss)

Le terme $20 \cdot \log\left(\frac{\lambda}{4\pi R}\right)$ représente la perte de parcours dans l'espace libre.

En pratique, on l'exprime souvent comme une atténuation :

$$ L_{dB} = -20 \cdot \log\left(\frac{\lambda}{4\pi R}\right) = 20 \cdot \log\left(\frac{4\pi R}{\lambda}\right) $$

Donc :

$$ P_r(dBm) = P_e(dBm) + G_e(dB) + G_r(dB) - L_{dB} $$

## Application

Cette formule est essentielle pour :
- Calculer la portée d'un lien radio
- Dimensionner un système de communication
- Estimer la puissance reçue à une distance donnée

## Voir aussi

- [[composants-dB]]
- [[dbm-definition]]
- [[calculs-rapides]]
