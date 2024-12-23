# Viinien luokittelu koneoppimismalleilla
Tässä projektissa käytetään koneoppimista, erityisesti valvottuja luokittelumalleja, ennustamaan viinin rypälelajike sen kemiallisten ja fysikaalisten ominaisuuksien perusteella. Projektissa hyödynnetään erilaisia koneoppimisen algoritmeja, jotka kykenevät oppimaan ja tekemään päätelmiä aiemmin näkemänsä datan perusteella.

## Analyysi etenee seuraavasti:
* Datan esikäsittely ja ominaisuuksien valinta: Selvitetään, mitkä viinin ominaisuudet (esim. alkoholipitoisuus, flavonoidit) vaikuttavat merkittävimmin rypälelajikkeen luokitteluun.
* Koneoppimismallien rakentaminen ja optimointi: Testataan useita luokittelualgoritmeja, kuten päätöspuu, satunnaismetsä ja logistinen regressio, ja vertaillaan niiden suorituskykyä.
* Mallien suorituskyvyn arviointi: Arvioidaan mallien tarkkuutta sekä opetus- että testidatalla ja tunnistetaan paras malli käytännön sovelluksiin.
  
## Käytetyt koneoppimismallit
* Logistinen regressio: Perustason luokittelumalli, joka arvioi todennäköisyyksiä lineaarisen suhteen avulla.
* Päätöspuu: Helposti tulkittava malli, joka luokittelee datan haarautumalla yksinkertaisten sääntöjen perusteella.
* Satunnaismetsä: Useista päätöspuista koostuva yhdistelmämalli, joka parantaa tarkkuutta ja vakautta.
* Gradient Boosting: Kehittynyt malli, joka optimoi ennusteita iteratiivisesti painottamalla virheitä.
