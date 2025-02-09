# Used-cars-AI-DA-Project
> A group assignment at JAMK. This project is in Finnish.


## Taustatietoa
Projekti toteutettiin osana JAMKin Data-analytiikka ja tekoäly -kurssimoduulia. 
Työ tehtiin ryhmätyönä ja ryhmässämme oli neljä jäsentä.
Työ toteutettiin CRISP-DM mallia noudattaen.
Tavoitteemme oli luoda koneoppimismalleja, jotka pystyisivät mahdollisimman hyvin ennustamaan niitä ominaisuuksia, jotka vaikuttavat eniten käytettyjen autojen myyntihintaan. Mallien luomisen jälkeen malleja arvioitiin ja vertailtiin keskenään, minkä jälkeen valitsimme parhaan mallin jatkoa varten.
Data oli csv-muodossa ja se sisälsi 3 miljoonaa riviä ja 66 saraketta.


## Projektin vaiheet
  1. [Business Understanding](docs/P1_business_understanding.md)
      - Alan ymmärtäminen.
      - Tavoitteiden määrittely.
      - Tämän vaiheen teimme yhdessä ryhmänä.
  2. [Data Understanding](docs/P2_data_understanding.ipynb)
      - Käytössä olevaan dataan tutustuminen.
      - Datan laadun arviointi.
      - Osuuteni oli Data quality and reporting -osuus.
  3. [Data Preparation](docs/P3_data_preparation.ipynb)
      - Datan siivous ja jäsentely.
      - Osuuteni oli kategoristen sarakkeiden muuntaminen sekä uuden dataframen ja csv-tiedoston luonti mallinnusvaihetta varten.
  4. [Modelling](docs/P4_modelling_random_forest.ipynb)
      - Käytettävien koneoppimismallien valinta.
      - Mallien toteutus ja arviointi.
      - Tulosten visualisointi.
      - Tässä vaiheessa kaikki ryhmän jäsenet tekivät omat mallinsa eri koneoppimismenetelmillä. Minä valitsin Random Forestin.
  5. [Evaluation](docs/P5_evaluation.ipynb)
      - Mallien arviointi ja vertailu toisiinsa.
      - Osuuteni oli dokumentoida tekemäni Random Forest -mallin tulokset.
  6. [Deployment](docs/P6_deployment.md)
      - Projektin tulosten käyttöönotto (vain suunnitelma).
      - Tämän vaiheen teimme yhdessä ryhmänä.
