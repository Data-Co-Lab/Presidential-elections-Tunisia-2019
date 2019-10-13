# Presidential-elections-Tunisia-2019

The goal of this project is to predict the results of the second round of the 2019 presidential elections in Tunisia based on the data of the first round of these elections. The idea is to apply Clustering, a technique of unsupervised learning in order to make two political families :

- The candidates which are similar to Kaies Saiid
- The candidates which are similar to Nabil Karoui
- The similarity is based on the electoral program, the convictions, the elective category, the number of votes, ...

## Dataset
The dataset was constructed based on information taken from the facebook pages and the reports of Sigma Conseil.

## Features

- 'TUNIS1', 'TUNIS2', 'NABEUL1','NABEUL2', 'BIZERTE', 'BEJA ', 'JANDOUBA', 'KEF', 'SELYENA','ZAGHOUANE', 'SOUSSE', 'MONESTIR', 'SFAX1', 'SFAX2', 'MAHDYA', 'GBELI','GABES', 'TATAOUINE', 'MEDNINE', 'GASSRINE ','TOZEUR', 'GAFSA','SIDI BOU', 'aryena', 'manouba', 'bnarous', 'kairwen': Number of votes in each electoral center

- '18-25', '25-46', '46-60', '60+': Electoral Age Categories of each candidate

- 'nide', 'nahdha': Party affiliations for each voter from 2014 election

- 'Myrath': Inheritance Law (Election Program: binary input)

- 'fr: Nationalization of Wealth (Election Program: binary input)

- 'RevOL': Revolutionary Category

- 'percentage': Percentage of votes in the first round

- 'choice': The intention to vote of this candidate during the second round ([0:Nabil , 1:Kaies , 0.5 no information])

- 'edu': Whether the majority of the voters are educated or not

- 'nouv': Whether the majority of the voters is voting for the first time

## Acknowledgement
This project was realized by Helmi Klai and supervised by Lilia Ennouri as part of the Engineering Department of Data Co-Lab
