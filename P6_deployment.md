## Phase 6 (Projektin käyttöönoton suunnitelma)

- Plan and implement deployment
    - Testasimme erilaisia koneoppimismalleja ja päädyimme käyttämään XGBoost-regressiota. Random Forest regressio on suurin piirtein yhtä tarkka, mutta XGBoost ei vaadi niin paljoa resursseja.
    - Malli julkaistaan API-rajapintana firman verkossa.
    - Varataan yrityksen pilvestä resurssi pyörittämään mallia ja API-rajapintaa.
    - Käytetään yrityksen omaa pilvipalvelua.
    - Asiakasta varten luodaan yksikertainen selainpohjainen käyttöliittymä (React/html).
    - Yrityksen sisäinen käyttö toimipisteeltä.
    - Mahdollisesti myyntipalveluna asiakkaille (esim. 5e/arvio).

- Plan monitoring
    - Seurattavia asioita ovat myyntiajat ja liiketulos.
    - Myös mallin suorituskykyä ja tarkkuutta seurataan.

- Plan maintenance
    - Mallia tullaan päivittämään uudella datalla vuosikellon mukaan.
    - Varsinkin kalliit autot ovat aliedustettuja datassa, joten niistä on kerättävä lisää dataa ja niiden hintojen ennustamista on parannettava.
    - Perustetaan git, josta workflow-toiminnolla siirretään koodi pilviresurssille. 
    - Git on sisäverkossa, joten sinne pääsee toimipisteeltä tai yrityksen VPN-yhteydellä. 
    - Luodaan skripti, joka siirtää datan tuotantoresurssille päivittäin. 

- Produce a final report
    - Lopullinen raportti on tehty PowerPoint-muotoon ja palautettu Git-repositoryyn Phase 7:n alle.

- Review project
    - Saavutimme projektin alussa asettamamme tavoitteet.
    - Opimme paljon uutta toimialasta, datan esikäsittelystä, koneoppimismallien kouluttamisesta ja kehittämisestä.
    - Käyttöönotto jäi pelkäksi suunnitelmaksi, sillä aikaa oli hyvin rajallisesti. Paremmalla ajalla käyttöönoton olisi voinut myös toteuttaa.