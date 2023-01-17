# TC-Portfolio

<p>&nbsp;</p>

Toni Luomala

# Lähtötilanne

Ticorporaten alkaessa itseäni kiinnosti frontend, testaus, tietokannat ja ui/ux suunnittelu. Lähtötilanne omien taitojen osalta oli seuraavanlainen:
- Ohjelmoinnin perusteet C# -kielellä
- Frontendin perusteet (Svelte)
- Ei backend kurssia
- Perus HTML ja css osaaminen
- Pilvialustat kurssi samaan aikaan tc:n kanssa

Mikä oli sitten vahvuusalueeni? Missään en kokenyt olevani vielä todella hyvä, joten suuntauduin vain sen perusteella mikä itseäni kiinnosti eniten eli frontend. UI/UX toteutus/suunnittelu kiinnostaa, mutta en koe olevani kovin luova siinä tehtävässä. Ensimmäisen vuoden suoritin Vaasan Ammattikorkeakoulussa, joten ensimmäisen vuoden opintoni poikkesivat JAMK:in vastaavista. Koulun vaihdosta johtuen toisen vuoden kurssit olivat sekoitus ensimmäisen ja toisen vuoden pakollisia kursseja, eikä vapaasti valittaville ja täydentäville jäänyt paljoa tilaa. Ainoa ohjelmointi kursssi toisena vuotena oli Frontendin perusteet.

<p>&nbsp;</p>

# Roolit ticorporatessa

Meidän ryhmäämme kuului aluksi 5 henkilöä, mutta yksi jäi pois matkasta aivan alkuvaiheessa. Tämä aiheutti osaltaan ongelmia roolien valintaan. Rooleja oli enemmän kuin oli halukkaita niitä ottamaan. Omalta osaltani tämä meni sitten niin, että alussa roolini olivat testaus ja frontend, sitten frontend ja markkinointi, sitten pelkkä frontend. Lopullinen vaihto tapahtui projektin kolmannella viikolla, eli lopulta palattiin alkupisteeseen ja roolini olivat taas testaus ja frontend. Tämä muutos oli siis lopullinen ja siinä pysyttiin koko loppuprojektin ajan. Näin jälkeenpäin ajateltuna voin olla ihan tyytyväinen ratkaisuun.

- Pääroolina tekniikka (Frontend)
- Sivuroolina testaus 
- Olin hetken aikaa myös markkinointivastaava
- Päädyin kuitenkin takaisin testaajaksi
- Tiimissämme oli tarkoitus olla alunperin 5 henkilöä, mutta yksi jäi pois matkasta
- Osaltaan tämä aiheutti alussa hieman ongelmia roolien valintaan

<p>&nbsp;</p>

# Tekniikka (Frontend) 

Vaikka numeroiden valossa olin menestynyt melko hyvin ohjelmointi kursseilla, koin silti olevani melko "wannabe" -tasolla ohjelmoinnissa. Ehkä voisin kuvailla tätä sillä tavalla, että useasti ymmärsin koodia, kykenin muokkaamaan ja soveltamaan valmista koodia, mutta heikkouteni oli oman koodin kirjoittaminen alusta asti. Koska ryhmämme päätyi valitsemaan frontend frameworkiksi Reactin ja itselläni ei ollut siitä mitään aiempaa kokemusta, aloitin projekin opettelemalla Reactia full stack open kurssin tehtäviä suorittamalla. Tähän käytin aikaa 2 viikkoa. Tein lähes kaikki taskit jotka minulle oli määritelty zenhubiin, vain pari aivan viimeistä tehtävää jäi kesken. Opin kurssista kyllä Reactia, mutta 2 viikkoa oli hieman liian lyhyt aika itselleni opetella uusi framework. Pidempää aikaa ei tähän ollut projektia silmällä pitäen järkeä käyttää, joten aloitin aloin osallistumaan frontendin koodaamiseen lokakuun loppupuolella. 

