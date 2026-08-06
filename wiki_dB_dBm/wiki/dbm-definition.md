# dBm - Décibel milliwatt

## Définition

Le **dBm** est une unité de puissance très utilisée, référencée à 1 milliwatt (source : video_electro_bidouilleur.md).

### Formule de conversion

$$ \text{dBm} = 10 \cdot \log_{10}\left(\frac{P \text{W}}{1 \ \text{mW}}\right) $$

### Référence fondamentale

$$ 0 \ \text{dBm} = 1 \ \text{mW} $$

- **Valeur négative** → puissance < 1 mW
- **Valeur positive** → puissance > 1 mW

## Conversion W vers dBm

$$ P_{dBm} = 10 \cdot \log\left(\frac{P(W)}{1\text{ mW}}\right) $$

## Conversion dBm vers mW

$$ P = 10^{\frac{P_{dBm}}{10}} \text{ mW} $$

## Valeurs usuelles

| $P_{dBm}$ | $P$ |
| --------- | ----------- |
| $-20$ dBm | $0{,}01$ mW |
| $-10$ dBm | $0{,}1$ mW |
| $-3$ dBm | $0{,}5$ mW |
| $0$ dBm | $1$ mW |
| $3$ dBm | $2$ mW |
| $10$ dBm | $10$ mW |
| $20$ dBm | $100$ mW |

## Exemples de calcul

### Exemple 1 : +27 dBm

Décomposition :

$$ = 0 + 10 + 10 + 10 - 3 $$

Donc :

$$ 1 \ \text{mW} \times 10 \times 10 \times 10 \div 2 = 500 \ \text{mW} $$

### Exemple 2 : -16 dBm

Décomposition :

$$ = 0 - 10 - 3 - 3 $$

Donc :

$$ 1 \ \text{mW} \div 10 \div 2 \div 2 = 25 \ \mu\text{W} $$

## Voir aussi

- [[decibel-definition]]
- [[regles-calcul-dB]]
- [[calculs-rapides]]
- [[dbuv-definition]]
