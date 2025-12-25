# Projet Akowe - Indice SSA

Ce projet construit un indice simple pour prioriser les pays d'Afrique subsaharienne (SSA) pour une EdTech.
Il combine 4 dimensions :
- taille du marche (population 15-24 + scolarisation),
- dynamique (croissance Internet + scolarisation secondaire),
- capacite de paiement (PIB/habitant PPA + depenses d'education),
- faisabilite operationnelle (acces Internet).

## Fichiers principaux
- `Analyse EDSTAT.ipynb` : notebook principal.
- `EdStatsData.csv`, `EdStatsCountry.csv`, `EdStatsSeries.csv` : donnees EdStats.

## Lancer le projet
1) Installer les dependances :

```bash
pip install -r requirements.txt
```

2) Ouvrir le notebook :

```bash
jupyter notebook
```

Puis executer `Analyse EDSTAT.ipynb` cellule par cellule.

## Donnees
Placez les fichiers EdStats a la racine du projet (meme dossier que le notebook) :
- `EdStatsData.csv`
- `EdStatsCountry.csv`
- `EdStatsSeries.csv`
- (optionnel) `EdStatsFootNote.csv`, `EdStatsCountry-Series.csv`

## Presentation (PowerPoint)
Lien Google Drive :
https://docs.google.com/presentation/d/1KTSIgc2RD78wZcmjwNXge6L176MNIAQ9/edit?usp=sharing&ouid=106060524966208801668&rtpof=true&sd=true

## Remarques
- Les fichiers CSV sont volumineux. Pour GitHub, il est recommande de ne pas versionner `EdStatsData.csv` et de fournir un lien de telechargement si besoin.
