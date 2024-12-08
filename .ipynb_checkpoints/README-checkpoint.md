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