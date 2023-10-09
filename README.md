# FIFA 2021 Player Dataset

![FIFA 2021 Logo](fifa2021.jpg)

## Overview

This dataset contains information about football (soccer) players featured in the FIFA 2021 video game. It includes various attributes and statistics for each player, making it a valuable resource for football enthusiasts, analysts, and data scientists interested in exploring player performance, ratings, and characteristics.

## Dataset Contents

The dataset consists of a single CSV (Comma-Separated Values) file named `fifa21 raw data v2.csv`. The dataset has been cleaned and transformed to enhance its usability. It now includes the following columns:

1. **ID**: Unique identifier for each player.
2. **Name**: Full name of the player.
3. **Nationality**: The player's nationality.
4. **Age**: Age of the player.
5. **OVA**: The overall rating of the player in FIFA 2021.
6. **POT**: The potential rating of the player in FIFA 2021.
7. **Club**: The club team the player belongs to.
8. **Contract Type**: The type of contract the player has with the club (Contract or Loan).
9. **Start Year**: The year the player joined the club.
10. **End Year**: The year the player left the club (if applicable).
11. **Positions**: The player's primary playing position(s).
12. **Height (cm)**: The player's height in centimeters (converted to integer).
13. **Weight (kg)**: The player's weight in kilograms (converted to integer).
14. **Preferred Foot**: The player's preferred foot for kicking (left or right).
15. **BOV**: Best Overall Rating.
16. **Best Position**: The player's best position in the game (if applicable).
17. **Joined**: The date the player joined the club.
18. **Value**: The estimated market value of the player in Euros (cleaned and converted to integer).
19. **Wage**: The player's weekly wage.
20. **Release Clause**: The release clause value for the player's contract in Euros (cleaned and converted to integer).
21. **Hits**: Number of hits or interactions related to the player.
22. **Value for Wage**: This ratio is obtained by dividing the player's "Value" by their "Wage".


## Usage

This cleaned and transformed dataset can be used for various purposes, including but not limited to:

- Analyzing player performance and ratings.
- Exploring the distribution of player attributes such as age, height, and weight.
- Investigating the relationship between player attributes and their market values or wages.
- Visualizing player nationality distribution within the dataset.
- Highly Valuable but Underpaid players. 

## Data Source

The original dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring/data). I acknowledge and thank Kaggle and the dataset provider for making this data available.

## License

This dataset is provided under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Acknowledgments

I would like to acknowledge Kaggle and the original dataset provider for making this dataset accessible. Additionally, I thank the open-source community for their valuable contributions to data cleaning and transformation.

---