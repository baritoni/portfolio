Toni Luomala <br>
HTK20S1, AA4498 <br>
toni.luomala@protonmail.com

# Ticorporate kurssin Portfolio


Ticorporate on JAMK:in tietojenkäsittely tutkintoon kuuluva n. 4kk:n pituinen projektinhallintaa käsittelevä kurssi, jonka aikana kehitetään muutaman hengen ryhmässä joko sovellus tai peli. Ryhmämme kehittämä sovellus on Brita nimeä käyttävä reseptisovellus.  

![image](https://user-images.githubusercontent.com/98876593/213166634-cd94a286-5897-47ca-bb5d-a435f7770582.png)

sovelluksen kotisivut: https://britareseptipankki.wixsite.com/brita


# Lähtötilanne

Ticorporaten alkaessa itseäni kiinnosti frontend, testaus, tietokannat ja ui/ux suunnittelu. Lähtötilanne omien taitojen osalta oli seuraavanlainen:
- Ohjelmoinnin perusteet C# -kielellä
- Frontendin perusteet (Svelte)
- Ei backend kurssia
- Perus HTML ja css osaaminen
- Pilvialustat kurssi samaan aikaan tc:n kanssa

Mikä oli sitten vahvuusalueeni? Missään en kokenut olevani vielä todella hyvä, mutta frontendista oli kokemusta jo Sveltestä ja frontendin toteuttaminen kiiinnosti itseäni edelleen. UI/UX toteutus/suunnittelu kiinnostaa, mutta en koe olevani kovin luova siinä tehtävässä. Ensimmäisen vuoden suoritin Vaasan Ammattikorkeakoulussa, joten ensimmäisen vuoden opintoni poikkesivat JAMK:in vastaavista. Koulun vaihdosta johtuen toisen vuoden kurssit olivat sekoitus ensimmäisen ja toisen vuoden pakollisia kursseja, eikä vapaasti valittaville ja täydentäville jäänyt paljoa tilaa. Ainoa ohjelmointi kursssi toisena vuotena oli Frontendin perusteet. Tavoitteitteekseni asetin itselle oppia koodaamaan paremmmin, lisää testauksesta sekä myös ryhmätyötaitoja.

<p>&nbsp;</p>

# Roolit ticorporatessa

Meidän ryhmäämme kuului aluksi 5 henkilöä, mutta yksi jäi pois matkasta aivan alkuvaiheessa. Tämä aiheutti osaltaan ongelmia roolien valintaan. Rooleja oli enemmän kuin oli halukkaita niitä ottamaan. Omalta osaltani tämä meni sitten niin, että alussa roolini olivat testaus ja frontend, sitten frontend ja markkinointi, sitten pelkkä frontend. Lopullinen vaihto tapahtui projektin kolmannella viikolla, eli lopulta palattiin alkupisteeseen ja roolini olivat taas testaus ja frontend. Tämä muutos oli siis lopullinen ja siinä pysyttiin koko loppuprojektin ajan. Näin jälkeenpäin ajateltuna voin olla ihan tyytyväinen ratkaisuun. Vaikka testaus oli sivurooli, niin todellisuudessa käytin siihen kuitenkin hieman enemmän kuin 20% työajasta.

- Pääroolina tekniikka (Frontend)
- Sivuroolina testaus 
- Olin hetken aikaa myös markkinointivastaava
- Päädyin kuitenkin takaisin testaajaksi
- Tiimissämme oli tarkoitus olla alunperin 5 henkilöä, mutta yksi jäi pois matkasta
- Osaltaan tämä aiheutti alussa hieman ongelmia roolien valintaan

<p>&nbsp;</p>

# Tekniikka (Frontend) 

- Javascript kirjastona React

- Uuden tekniikan opettelua

- Lähinnä apukoodarina, vaikka frontend oli päärooli


Vaikka numeroiden valossa olin menestynyt melko hyvin ohjelmointi kursseilla en silti kokenut olevani ohjelmoinnissa kovin hyvä. Ehkä voisin kuvailla tätä sillä tavalla, että useasti ymmärsin koodia, kykenin muokkaamaan ja soveltamaan valmista koodia, mutta heikkouteni oli oman koodin kirjoittaminen alusta asti. Koska ryhmämme päätyi valitsemaan frontend frameworkiksi Reactin ja itselläni ei ollut siitä mitään aiempaa kokemusta, aloitin projekin opettelemalla Reactia full stack open kurssin tehtäviä suorittamalla. Tähän käytin aikaa 2 viikkoa. Tein lähes kaikki "spiket" jotka minulle oli määritelty zenhubiin, vain pari aivan viimeistä tehtävää jäi kesken. Opin kurssista kyllä Reactia, mutta 2 viikkoa oli hieman liian lyhyt aika itselleni opetella uusi framework. Pidempää aikaa ei tähän ollut projektia silmällä pitäen järkeä käyttää, joten aloitin aloin osallistumaan frontendin koodaamiseen lokakuun loppupuolella. 

Ensimmäisiä sovelluksen osia, joiden tekemiseen osallistuin olivat sovelluksen kirjautumis -ja rekisteröintisivut. Kirjautumissivun luontiin löytyi varsin selkeä tutoriaali, jossa näytettiin kuinka luodaan User Pool AWS Cognitossa ja kuinka se saadaan toimivaksi Reactin kirjautumissivulla. Kopioin UserPoolId:n ja ClientId:n sovelluksemme AWS:n sivuilta Cognito palvelusta. Alla kuvia UserLoginPage -komponentista.

![image](https://user-images.githubusercontent.com/98876593/213171719-27ca4f04-1465-410c-8d3c-ab594946ab0c.png)


![image](https://user-images.githubusercontent.com/98876593/211802905-17460b4f-37bb-4082-b8b2-18c918f99029.png)

<p>&nbsp;</p>

Listan lisäys komponenttia tein yhdessä ryhmän toisen frontend -koodarin kanssa, osan siitä parikoodauksena niin että olin itse koneella ja toinen neuvoi ja kommentoi samalla. Tällä tavoin en ollut työskennellyt koskaan aiemmin. Homma toimi suht ok pientä sekoilua lukuunottamatta. Ongelma oli ehkä siinä, että osaamistasossa oli melko suuri ero, eli toiselle koodarille React oli paljon paremmin hallussa ja en toisekseen ollut tottunut työskentelemään tällä tavoin, joten se tuntui hieman oudolta. Kyseisessä komponentissa on painike, josta avautuu valikko jolla voi lisätä uuden listan itselle. Itselle täysin uutta asiaa oli mm. backendiin tehtävät pyynnöt axiosin avulla. Lisätty lista näkyy sivulla ja listaa klikkaamalla pääsee katsomaan listan sisältämiä reseptejä.

Omat listat -sivu valmiissa sovelluksessa
![image](https://user-images.githubusercontent.com/98876593/212677249-04644cd4-c728-42d1-a46b-839a37fd0c10.png)

<p>&nbsp;</p>

Alla kuva OwnLists -komponentin koodista. UseEffect on funktio, jonka suoritetaan kerran siinä vaiheessa kun sivu on latautunut 
![image](https://user-images.githubusercontent.com/98876593/212067474-2fcecbbb-01eb-4b4f-828d-c27b0bbe429a.png)

<p>&nbsp;</p>

Komponentin otsikko, painike ja importoitu ListModal komponentti
![image](https://user-images.githubusercontent.com/98876593/212675207-86684b89-14c4-4f8a-88f6-e8b743263432.png)

<p>&nbsp;</p>

# Testaus

- Testaussuunnitelman luonti

- Manuaalista testaamista

- End to end testejä cyppressilla

- Yksikkötestausta Jestillä

- Backendin testausta postmanilla

Sovellusta testasimme manuaalilla testeillä, jotka oli määritelty zenhubin taskeihin, eli aina kun toiminnallisuus saatiin valmiiksi, se siirrettiin testaus osioon ja kuitattiin valmiiksi vasta kun se oli testattu toimivaksi. Tätä manuaalista testausta suorittivat kaikki tiimissämme, mutta tulimme huomaamaan projektin edetessä, että zenhubin testaus osio paisui viikko viikolta. Meillä olisi ollut tarvetta siis testata enemmän, mutta meillä ei ollut riittävästi aikaa. Itse pyrin pääsäntöisesti testaamaan valmistuneita ominaisuuksia noin kerran viikossa. Testaamisesta aiempaa kokemusta oli kertynyt vain toisen vuoden testaus kurssilta. Cypressia käytettiin kyseisellä kurssilla end to end testien tekemiseen. Paljon ei ollut enää muistissa cypressin toiminnasta, eli aika nollilta joutui aloittaa sen kanssa. Käytin testien tekemiseen yleensä omaa testausbranchia. Projektin aikana sain valmiiksi muutaman end to end testin. Vaikka testejä ei sinällään käytetty sovelluksen kehittämiseen, koska testien avulla ei löytynyt uusia bugeja, niin tällaisten testien kirjoittaminen tulisi olemaan hyödyllistä jos projektia vietäisiin pidemmälle esim. julkaistavaksi asti. Tämä siitä syystä, että kukaan ei jaksa tehdä tällaisia testejä manuaalisesti päivittäin eikä esim. yrityksissä resurssit siihen välttämättä riittäisi. Automaattisia testejä voitaisiin ajastaa käynnistymään päivittäin jolloin saataisiin aina suoraan tieto jos testi epäonnistuu.

Testien kirjoittamisessa tuli vastaan yksi isompi ongelma: Cypress testi ei normaalisti tallenna selaimen local storagen kirjautumistietoja, jolloin testin tekeminen kirjautuneena ei onnistu. Suurin osa sovelluksen toiminnallisuuksista vaati sisään kirjautumisen ja sen takia kirjautuminen sisällytettiin useampaan testiin. Ongelmaa yritimme korjata tallentamalla kirjautumistiedot "snapshottiin" siinä kuitenkaan onnistumatta. Sain ongelman kierrettyä kirjoittamalla monta eri vaihetta yhden testin sisälle kirjautumisen jälkeen. Tämä toimi siitä syystä, että tieto kirjautumisesta nollaantuvat vain eri testien välillä. Tiesin kuitenkin, että tämä ei olisi oikea tapa kirjoittaa testejä, joten perehdyin ongelmaan vielä myöhemmin. 

Ongelmaan löytyi ratkaisu funktioiden avulla, jotka palauttavat ja tallentavat kirjautumistiedot jokaisessa testissä.
![image](https://user-images.githubusercontent.com/98876593/212105494-82b9cc74-94d4-46e6-bb26-8a704c148825.png)

<p>&nbsp;</p><p>&nbsp;</p>

Cypress reseptin lisäys end to end testi
![image](https://user-images.githubusercontent.com/98876593/212108788-39603892-c1e6-425f-a446-f82c3eb54527.png)

<p>&nbsp;</p>

Yksikkötesti jossa testataan Loading komponentin renderöimää tekstiä
![image](https://user-images.githubusercontent.com/98876593/212763102-aad5b9b4-4d34-4b76-9f0f-88d1cbb323b3.png)

<p>&nbsp;</p>

# Mitä opin tästä kaikesta?

Projektissa työskenteleminen oli välillä haasteellista, johtuen pitkälti siitä, että uusien asioiden opetteluun ja ongelmien selvittämiseen kului kohtuullisen paljon aikaa. Projektiin olisi ollut helpompi lähteä mukaan jos käyttämämme tekniikat olisivat olleet itselle ennestään tuttuja. Sain kuitenkin samalla mahdollisuuden oppia uutta. Voin kuitenkin olla tyytyväinen että sain roolit tekniikasta ja testauksesta, koska samat asiat kiinnostavat edelleen myös projektin jälkeen. Ottaen huomioon, että React oli täysin uusi tekniikka itselle olen kyllä oppinut Reactia, mutta koodin tuottaminen on itselleni edelleen hieman hankalaa. Testauksesta opin käyttämään cypressia paremmin, sekä hieman postmanin käyttöä backendin testauksessa. Yksikkötestien kirjoittaminen jäi vähiiin koska aloitin sen vasta projektin loppuvaiheessa ja vastaan tuli teknisiä ongelmia. Tarkoituksena oli kuitenkin kirjoittaa yksikkötestejä jossain vaiheessa projektia.

Jokaisena päivänä tein, tai ainakin yritin tehdä jotain projektimme eteen. Olisin toivonut saavani frontendissa vähän enemmän itsenäisesti aikaiseksi, mutta tilanne oli siinä mielessä vähän hankala kun tekniikat olivat itselle uusia. Projektin aikana selkeni kuitenkin ajatus siitä miten tärkeää tiedonhakutaito on tällaisessa työssä. Toisekseen koodaamisen osalta tajusin paremmin miten tärkeää console loggaaminen on, vaikka sen kyllä tiedostin jo aiemminkin, niin kurssin aikana sen tärkeys erityisesti korostui. Kommunikointitaitoja ei voi kyllin korostaa. Kommunikointi ei tiimissämme varmasti ollut täydellistä, mutta onnistui kuitenkin sen verran hyvin, että saimme asiat yleensä hoidettua keskenään. Sain myös työtehtävieni kautta mahdollisia ideoita opinnäytetyön aiheeksi. 

- Uutta frontend frameworkia, koska React ei ollut aiemmin tuttu

- Hieman postmanin käyttöä

- Gitin käyttäminen tuli tutummaksi

- Lisää testauksesta. Cyppressia olin käyttänyt aiemmin, mutta melko vähän, joten sain siitä lisää kokemusta

- Tiimityöskentely voi olla välillä vaikeaa

- Scrumin käytänteet

<p>&nbsp;</p>

## Mitä tulevaisuudessa?

Tällä hetkellä suunnitelmissa olisi hakea työtehtäviä todennäköisimmin testaajana eli sain kurssista vahvistusta sille minkälaisiin työtehtäviin aion hakeautua. Jatkossa on tarkoitus opiskella backend sovelluskehitystä ja syventää osaamista frontendin parissa käymällä full stack open kurssia perusteellisemmin kuin se oli mahdollista ticorporaten aikana. Ticorporate oli enimmäkseen miellyttävä kurssi jonka aikana sai kokemusta asioista, joita ei ole ollut mahdollista muilla kursseilla saada.

- Samat asiat kiinnostaa edelleen

- Opinnäytetyö ja harjoittelu

- Kursseina full stackia ja backendia jatkossakin

- Töitä mahdollisesti testaajana tai frontend -kehittäjänä








