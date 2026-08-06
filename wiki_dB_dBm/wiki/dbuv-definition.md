# dBµV - Décibel microvolt

## Définition

Le **dBµV** est une unité de tension référencée à 1 microvolt (source : fiche_david.md).

## Conversion tension vers dBµV

$$ U_{dB\mu V} = 20 \cdot \log\left(\frac{U(V)}{1\ \mu V}\right) $$

## Conversion dBµV vers tension

$$ U = 10^{\frac{U_{dB\mu V}}{20}} \ \mu V $$

## Formule générale pour le rapport de tensions

### Vers dB

$$ X_{dB} = 20 \cdot \log\left(\frac{U_1}{U_2}\right) $$

### Depuis dB

$$ \frac{U_1}{U_2} = 10^{\frac{X_{dB}}{20}} $$

## Valeurs utiles

| Valeur | Équivalent | Condition |
| ------ | ---------- | --------- |
| $13$ dBm | ≈ $1$ V | 50Ω |
| $0$ dBm | ≈ $224$ mV | 50Ω |
| $107$ dBµV | ≈ $0$ dBm | 50Ω |
| $120$ dBµV | ≈ $1$ V | - |

## Bruit thermique

$$ -174 \ \text{dBm} $$

C'est le bruit thermique pour une bande passante de 1 Hz à 17°C (source : fiche_david.md).

## Voir aussi

- [[dbm-definition]]
- [[relation-puissance-tension]]
- [[decibel-definition]]
