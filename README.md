# pokemon-challenge
Addestramento supervisionato di un modello di machine learning per predire il vincitore in uno scontro tra pokemon :crossed_swords: :shield:

* [pokemon.csv](https://github.com/mariocuomo/pokemon-challenge/blob/main/pokemon.csv)<br>
É un dataset (.csv) di supporto contenente diverse informazioni riguardo i pokemon.

* [combats.partial.csv](https://github.com/mariocuomo/pokemon-challenge/blob/main/combats.partial.csv)<br>
É il dataset (.csv) di partenza per l'apprendimento supervisionato.<br>
É composto da triple **pokemon1 | pokemon2 | vincitore**.

* [preparazione.ipynb](https://github.com/mariocuomo/pokemon-challenge/blob/main/preparazione.ipynb)<br>
É un Jupyter Notebook con l'obiettivo di caricare il dataset e splittarlo in due dataset (train.csv e test.csv) con un rapporto 5:1.

* [train.ipynb](https://github.com/mariocuomo/pokemon-challenge/blob/main/train.ipynb)<br>
É un Jupyter Notebook con l'obiettivo di caricare i due dataset (train.csv e test.csv), addestrare il modello sui dati di train - con l'analisi aggiuntiva del dataset pokemon.csv - e testarlo su quelli di test.

---
Challenge proposta durante il corso di Intelligenza Artificiale, Roma Tre.<br>
Per saperne di più :point_right: [mariocuomo/artificial_intelligence](https://github.com/mariocuomo/artificial_intelligence)