Ensimmäisiä sovelluksen osia, joiden tekemiseen osallistuin olivat sovelluksen kirjautumis -ja rekisteröintisivut. Kirjautumissivun luontiin löytyi varsin selkeä tutoriaali, jossa näytettiin kuinka luodaan User Pool AWS Congitossa ja kuinka se saadaan toimivaksi Reactin kirjautumissivulla. Kopioin UserPoolId:n ja ClientId:n sovelluksemme AWS:n sivuilta Cognito palvelusta. Alla kuva UserLoginPage -komponentista.
![image](https://user-images.githubusercontent.com/98876593/211802905-17460b4f-37bb-4082-b8b2-18c918f99029.png)

Alla kuva UserRegisterPage -komponentista
![image](https://user-images.githubusercontent.com/98876593/212065587-7b45b103-2963-4004-9a76-81a90f007cb7.png)

Listan lisäys komponenttia tein yhdessä Villen kanssa, osan siitä parikoodauksena niin että olin itse koneella ja Ville neuvoi ja kommentoi samalla. Tällä tavoin en ollut työskennellyt koskaan aiemmin. Homma toimi suht ok pientä sekoilua lukuunottamatta. Ongelma oli ehkä siinä, että osaamistasossa oli melko suuri ero ja en toisekseen ollut tottunut työskentelemään tällä tavoin, joten se tuntui hieman oudolta. Kyseisessä komponentissa on painike, josta avautuu valikko jolla voi lisätä uuden listan itselle. Itselle täysin uutta asiaa oli mm. backendiin tehtävät pyynnöt axiosin avulla. Lisätty lista näkyy sivulla ja listaa klikkaamalla pääsee katsomaan listan sisältämiä reseptejä.

Omat listat -sivu valmiissa sovelluksessa
![image](https://user-images.githubusercontent.com/98876593/212677249-04644cd4-c728-42d1-a46b-839a37fd0c10.png)

Alla kuva OwnLists -komponentin koodista. UseEffect on funktio, jonka suoritetaan kerran siinä vaiheessa kun sivu on latautunut 
![image](https://user-images.githubusercontent.com/98876593/212067474-2fcecbbb-01eb-4b4f-828d-c27b0bbe429a.png)

Axiosilla totetutettu käyttäjän listahaku backendistä
![image](https://user-images.githubusercontent.com/98876593/212675078-5f4b0967-a6b8-49aa-94de-449962510b52.png)

Komponentin otsikko, painike ja importoitu ListModal komponentti
![image](https://user-images.githubusercontent.com/98876593/212675207-86684b89-14c4-4f8a-88f6-e8b743263432.png)

<p>&nbsp;</p>

# Testaus

Sovellusta testasimme manuaalilla testeillä, jotka oli määritelty zenhubin taskeihin, eli aina kun toiminnallisuus saatiin valmiiksi, se siirrettiin testaus osioon ja kuitattiin valmiiksi vasta kun se oli testattu toimivaksi. Tätä manuaalista testausta suorittivat kaikki tiimissämme, mutta tulimme huomaamaan projektin edetessä, että zenhubin testaus osio paisui viikko viikolta. Meillä olisi ollut tarvetta siis testata enemmän, mutta meillä ei ollut riittävästi aikaa. Itse pyrin pääsäntöisesti testaamaan valmistuneita ominaisuuksia noin kerran viikossa. Testaamisesta aiempaa kokemusta oli kertynyt vain toisen vuoden testaus kurssilta. Cypressia käytettiin kyseisellä kurssilla end to end testien tekemiseen. Paljon ei ollut enää muistissa cypressin toiminnasta, eli aika nollilta joutui aloittaa sen kanssa. Käytin testien tekemiseen yleensä omaa testausbranchia. Projektin aikana sain valmiiksi muutaman end to end testin. Vaikka testejä ei sinällään käytetty sovelluksen kehittämiseen, koska testien avulla ei löytynyt uusia bugeja, niin tällaisten testien kirjoittaminen tulisi olemaan hyödyllistä jos projektia vietäisiin pidemmälle, kuten julkaistaisiin play kaupassa. Tämä siitä syystä, että kukaan ei jaksa tehdä tällaisia testejä manuaalisesti päivittäin eikä esim. yrityksissä resurssit siihen välttämättä riittäisi. Automaattisia testejä voitaisiin ajastaa käynnistymään päivittäin jolloin saataisiin aina suoraan tieto jos testi epäonnistuu.

Testien kirjoittamisessa tuli vastaan yksi isompi ongelma: Cypress testi ei normaalisti tallenna selaimen local storagen kirjautumistietoja, jolloin testin tekeminen kirjautuneena ei onnistu. Suurin osa sovelluksen toiminnallisuuksista vaati sisään kirjautumisen ja sen takia kirjautuminen sisällytettiin useampaan testiin. Ongelmaa yritimme korjata tallentamalla kirjautumistiedot "snapshottiin" siinä kuitenkaan onnistumatta. Sain ongelman kierrettyä kirjoittamalla monta eri vaihetta yhden testin sisälle kirjautumisen jälkeen. Tämä toimi siitä syystä, että tieto kirjautumisesta nollaantuvat vain eri testien välillä. Tiesin kuitenkin, että tämä ei olisi oikea tapa kirjoittaa testejä, joten perehdyin ongelmaan vielä myöhemmin. 

Ongelmaan löytyi ratkaisu funktioiden avulla, jotka palauttavat ja tallentavat kirjautumistiedot jokaisessa testissä.
![image](https://user-images.githubusercontent.com/98876593/212105494-82b9cc74-94d4-46e6-bb26-8a704c148825.png)

Cypress reseptin lisäys end to end testi
![image](https://user-images.githubusercontent.com/98876593/212108788-39603892-c1e6-425f-a446-f82c3eb54527.png)

Yksikkötesti jossa testataan Loading komponentin renderöimää tekstiä
![image](https://user-images.githubusercontent.com/98876593/212763102-aad5b9b4-4d34-4b76-9f0f-88d1cbb323b3.png)

Miksi valitsin juuri nämä työt portfolioon? Villen oltua huomattavasti pätevämpi frontend koodari, moni komponentti jonka tekoon osallistuin meni Villen ohjeistuksessa, joko niin, että itse tein ja Ville ohjeisti tai vaihtoehtoisesti katsoin mukana Villen koodaamista samalla kun hän selitti mitä tekee ja yritin oppia samalla. Tästä syystä valitsin portfolioon ne React -komponentit joiden tekoon osallistuin kaikista eniten. Testauksesta halusin tuoda esiin yhden selkeän ongelmakohdan cypress testissä ja siihen löytyneen ratkaisun.    
 
<p>&nbsp;</p>

# Mitä opin tästä kaikesta?

Projektissa työskenteleminen oli välillä haasteellista, johtuen pitkälti siitä, että uusien asioiden opetteluun ja ongelmien selvittämiseen kului kohtuullisen paljon aikaa. Projektiin olisi ollut helpompi lähteä mukaan jos itsellä olisi ollut yksi selkeä vahvuusalue, nyt sellaista ei oikein ollut tiedossa etukäteen. Voin kuitenkin olla tyytyväinen että sain roolit tekniikasta ja testauksesta, koska samat asiat kiinnostavat edelleen myös projektin jälkeen. Projektin aikana tavoitteenani oli kehittyä koodaamisessa ja testaajan työssä. Koodaamisen osalta tämä toteutui, mutta vain osittain. Ottaen huomioon, että React oli täysin uusi framework itselle olen kyllä oppinut siitä suhteellisen paljon, mutta en koe yleisesti olevani koodarina paljoakaan parempi kuin ennen, koska koodin kirjoittaminen itsenäisesti on edelleen vaikeaa. Sovelluskehityksestä olisi vielä paljon opittavaa ja aioin vielä jatkossakin full stackia opiskella, jotta saisin varmemmin töitä. Testauksesta opin käyttämään cypressia paremmin, sekä hieman postmanin käyttöä backendin testauksessa. Tarkoitus oli kirjoittaa myös yksikkötestejä, mutta ne jäivät aivan projektin loppuvaiheeseen ja vastaan tuli teknisiä ongelmia.

Jokaisena päivänä tein, tai ainakin yritin tehdä jotain projektimme eteen. Projektin aikana selkeni kuitenkin ajatus siitä miten tärkeää tiedonhakutaito on tällaisessa työssä. Toisekseen koodaamisen osalta tajusin paremmin miten tärkeää console loggaaminen on, vaikka sen kyllä tiedostin jo aiemminkin, niin kurssin aikana sen tärkeys erityisesti korostui. Kommunikointitaitoja ei voi kyllin korostaa. Kommunikointi ei tiimissämme varmasti ollut täydellistä, mutta onnistui kuitenkin sen verran hyvin, että saimme asiat yleensä hoidettua keskenään. Sain myös työtehtävieni kautta mahdollisia ideoita opinnäytetyön aiheeksi. Tällä hetkellä suunnitelmissa olisi hakea työtehtäviä todennäköisimmin testaajana.

- Uutta frontend frameworkia, koska React ei ollut aiemmin tuttu

- Hieman postmanin käyttöä

- Gitin käyttäminen tuli tutummaksi

- Lisää testauksesta. Cyppressia olin käyttänyt aiemmin, mutta melko vähän, joten sain siitä lisää kokemusta

- Tiimityöskentely voi olla välillä vaikeaa

- Scrumin käytänteet


Voit kirjoittaa tavoitteista lisää 





