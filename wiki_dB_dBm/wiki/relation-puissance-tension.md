# Relation Puissance / Tension / Impédance

## Formules de base

### Puissance à partir de la tension (source : fiche_david.md)

$$ P = \frac{U_{\text{eff}}^2}{R_c} $$

### Puissance avec impédance (source : video_electro_bidouilleur.md)

$$ P = \frac{V^2}{R} $$

$$ P = \frac{V^2}{Z} $$

### Tension à partir de la puissance

$$ V = \sqrt{P \cdot Z} $$

$$ U_{\text{eff}} = \sqrt{P \cdot R_c} $$

## Valeurs en hyperfréquence

En hyperfréquence, l'impédance caractéristique est généralement :

$$ R_c = 50 \ \Omega $$

## Tension efficace pour une sinusoïde

$$ U_{\text{eff}} = \frac{U}{\sqrt{2}} $$

## Valeurs de référence à 0 dBm

La tension dépend de l'impédance (source : video_electro_bidouilleur.md) :

### À 50 Ω

$$ 0 \ \text{dBm} \approx 224 \ \text{mV RMS} $$

### À 75 Ω

$$ 0 \ \text{dBm} \approx 274 \ \text{mV RMS} $$

## Différence entre puissance et tension

**Attention :** Les règles de calcul sont différentes !

| Grandeur | ×2 | ×10 |
| -------- | -- | -- |
| **Puissance** | +3 dB | +10 dB |
| **Tension** | +6 dB | +20 dB |

Pourquoi 20 log pour la tension ?

$$ \text{dB} = 20 \cdot \log_{10}\left(\frac{V_2}{V_1}\right) $$

Car $P \propto V^2$, donc :

$$ 10 \cdot \log(V^2) = 20 \cdot \log(V) $$

## Voir aussi

- [[decibel-definition]]
- [[dbm-definition]]
- [[dbuv-definition]]
