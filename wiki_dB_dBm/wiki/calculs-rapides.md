# Calculs rapides en dB

## Méthode de décomposition

Pour calculer mentalement, décomposez le dB en somme de valeurs connues (source : fiche_david.md).

### Exemples

**26 dB** = 20 + 3 + 3 → ×100 ×2 ×2 = **400**

**-13 dB** = -10 - 3 → 0,1 / 2 = **0,05**

**-17 dBm** = -20 + 3 → 0,01 × 2 = **0,02 mW**

## Valeurs approchées utiles

| dB | Rapport approximatif |
| -- | -------------------- |
| 1 dB | ≈ 1,258 |
| 5 dB | ≈ 3,162 |

## Règles de calcul

- **Multiplication** → **addition** en dB
- **Division** → **soustraction** en dB

## Astuces pour les conversions

### Décomposition de puissances

Pour convertir un dBm en mW :
1. Décomposez en -20, -10, -3, 0, +3, +10, +20
2. Appliquez les facteurs correspondants
3. Multipliez les résultats

### Exemple pratique

Pour +27 dBm :
- 27 = 10 + 10 + 10 - 3
- 1 mW × 10 × 10 × 10 ÷ 2 = **500 mW**

Pour -16 dBm :
- -16 = -10 - 3 - 3
- 1 mW ÷ 10 ÷ 2 ÷ 2 = **25 µW**

## Voir aussi

- [[regles-calcul-dB]]
- [[dbm-definition]]
- [[bilan-liaison-friis]]
