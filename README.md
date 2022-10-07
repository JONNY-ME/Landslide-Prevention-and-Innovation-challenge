# Landslide-Prevention-and-Innovation-challenge

# Description: 
This repository contains the code for the Landslide Prevention and Innovation Challenge on Zindi Africa. You can check out the challenge here 👉 [Zindi Competetion](https://zindi.africa/competitions/landslide-prevention-and-innovation-challenge).

# Approach: 
For this Challenge, I used two approachs and an ensemble of both, which are included in the following notebooks:
* **Landslide prediction V1.ipynb** - This notebook uses the oversampling method for the data imbalance problem. the model used are CatBoostClassifier and LGBMClassifier. It produes the `submission1.csv` output file.
* **Landslide prediction V2.ipynb** - This notebook uses threshold variation for the data imbalance problem. same models as in V1 are used, but with different parameters. It produces the `submission2.csv` output file.
*  **Ensembling Landslide prediction.ipynb** - This notebook uses the ensemble of the two approaches above, i.e the submission1.csv and submission2.csv files. It produces the `ensemble.csv` output file.

# Results: 
The results of the two approaches are as follows:
* **Landslide prediction V1.ipynb** - The model achieved a F1 score of `0.7624`.
* **Landslide prediction V2.ipynb** - The model achieved a F1 score of `0.7613`.
* **Ensembling Landslide prediction.ipynb** - The model achieved a F1 score of `0.7652`.

#### Rank on the leaderboard: 3rd place using the ensemble.csv file.

Please Leave a⭐️ to my repo, if you find it useful😊
