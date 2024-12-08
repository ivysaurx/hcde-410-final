# hcde-410-final
An analysis of otome games and the presence of female characters in them. 
The explored problem statement is: Does the presence of more female characters increase the success of the games, and if so, what does that say about the writers?
Other research questions include: "What does that say about the possible presence of misogyny within the otome game community where the focus is typically on male characters?" and "Conversely, how do male characters within otome games impact the sales of the games?"

The applied dataset is from Kaggle, supplemented by data from ggirluriage.
Kaggle: https://www.kaggle.com/datasets/isabell2018/female-characters-in-japanese-otome-games?select=OtomeGames.csv
ggiruluriage: https://w.atwiki.jp/ggirluriage/pages/16.html

### Reading OtomeGames.csv:

| Name  | Year | Date | Copies1stWeek | CopiesTotal | Platform | Company | CERO |  NoLI | NoFemale | NoFemaleLI | NoFemaleFI | NoLGBT |  NoCDM | NoCDF |
| ------------- | ------------- |------------- | ------------- |------------- |------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Name of the game in Japanese  | The year the game was originally released  |Date the game was released (Note: the dates are NOT accurate. Ignore this column) | # of game sales in its first week after release |# of total game sales | The device the game was released to be played on (eg: Switch) | The company that published the game | CERO rating of the game (R18 games are rated Z) |  Number of love interests | Number of female main characters | Number of female love interests | Number of female friendship interests | Number of LGBTQ characters | Unknown | Unknown |

#### Extra Notes about OtomeGames.csv columns:
Date: This column is mostly innaccurate due to the nature of Japanese date formats. For example, January 2nd 2024 would be 24/01/02, in the format of YY/MM/DD. The person who labeled the data might have gotten their dates mixed up.
Copies1stWeek and CopiesTotal: One of the things to note is that if the game's platform was on PC, there are no sales recorded whatsoever. It is also important to note that some of the newer titles near the end of the dataset do not have a value for CopiesTotal (some even for Copies1stWeek) because they were still on sale in Japan during the creation of the dataset. A third thing to note about these sales is that this only includes sales in Japan and does not include sales of the games after they have been localized by non-Japanese companies, such as Aksys Games.

## How to Navigate the Files
For more information about the overall project, feel free to read **A4.ipynb**.
The first file to examine and run is **coefficients.ipynb**. The second file is **machinelearning.ipynb**. 
**coefficients.ipynb** calculates the Pearson, Spearman, and Kendall coefficients between the numerical values in the *otomegames.csv* dataset.
**machinelearning.ipynb** is intended to optimize Copies1stWeek and CopiesTotal by selecting some factors to change it.

# License
This work utilizes an MIT license.