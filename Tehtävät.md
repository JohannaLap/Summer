X) TIivistys
- Git eroaa merkittävästi muista versionhallintajärjestelmistä, siinä mielessä kuinka se käsittelee ja tallentaa dataa. Git käsittelee dataa kuin sarjana kuvakaappuksia pienoistiedostojärjestelmästä.
- Plussana että lähes kaikki Gitin toiminnot ovat paikallisia, joten ne eivät vaadi ulkoista palvelinta. Tämä antaa joustavuutta ja nopeutta. Git myös varmistaa datan eheyden tarkistamalla kaiken tallennettavan ennen tallennusta.
- Git myös keskittyy enemmän datan lisäämiseen, kuin sen poistamiseen tai muokkaamiseen. Useimmat toiminnoista lisäävät dataa tietokantaan.
- Tiedostot ja hakemistojen tilat voivat olla joko: modified, staged, commited 
- Gitin käytössä oleellisimmat komennot ovat: gitt add. && gitt commit ja git pull && git push.




a) Uusi varasto gihubiissa
![new repository](https://github.com/JohannaLap/Summer/assets/165195836/55b83552-d55a-43c7-b540-4a8661106216)

b) Varaston kloonaus ja muutokset 
Ensiksi kloonasin tekemäni uuden varaston, jonne loin sitten touch komennolla uuden teidoston. Tiedoston luonnin jälkeen lisäsin teksiä tiedostoon. 
![uusi testitiedosto](https://github.com/JohannaLap/Summer/assets/165195836/c9ad28a9-3b00-485e-9737-2e3de02fa280)

![testing](https://github.com/JohannaLap/Summer/assets/165195836/1a5ebcdc-792e-47e0-a677-139bef1f05f9)

![git push](https://github.com/JohannaLap/Summer/assets/165195836/29cd7511-8d28-4279-a3d5-0fa2779cabe6)

![github](https://github.com/JohannaLap/Summer/assets/165195836/e4bc5439-4501-40d4-9904-36bc341acbda)


c) Muutoksen teko ilman committia
Avasin tekemäni tekstitiedoston ja tein teksiin muutoksia, jotka sitten peruutin git rest --hard komennolla.
![muutosten tekeminen](https://github.com/JohannaLap/Summer/assets/165195836/18fabb06-e2ea-4c8a-b08b-04c4adab8674)
![muutosten peruutus](https://github.com/JohannaLap/Summer/assets/165195836/a79793d4-b3ba-4534-a8f8-7c0f0b639fa7)


d) Nimen ja sähköpostiosoitteen tarkastelu 
Komennolla git config --global --list komennolla tarkistin, että sähköposti ja nimi näkyvät toivotulla tavalla.
![git config --global --list](https://github.com/JohannaLap/Summer/assets/165195836/fce2dad9-0b9d-4558-8301-c2bcc5e0e40d)

Tässä vielä git log näkymä 
![git log](https://github.com/JohannaLap/Summer/assets/165195836/c859b680-ca7a-4482-b2d9-4f9afa5aa545)
