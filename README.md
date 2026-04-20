# Analyse des Données d'Écoute Spotify

Ce projet analyse les données d'écoute d'un utilisateur Spotify pour extraire des insights sur ses habitudes d'écoute musicale. 

[Lien vers le projet kaggle](https://www.kaggle.com/code/augustinmontreuil/analyzing-spotify-streaming-history-insights/edit)

## Fonctionnalités

- Analyse des artistes et morceaux les plus écoutés
- Analyse temporelle des écoutes (par jour et par heure)
- Analyse des comportements d'écoute (shuffle, skip)
- Visualisations des données
- Statistiques détaillées sur les habitudes d'écoute


## Dépendances

- pandas >= 1.5.0
- numpy >= 1.21.0
- matplotlib >= 3.5.0
- seaborn >= 0.11.0
- plotly >= 5.13.0

## Résultats 

![image](https://github.com/user-attachments/assets/5e955e6c-6f3f-41ca-a3b5-694f75b4b976)

![image](https://github.com/user-attachments/assets/fd15638b-21ec-45ef-a9f1-b1dc5281f5ff)

![image](https://github.com/user-attachments/assets/e0158dec-0d6a-4eec-8906-f7dafb57c6c8)

## Statistiques générales

- **Total de morceaux écoutés** : 149 648  
- **Période couverte** : du 08/07/2013 au 15/12/2024  
- **Artistes différents** : 4 105  
- **Titres uniques** : 13 801  

---

## Top 10 artistes

| Artiste             | Écoutes |
|---------------------|---------|
| The Beatles         | 13 620  |
| The Killers         | 6 876   |
| John Mayer          | 4 851   |
| Bob Dylan           | 3 808   |
| Paul McCartney      | 2 697   |
| Led Zeppelin        | 2 476   |
| Johnny Cash         | 2 470   |
| The Rolling Stones  | 2 390   |
| Radiohead           | 2 303   |
| The Black Keys      | 2 231   |

---

## Top 10 morceaux

| Titre                                 | Artiste           | Écoutes |
|---------------------------------------|-------------------|---------|
| Ode To The Mets                       | The Strokes       | 207     |
| In the Blood                          | John Mayer        | 181     |
| Dying Breed                           | The Killers       | 166     |
| Caution                               | The Killers       | 164     |
| 19 Dias y 500 Noches (live)           | Joaquín Sabina    | 148     |
| Concerning Hobbits                    | Howard Shore      | 142     |
| All These Things That I've Done       | The Killers       | 142     |
| Come Together (Remastered 2009)       | The Beatles       | 137     |
| Yesterday (Remastered 2009)           | The Beatles       | 134     |
| Crucify Your Mind                     | Rodríguez         | 131     |

---

## Habitudes d’écoute

### Par jour de la semaine

| Jour       | Écoutes |
|------------|---------|
| Vendredi   | 25 623  |
| Mercredi   | 23 333  |
| Jeudi      | 21 364  |
| Lundi      | 21 013  |
| Mardi      | 20 691  |
| Samedi     | 19 385  |
| Dimanche   | 18 239  |

### Par heure de la journée

| Heure | Écoutes |
|-------|---------|
| 00h   | 10 869  |
| 01h   | 9 377   |
| 02h   | 9 016   |
| 03h   | 8 541   |
| 04h   | 6 345   |
| 05h   | 7 150   |
| 06h   | 7 363   |
| 07h   | 4 409   |
| 08h   | 2 312   |
| 09h   | 1 695   |
| 10h   | 1 207   |
| 11h   | 903     |
| 12h   | 724     |
| 13h   | 1 658   |
| 14h   | 2 759   |
| 15h   | 3 725   |
| 16h   | 6 735   |
| 17h   | 9 181   |
| 18h   | 8 932   |
| 19h   | 8 146   |
| 20h   | 10 467  |
| 21h   | 8 926   |
| 22h   | 8 706   |
| 23h   | 10 502  |

---

## Analyse des comportements

- **Mode aléatoire (shuffle)** : 74,54 %  
- **Morceaux skipés** : 5,18 %  

---

## 🔍 Statistiques supplémentaires

**Durée moyenne d’écoute par morceau** : 128,29 secondes  

### Plateformes utilisées

| Plateforme       | Écoutes |
|------------------|---------|
| Android          | 139 821 |
| Cast to device   | 3 893   |
| iOS              | 2 842   |
| Windows          | 1 691   |
| macOS            | 1 176   |

### Raisons de fin d’écoute

| Raison            | Cas     |
|-------------------|---------|
| Fin naturelle     | 77 110  |
| Suivant appuyé    | 53 462  |
| Fin du morceau    | 10 116  |
| Déconnexion       | 4 367   |
| Retour arrière    | 2 182   |

---
[Retour au portfolio](https://github.com/augu-gif/mon-portfolio-data-analyst/blob/main/README.md)
