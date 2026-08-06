# Composants en dB

## Amplificateur et atténuateur

### Formule générale (source : fiche_david.md)

$$ P_s = P_e + G_0 + G_1 - A + G_2 $$

Où :
- $P_s$ = Puissance de sortie (dBm)
- $P_e$ = Puissance d'entrée (dBm)
- $G_0, G_1, G_2$ = Gains (dB)
- $A$ = Atténuation (dB)

### Exemple

Données :
- $P_e = -10$ dBm
- $G_0 = 10$ dB
- $G_1 = 20$ dB
- $A = 30$ dB
- $G_2 = 10$ dB

Calcul :

$$ P_s = -10 + 10 + 20 - 30 + 10 = 0 \text{ dBm} $$

## Amplification

### Formule (source : fiche_david.md)

$$ P_s = a \cdot P_e \Rightarrow P_s(dBm) = P_e(dBm) + A_{dB} $$

## Atténuation

### Formule (source : fiche_david.md)

$$ P_s = \frac{P_e}{a} \Rightarrow P_s(dBm) = P_e(dBm) - A_{dB} $$

## Coupleur

Un coupleur directionnel a plusieurs paramètres caractéristiques (source : fiche_david.md).

### Couplage

$$ C_{dB} = P_1(dBm) - P_3(dBm) $$

### Perte d'insertion

$$ A_{dB} = P_1(dBm) - P_2(dBm) $$

### Isolation

$$ I_{dB} = P_1(dBm) - P_4(dBm) $$

### Directivité

$$ D_{dB} = P_3(dBm) - P_4(dBm) $$

### Relation entre paramètres

$$ D_{dB} = I_{dB} - C_{dB} $$

## Voir aussi

- [[bilan-liaison-friis]]
- [[dbm-definition]]
- [[regles-calcul-dB]]
