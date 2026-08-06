# Règles de calcul en dB

## Règles fondamentales

### Pour la puissance (source : video_electro_bidouilleur.md)

- ×2 → **+3 dB**
- ÷2 → **-3 dB**
- ×10 → **+10 dB**
- ÷10 → **-10 dB**

## Valeurs usuelles (source : fiche_david.md)

### Rapport de puissances en dB

| $X_{dB}$ | Rapport $P_1/P_2$ |
| -------- | ----------------- |
| $-40$ dB | $1/10000$ |
| $-30$ dB | $1/1000$ |
| $-20$ dB | $1/100$ |
| $-10$ dB | $1/10$ |
| $-3$ dB | $1/2$ |
| $0$ dB | $1$ |
| $3$ dB | $2$ |
| $10$ dB | $10$ |
| $20$ dB | $100$ |
| $30$ dB | $1000$ |
| $40$ dB | $10000$ |

## Règles de calcul (source : fiche_david.md)

- $A_{dB} \pm B_{dB} = C_{dB}$
- $A_{dBm} \pm B_{dB} = C_{dBm}$
- ❌ $A_{dBm} + B_{dBm}$ **impossible** (on ne peut pas additionner deux puissances en dBm)
- $A_{dBm} - B_{dBm} = C_{dB}$

## Interprétation

- Si $X_{dB} < 0$ → **atténuation** (affaiblissement)
- Si $X_{dB} > 0$ → **amplification**
- Si $X_{dB} = 0$ → **aucun changement**

## Voir aussi

- [[decibel-definition]]
- [[dbm-definition]]
- [[calculs-rapides]]
