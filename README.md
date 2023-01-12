# TC-Portfolio
# Lähtötilanne

Ticorporaten alkaessa itseäni kiinnosti frontend, testaus, tietokannat ja ui/ux suunnittelu. Lähtötilanne omien taitojen osalta oli seuraavanlainen:
- Ohjelmoinnin perusteet C# -kielellä
- Frontendin perusteet (Svelte)
- Ei backend kurssia
- Perus HTML ja css osaaminen
- Pilvialustat kurssi samaan aikaan tc:n kanssa
- Tietokantojen perusteet

Mikä oli sitten vahvuusalueeni? Missään en kokenyt olevani vielä varsinaisesti hyvä, kykenin suuntautumaan vain sen perusteella mikä itseäni kiinnosti eniten, joten suuntauduin frontendiin ja testaukseen. Ensimmäisen vuoden suoritin Vaasan Ammattikorkeakoulussa, joten ensimmäisen vuoden opintoni poikkesivat JAMK:in vastaavista. Koulun vaihdosta johtuen toisen vuoden kurssit olivat sekoitus ensimmäisen ja toisen vuoden pakollisia kursseja, eikä vapaasti valittaville ja täydentäville jäänyt paljoa tilaa. Ainoa ohjelmointi kursssi oli Frontendin perusteet.

# Roolit ticorporatessa

Meidän ryhmäämme kuului aluksi 5 henkilöä, mutta yksi jäi pois matkasta aivan alkuvaiheessa. Tämä aiheutti osaltaan ongelmia roolien valintaan. Rooleja oli enemmän kuin oli halukkaita niitä ottamaan. Omalta osaltani tämä meni sitten niin, että alussa roolini olivat testaus ja frontend, sitten frontend ja markkinointi, sitten pelkkä frontend. Lopullinen vaihto tapahtui projektin kolmannella viikolla, eli lopulta palattiin alkupisteeseen ja roolini olivat taas testaus ja frontend. Tämä muutos oli siis lopullinen ja siinä pysyttiin koko loppuprojektin ajan.

- Pääroolina tekniikka (Frontend)
- Sivuroolina testaus 
- Olin hetken aikaa myös markkinointivastaava
- Päädyin kuitenkin takaisin testaajaksi
- Tiimissämme oli tarkoitus olla alunperin 5 henkilöä, mutta yksi jäi pois matkasta
- Osaltaan tämä aiheutti alussa hieman ongelmia roolien valintaan

# Frontend

Vaikka numeroiden valossa olin menestynyt melko hyvin ohjelmointi kursseilla, koin silti olevani melko "wannabe" -tasolla ohjelmoinnissa. Ehkä voisin kuvailla tätä sillä tavalla, että useasti ymmärsin koodia, kykenin muokkaamaan ja soveltamaan valmista koodia, mutta heikkouteni oli oman koodin kirjoittaminen alusta asti. Koska ryhmämme päätyi valitsemaan frontend frameworkiksi Reactin ja itselläni ei ollut siitä mitään aiempaa kokemusta, aloitin projekin opettelemalla Reactia full stack open kurssin tehtäviä suorittamalla. Tähän käytin aikaa 2 viikkoa. Opin kurssista kyllä Reactia, mutta 2 viikkoa oli hieman liian lyhyt aika itselleni opetella uusi framework. Pidempää aikaa ei tähän ollut projektia silmällä pitäen järkeä käyttää, joten aloitin aloin osallistumaan frontendin koodaamiseen lokakuun loppupuolella.

Ensimmäisiä aikaansaannoksiani olivat sovelluksen rekisteröinti ja kirjautumissivut. Tarkoituksena oli luoda toiminnallisuus, jonka avulla käyttäjän antamat rekisteröintitiedot menevät AWS cognito palveluun. Tässä onnistuinkin eli sain aikaan toimivat pohjat sekä rekisteröinti, että kirjautumissivulle. Näihin löytyi kuitenkin varsin selkeät tutoriaalit youtubesta joita käytin apuna komponenttien luomiseen. Kopioin UserPoolId:n ja ClientId:n sovelluksemme AWS:n sivuilta Cognito palvelusta. Alla kuva UserLoginPage -komponentista.
![image](https://user-images.githubusercontent.com/98876593/211802905-17460b4f-37bb-4082-b8b2-18c918f99029.png)
Sivu toimi aluksi alkeellisesti niin, että console loggaamalla saimme näkyviin sivulle 

Alla kuva UserRegisterPage -komponentista
![image](https://user-images.githubusercontent.com/98876593/212065587-7b45b103-2963-4004-9a76-81a90f007cb7.png)

Alla kuva OwnLists -komponentista
![image](https://user-images.githubusercontent.com/98876593/212067474-2fcecbbb-01eb-4b4f-828d-c27b0bbe429a.png)

# Testaus

Sovellusta testasimme manuaalilla testeillä, jotka oli määritelty zenhubin taskeihin, eli aina kun toiminnallisuus saatiin valmiiksi, se siirrettiin testaus osioon ja kuitattiin valmiiksi vasta kun se oli testattu toimivaksi. Tätä manuaalista testausta suorittivat kaikki tiimissämme, mutta tulimme huomaamaan projektin edetessä, että zenhubin testaus osio paisui viikko viikolta. Meillä olisi ollut tarvetta siis testata enenmmän manuaalisesti, mutta meillä ei riittänyt aika siihen. Itse pyrin pääsäntöisesti testaamaan valmistuneita ominaisuuksia noin kerran viikossa. Testaamisesta aiempaa kokemusta oli kertynyt vain toisen vuoden testaus kurssilta. Cypressia käytettiin kyseisellä kurssilla end to end testien tekemiseen. Paljon ei ollut enää muistissa cypressin toiminnasta, eli aika nollilta joutui aloittaa sen kanssa. Käytin testien tekemiseen yleensä omaa testausbranchia. Projetkin aikana sain valmiiksi muutaman end to end testin. 



