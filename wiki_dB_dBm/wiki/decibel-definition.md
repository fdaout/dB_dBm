# Décibel (dB) - Définition et Histoire

## Origine historique

Le décibel (dB) provient des milieux de la télécommunication, de l'électronique et de l'acoustique (source : video_electro_bidouilleur.md).

- **Introduit vers 1924**
- En l'honneur de **Alexander Graham Bell**
- Le décibel est un **dixième de bel** :

$$ 10 \ \text{dB} = 1 \ \text{bel} $$

Mais en pratique, on n'utilise que le décibel.

> Important : Le décibel **n'appartient pas au système international**, car il exprime un **rapport**, pas une valeur absolue (source : video_electro_bidouilleur.md).

## Définition

Le décibel exprime un **rapport entre deux valeurs de même unité** (source : video_electro_bidouilleur.md).

### Pour la puissance

$$ \text{dB} = 10 \cdot \log_{10}\left(\frac{P_2}{P_1}\right) $$

### Pour la tension ou le courant

$$ \text{dB} = 20 \cdot \log_{10}\left(\frac{V_2}{V_1}\right) $$

$$ \text{dB} = 20 \cdot \log_{10}\left(\frac{I_2}{I_1}\right) $$

## Pourquoi utiliser les décibels ?

### 1. Compression des grandes valeurs

Le décibel permet de représenter des **rapports énormes** sur une échelle compacte (source : video_electro_bidouilleur.md).

Exemple : De **0 dB à 90 dB** correspond à des rapports de **1 à 1e9**.

### 2. Calculs simplifiés

Avec les dB :
- Multiplications → **additions**
- Divisions → **soustractions**

### 3. Graphiques lisibles

Les échelles logarithmiques permettent de représenter plusieurs **décades** avec une bonne résolution.

## Voir aussi

- [[dbm-definition]]
- [[regles-calcul-dB]]
- [[relation-puissance-tension]]
