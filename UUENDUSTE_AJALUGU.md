# KloorLauncheri uuenduste ajalugu

Viimati uuendatud: 30.08.2026
Praegune stabiilne versioon: **1.9.3**
Autor ja väljaandja: **Kloor**

See dokument koondab launcheri, KloorCore'i, API, veebilehe ja väljalaskesüsteemi olulisemad muudatused. Varasematel arendusversioonidel ei olnud alati eraldi avalikku väljalaskemärget; nende kirjeldused on taastatud lähtekoodist, andmebaasimigratsioonidest ja säilinud artefaktidest.

## 1.9.3 – lihtsam administraatori ligipääs

- Eemaldati Authenticatori/2FA seadistamine ja ühekordsed koodid.
- Administraatori õigused kontrollitakse endiselt serveris ning ohtlikud konto-, rolli- ja väljalasketoimingud nõuavad parooli.
- Windowsi installer, veebileht ja automaatuuenduste kanal uuendati versioonile 1.9.3.

## 1.9.2 – kinnitatud kontod, loojate jagamine ja turvalisem suhtlus

- Veebikonto loomine nõuab kordumatut kinnitatud e-posti; lisati ühekordsed 20-minutilised parooli taastamise lingid ja turvaline e-posti muutmine.
- Launcher seob veebis loodud Kloori konto litsentsitud Microsofti/Minecrafti kontoga ega loo enam eraldi dubleeritud kasutajat.
- Vestlusele lisati sõimufilter, kasutaja vaigistamine ja serveripoolne spämmikaitse.
- Emote Studio sai õpetuse, kohaliku galerii, salvestamise, impordi, ekspordi ja sõprade või gruppidega jagamise.
- PvP kitte saab importida, eksportida ja jagada kontrollitud privaatlingiga.
- Avaleht kuvab privaatsusseadeid järgiva online-sõprade loendi; jõudlustestide ja modianalüüside tulemused säilivad ajaloos.
- Lisati administraatoriportaal kasutajate, raportite, teadaannete, väljalasete, vigade ja auditilogi haldamiseks; ohtlikud toimingud nõuavad parooli ning saladusi ei kuvata.
- Veebilehele lisati päris funktsioonide ekraanipildid, paigaldus- ja süsteeminõuete juhendid, KloorCore'i ja loometööriistade tutvustus, olekuleht, kontoandmete juhend ning turvaraportite leht.
- Discord Rich Presence kasutab avalikku rakenduse ID-d `1543471140532650095` ja järgib launcheri mängutegevuse ning serveri jagamise privaatsuslüliteid; Discordi saladusi ega võtmeid ei salvestata.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.9.2.

## 1.9.1 – skinniga Emote Studio ja PvP kitid

- Emote Animation Studio kuvab nüüd sisselogitud Minecrafti konto päris skini.
- Lisati eelvaate pööramine, suum, animatsiooni kestus, loop-lüliti ning Neutral, Wave, Victory ja Walk asendimallid.
- Kehaosade keyframe'ide arv ja valitud keyframe on ajajoonel selgelt nähtavad.
- Keyframe'e saab lisada, ükshaaval eemaldada, valitud kehaosa kaupa puhastada või kõik korraga kustutada.
- Tühja keyframe'ide loendiga animatsioon on lubatud ja eksporditav.
- Inventory Layout Studio muudeti Minecrafti PvP kitiplaneerijaks: üheksa hotbar'i kohta, armor ja offhand.
- PvP esemeid saab valida või lohistada õigesse pessa, lisada kohandatud item ID ning paremklõpsuga pesa puhastada.
- Kit salvestatakse installatsiooni kaupa ja kontrollitud JSON-failina KloorCore'i konfiguratsioonikausta.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.9.1.

## 1.9.0 – loometööriistad, turvalisemad uuendused ja kontohaldus

- Lisati Emote Animation Studio ajajoone, kuue luu pööramise, eelvaate ja KloorCore'i ekspordiga.
- Lisati Inventory Layout Studio kosmeetika ja kuni kuue lemmikemote'i paigutuste salvestamiseks.
- Lisati kohalik jõudlustest, RAM-i/JVM-i profiilid ja tõendipõhine modide probleemianalüüs.
- Modipaki eksport sisaldab nüüd täpset SHA-256 lockfile'i; import kontrollib iga faili.
- Modide hulgiuuendus teeb enne muudatusi snapshot'i, kontrollib tulemust ja taastab vea korral vana oleku.
- Sõbrakutsega saab jagada täpse modipaki ning ühe vajutusega selle sünkroonida ja serveriga liituda.
- Skin Studio sai konto kaupa ajaloo, lemmikud ja turvalise versioonide taastamise.
- Lisati kohalik serveritööruum, launcheri saavutused, värvipimeduse režiimid ja klaviatuuri kiirklahvid.
- KloorCore'i emote-ratas toetab lemmikuid ning kohalikult eksporditud kohandatud emote'e.
- Lisati seadme vanemlik kontroll suhtlusfunktsioonide ja vabatahtlike preemiareklaamide piiramiseks.
- Lisati kontoandmete JSON-eksport ja parooliga kinnitatud täielik Kloori konto kustutamine.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.9.0.

## 1.8.5 – ühe klõpsuga 3D-joonistamine

- 3D-mudelil kehaosale vajutamine valib kehaosa ja värvib esimese piksli kohe sama vajutusega.
- Joonistuslohistus lukustub vajutatud kehaosale ega värvi kõrvalolevaid kehaosi.
- Skin Studio juhendtekst kirjeldab nüüd vasakklõpsuga joonistamist ja paremklõpsuga pööramist.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.5.

## 1.8.4 – suurem Skin Studio tööala

- Skin Studio ülemine kirjeldus eemaldati, et joonistusalale jääks rohkem ruumi.
- Vasaku redaktorikaardi vertikaalne kerimine eemaldati.
- 3D-mudeli tööala sobitub nüüd automaatselt saadaoleva kõrgusega.
- Mudeli hiirerattaga suumimine ei liiguta enam redaktorikaarti üles ega alla.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.4.

## 1.8.3 – kompaktsem Skin Studio menüü

- Kehaosade valik kujundati ümber kompaktseks kaheveeruliseks kaardimenüüks.
- Kehaosa nimi ja nähtavuse nupp paiknevad nüüd samal real.
- Aktiivsel, peidetud ja hiirega valitud kehaosal on selgem visuaalne olek.
- Väikse akna jaoks lisati automaatne üheveeruline paigutus.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.3.

## 1.8.2 – korrastatud Minecrafti menüü

- Skin Studio eemaldati vasaku külgriba Minecrafti alammenüüst.
- Skin Studio jääb avatavaks konto täisvaate kaudu.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.2.

## 1.8.1 – eraldi kontovaade

- Külgriba profiiliikoon avab nüüd launcheri paremas osas täismõõdus kontovaate senise väikese hüpikmenüü asemel.
- Kontovaates kuvatakse Kloori profiil, Minecrafti kasutaja, olek ja salvestatud Microsofti kontod.
- Kontovaates saab kontot vahetada, Microsofti konto lisada, aktiivse konto eemaldada ning avada profiiliseaded, sõbrad ja Skin Studio.
- Lisati kitsama akna jaoks üheveeruline responsiivne paigutus ja aktiivse profiiliikooni visuaalne olek.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.1.

## 1.8.0 – grupivestlus ja suur tööriistauuendus

- Kontoportaal kujundati ümber kompaktse profiilipäise, krediidisaldo, ikoonidega navigeerimise, viimistletud otsingu, sõbrakaartide ja eraldi grupivestluse külgribaga; Shop jagati eraldi Themes, Auras ja Emotes kategooriateks ning mobiilivaates on paigutus responsiivne.
- Veebilehele lisati Affiliates leht loojatele, Minecrafti kogukondadele ja mänguveebidele koos kandideerimisjuhiste, partnerireeglite ning ülemise menüü ja jaluse otseteega.
- Affiliates lehe ülaossa lisati selgelt märgistatud Virtuaal.com ja FinnishHosti sponsoreeritud partneribännerid; FinnishHosti bänner kohandati tumeda lehe jaoks mustale taustale ja anti vahemälukindel failinimi ning pildid teenindatakse kloor.eu-st.
- Veebilehele lisati sisselogitud kontoportaal koos Kloor Crediti saldo, täieliku kosmeetika- ja emoodipoe, ostmise ning varustamisega.
- Veebiportaalis saab otsida kasutajaid, hallata sõbrakutseid ja sõpru, blokeerida kasutajaid ning näha privaatsusseadetega piiratud kohalolekut.
- Veebiportaalis töötavad privaatsõnumid, grupivestlused, teavitused ning konto privaatsus- ja kutsete seaded.
- Veebisessioonile lisati eraldi piiratud õigustega API; see ei saa käivitada Minecrafti, teenida mängukäivituse krediite ega kasutada launcheri failifunktsioone.
- Arvuti kohalikke faile vajavad paigaldused, modid, shaderid, Skin Studio, maailmavarundused ja pilvesünkroon jäävad turvaliselt desktop-launcherisse ning on portaalis selgelt märgitud.
- Veebilehel saab nüüd luua Kloori kasutaja; parool räsitakse API serveris Argon2id-ga ning veebimajutus ei säilita parooli ega API saladusi.
- Sisselogimata külastaja näeb konto loomise vaadet ning launcheri allalaadimise link nõuab kehtivat serveripoolset veebisessiooni.
- Veebis loodud konto ühendatakse launcheris sama kasutajanime ja parooliga Microsofti kaudu kinnitatud Minecrafti identiteediga; olemasolev veebisessioon säilib.
- Konto ühendamine keeldub automaatselt andmeid sisaldavat või juba Minecraftiga seotud kontot liitmast, vältides profiilide ja krediitide kaotsiminekut.
- Registreerimise piirang kasutab veebimajutuse allkirjastatud anonüümset kliendivõtit, mitte avalikku IP-aadressi ega ühist veebiserveri limiiti.
- Veebilehele lisati grupivestluse, Skin Studio ja sisubrauseri uued funktsioonikaardid.
- Pärast veebilehel sisselogimist avatakse nüüd avaleht, mitte konto ülevaade.
- Lisati kuni 20 liikmega grupivestlused, grupi loomine, sõprade lisamine, lahkumine, omaniku kustutamine ja reaalajas sõnumid.
- Grupivestlus töötab launcheris ja KloorCore'i mängusiseses menüüs; sõnumeid saab blokeerimise ja raporteerimise tööriistadega hallata.
- API kontrollib liikmelisust, sõprust ja blokeeringuid serveris, piirab sõnumite pikkust ning säilitab vestlusajaloo 30 päeva.
- Kasutaja blokeerimine eemaldab blokeeritud osapoole jagatud grupist ning server takistab blokeeringust möödumist grupisõnumitega.
- Skin Studio sai täitevahendi, pipeti, peegeljoonistuse, värvipaleti, kehakihtide nähtavuse, vastaspoole kopeerimise ja valmis originaalmallid.
- Skin Studio salvestab mustandi automaatselt konto kaupa, kuvab enne/pärast võrdluse ning takistab vigase läbipaistva baaskihiga skini rakendamist.
- Allalaadimised kasutavad kahe paralleelse tööga järjekorda; ootel töö saab ette tõsta või katkestada.
- Olemasolevad modikonfliktide audit, kõigi modide uuendus, Kloori modpacki eksport/import, installatsiooni parandus, teavituskeskus, serveriajalugu, sõbrakutsed ja automaatuuendus seoti uue töövooga.
- Parandati sundvärvide, fookuse ja ekraanilugeja olekute tuge.
- KloorCore'i mõlema toetatud Minecrafti versiooni kontrollsummaga JAR-id ehitati uuesti.
- MariaDB grupivestluse migratsioon ja API versioon paigaldati varukoopia ning järelkontrolliga.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.8.0.

## 1.7.4 – Skin Studio kehaosa lukustus

- Valitud kehaosalt lohistamine ei värvi enam kõrvalolevaid kehaosi.
- Kehaosa piirang kehtib nüüd nii 3D-mudelil kui ka täpsemas 2D tekstuurikaardis.
- Mitmepiksliline pintsel muudab ainult valitud kehaosa tekstuuripiksleid.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.7.4.

## 1.7.3 – Skin Studio paigutus

- Skin Studio hoiab kehaosa valiku ka launcheri minimaalses aknas mudelist paremal.
- Põhilehe kerimisriba on peidetud; väiksema kõrguse korral kerivad ainult redaktori kaardid ja mudeli suum ei liiguta neid.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.7.3.

## 1.7.2 – Skin Studio kehaosad

- Skin Studio leht ei keri enam mudeli hiirerattaga suumimise ajal üles ega alla.
- Paremalt paneelilt saab valida kogu keha, pea, keha, mõlemad käed ja mõlemad jalad eraldi.
- Mehikesel kehaosale klõpsamine valib selle enne joonistamist ning teised osad tuhmuvad selgeks fookuseks.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.7.2.

## 1.7.1 – Skin Studio kaamera

- Parema hiireklahviga lohistamine pöörab tegelast nüüd korraga horisontaalselt ja vertikaalselt.
- Hiireratas, pluss-/miinusklahvid ja eraldi nupud muudavad sujuvalt vaate suurust.
- Algvaade on kaugem ning Reset taastab pöörde, kalde ja suumi koos.
- Nooleklahvidega saab mudelit pöörata kõigis neljas suunas.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.7.1.

## 1.7.0 – pööratav 3D Skin Studio

- Skin Studio põhivaade on nüüd pööratav Minecrafti tegelane, mille nähtavatele kehaosadele saab otse joonistada ja kustutada.
- Mudelit saab pöörata tühjalt alalt lohistades, parema hiireklahviga lohistades, pööramisnuppudega või klaviatuuri nooleklahvidega.
- Eraldi saab muuta keha- ja pealmist kosmeetikakihti; Classic ja Slim käemudelitel on õiged tekstuurialad.
- Pikslite tabamine, sügavusjärjestus, nähtavate külgede valik ja UV-koordinaadid kontrollitakse eraldi automaattestidega.
- Täpsem 2D tekstuurikaart jäi kokkupakitava lisatööriistana alles.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.7.0.

## 1.6.9 – Skin Studio

- Launcherisse lisati 64 × 64 piksliredaktor oma Java Editioni skini loomiseks.
- Redaktor toetab värvimist, kustutamist, kolme pintslisuurust, pikslivõrku, tagasi-/edasivõtmist ning algskini taastamist.
- Skini saab turvaliselt PNG-failina importida ja eksportida ning valida Classic või Slim käemudeli.
- Kinnitatud Microsofti/Minecrafti kontole saab skini otse rakendada; konto ja Kloor API avalik skin uuendatakse pärast üleslaadimist.
- PNG sisend piiratakse ühe megabaidiga, kontrollitakse 64 × 64 mõõtmetele ning kodeeritakse enne kasutamist uuesti, eemaldades lisametaandmed.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.9.

## 1.6.8 – parandatud mängusisene KloorCore

- Mängusisene pood mahub nüüd ekraanile ka suure Minecrafti GUI skaalaga.
- Paneel, külgriba, kaardid, leheküljed ja ostukinnitus kohanduvad ekraani mõõtudega.
- Väiksemal ekraanil kuvatakse automaatselt vähem tooteid lehel, ilma servadest väljumata.
- Uued kontrollsummaga KloorCore'i JAR-id lisati Minecraft 1.21.1 ja 1.21.11 jaoks.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.8.
- Avaldati universaalne allkirjastamata macOS beta DMG Intelile ja Apple siliconile koos hoiatuse, paigaldusjuhise, allalaadimisloenduri ja SHA-256 kontrollsummaga.

## 1.6.7 – poe kategooriad

- Shopis on eraldi valikurea vaated teemadele, auradele ja emote'idele.
- Iga kategooria näitab oma toodete arvu ning ainult vastava liigi tooteid.
- Vaiketeema taastamise nupp kuvatakse ainult teemade vaates.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.7.

## 1.6.6 – täpne kontokaardi kujundus

- Kontokaart viidi näidisega vastavusse: nimi ilma `@`-märgita, ainult Online-olek ja kaks ikoonnuppu.
- Tegelase eelvaadet suurendati ning tekstiosa joondati kaardi ülemisse ossa.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.6.

## 1.6.5 – uus kontokaart

- Külgriba kontoala kuvab nüüd Minecrafti naha täispikka pikslitegelast.
- Kasutajanimi, võrguolek ning Minecrafti nimi on eraldi ja selgemalt paigutatud.
- Konto vahetamine ja väljalogimine paiknevad kaardi alumisel nupureal.
- Konto valikumenüü avaneb automaatselt kogu uue kaardi kohal.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.5.

## 1.6.4 – avalehe menüü kiht

- Installatsioonimenüü avaneb jälle allapoole ja kuvatakse avalehe kaartide peal, mitte nende taga.
- Windowsi installer, veebileht, automaatuuendused ja töölaua koopia uuendati versioonile 1.6.4.

## 1.6.3 – avalehe valikuparandus

- Avalehe installatsioonimenüü avaneb nüüd ülespoole ega jää enam kangelaspildi alumise serva taha peitu.
- Windowsi installer, veebileht, automaatuuenduste voog ja töölaua koopia uuendati versioonile 1.6.3.

## 1.6.2 – veebisisu kogud

- Avalehe installatsioonivalik asendati tumeda Kloori kujundusega rippmenüüga.
- Safe Mode paigutati eraldi avalehe paremasse ülanurka ning muudeti kompaktsemaks.
- Modide veebikogule lisati Modrinthi kõrvale CurseForge'i otsing ja turvaline paigaldus.
- Ressursipakke ja varjutajapakke saab nüüd otsida ning paigaldada otse Modrinthist või CurseForge'ist.
- CurseForge'i API-võti jääb ainult Kloor API serverisse; failidel kontrollitakse sobivust, suurust, SHA-1 räsi ja lubatud CDN-hostinime.
- Mitmefaililine CurseForge'i paigaldus kasutab ajutist ala ja ebaõnnestumisel tagasipööramist.
- Windowsi installer, veebilehe allalaadimine ja automaatuuenduste voog viidi ühtselt versioonile 1.6.2.
- Lisati püsireegel, et iga uus EXE avaldatakse pärast kontrolli ka veebilehel ning eelmine aktiivne installer eemaldatakse.

## 1.6.1 – turva- ja hooldusväljalase

- Lisati automaatne lähtekoodi turvakontroll isikuandmete, privaatvõtmete, ligipääsutunnuste ja soovimatu pildimetaandmestiku leidmiseks.
- Rakenduse veateated peidavad kodukataloogi kasutajanime, paroole, client secret väärtusi ja muid tundlikke välju.
- Avalikest linkidest ja päringu User-Agent väärtustest eemaldati isiklikud või teenusekonto tunnused.
- Pakendist eemaldati lähtekaardid, arenduseks mõeldud teegifailid ja testifailid.
- Lisati Kloori litsentsifail ning väljalaskekontroll kontrollib autorit, litsentsi, versiooni ja pakendi turvareegleid.
- Serveris keelati SSH parooliga ja root-kasutajaga sisselogimine; lubatud on võtmega autentimine.
- Serveri süsteemipaketid ja kernel uuendati ning teenuste taaskäivitus kontrolliti.
- Veebilehe, updateri, töölaua ja installeri versioon viidi ühtselt versioonile 1.6.1.
- Vanad 1.6.0 allalaadimisfailid eemaldati aktiivsetest väljalaskekataloogidest.
- Lisati keskne uuenduste ajaloo dokument ja püsiv hooldusreegel, mis nõuab selle täiendamist iga lõpetatud muudatuse järel.

## 1.6.0 – sotsiaal- ja multiplayer-süsteem

- Täielik sõbralist launcheris ja KloorCore'i mängusiseses menüüs.
- Sõbrakutsed, aktsepteerimine, eemaldamine ja blokeerimine kasutavad püsivat Kloori kasutaja ID-d.
- Lisati privaatvestlus, lugemata sõnumid ja vestluse turvaline sünkroonimine.
- Lisati serverikutsed ning ühe vajutusega liitumine.
- Enne liitumist kontrollitakse Minecrafti versiooni ja modpacki ühilduvust.
- Lisati profiilid, olekud, privaatsusseaded, raporteerimine ja modereerimisandmed.
- Lisati launcheri ja mängu teavituskeskus.
- Lisati sõbrale jagatavad modpackid, piiratud kasutusajaga ligipääsukood ja `kloorlauncher:` süvalink.
- Presence-süsteem saadab oleku ainult sõpradele ja arvestab kasutaja privaatsusseadeid.
- KloorCore sai eraldi kontrollitud buildid Minecraft 1.21.1 ja 1.21.11 jaoks.

## 1.5.x – kasutajaliides ja stabiilsus

- Vasak menüü koondati loogilistesse jaotistesse, et põhivaade oleks puhtam.
- Avalehele lisati Kloori taust, mängunupp, hiljutised sessioonid, sõprade olek ja uudised.
- Konto menüü, avatari kuvamine ja katkise skin'i varupilt parandati.
- Native-kinnituskastid asendati launcheri kujundusega modaalakendega.
- Shopi ostu järel säilitatakse lehe asukoht ja andmed uuendatakse ilma kogu vaate uuesti laadimiseta.
- Installatsiooni loomise Minecrafti versioonivalik sai otsingu, suurema nimekirja ja korrektse kerimise.
- Installatsiooni kustutamine muutus lukustatud failide ja paralleelsete toimingute suhtes turvalisemaks.
- JVM argumentide valideerimist ja kasutajasõbralikke Java veateateid parandati.
- Lisati redigeeritud diagnostikapakett, crash-analüüs ja logide tundlike väärtuste eemaldamine.

## 1.4.0 – KloorCore, emote'id ja kosmeetika

- Lisati ainult KloorLauncheriga hallatav KloorCore Fabric mod.
- KloorCore paigaldatakse sobivasse installatsiooni automaatselt ning selle SHA-256 kontrollitakse enne käivitamist.
- Lisati mängusisene menüü, emote-ratas ja kosmeetika eelvaade.
- Lisati Wave, Heart ja Sparkle emote'id ning Emerald, Frost ja Flame Aura kosmeetika.
- Mängusisene shop kasutab sama serveripoolset Kloor Crediti rahakotti nagu launcher.
- Ostud on idempotentsed: korduv vajutus ei tohi sama ostu ega krediidikulu dubleerida.
- Parandati parema Shift-klahviga avatava menüü kokkujooksmine.
- KloorCore'i ja launcheri IPC on localhost-põhine, ajaliselt piiratud ja installatsiooniga seotud.

## 1.3.x – pilvesünkroon, updater ja Fabric

### 1.3.3

- Parandati Minecrafti versioonide valik ning väga vanade ja uute versioonide kuvamine.
- Parandati vigased JVM valikud, mis põhjustasid teate „Could not create the Java Virtual Machine”.
- Installatsiooni loomise ja kustutamise dialoogid muudeti selgemaks.

### 1.3.2

- Parandati Fabrici käivitusviga, kus `KnotClient` puudus classpath'ist.
- Fabrici Maven-teegid tuletatakse nüüd koordinaatidest, laaditakse lubatud hostist ja kontrollitakse SHA-1 abil.
- Vigase vana Fabrici profiili vahemälu parandatakse automaatselt.

### 1.3.1

- Updater viidi GitHubi päringult Kloori enda HTTPS JSON-manifestile.
- „Check for updates” näitab nüüd selgelt, kas versioon on uusim, saadaval või kontroll ebaõnnestus.
- Kontrollitakse versiooni, failinime, suurust, allalaadimis-URL-i ja SHA-256 summat.
- Eemaldati kasutajale mittevajalik developer status panel.

### 1.3.0

- Lisati vabatahtlik otsast lõpuni krüpteeritud pilvesünkroon.
- Sünkroon hõlmab ainult seadeid, installatsioonipresette ja maailmade metaandmeid.
- Microsofti tokenid, Kloori parool, maailmade failid, modid ja logid ei lähe pilve.
- Lisati Safe Mode, riistvarapõhised jõudlusprofiilid ja installatsiooni snapshot/rollback.
- Lisati automaatsed maailmade varukoopiad, Modrinthi audit/update-all ja salvestusruumi puhastus.
- Lisati peatavad, jätkatavad ja kiirusepiiranguga allalaadimised.

## 1.2.x – Kloori konto, krediidid ja veebiteenus

### 1.2.7

- Parandati WebSocket presence'i esimese sõnumi ja varajase sulgemise võistlusolukorrad.
- Sõprade online-olek, mäng, server ja privaatsusmuudatused sünkroonitakse kohe.
- Lisati sõbrasündmused: kutse, aktsepteerimine, eemaldamine ja blokeerimine.

### 1.2.6

- Lisati anonüümne allalaadimiste koguarv ja privaatsust arvestav aktiivsete kasutajate arv.
- Allalaadimine loetakse ühe korra juhusliku idempotentsusvõtme abil; IP-aadressi ega kasutajat ei salvestata.

### 1.2.5

- Lisati PHP-põhine kloor.eu allalaadimis- ja kontoleht.
- Veebis saab Kloori kontoga sisse logida eraldi piiratud veebisessiooni kaudu.
- Veebitoken ei anna ligipääsu launcheri, mängu, sõprade ega krediitide muutmise API-le.
- Lisati tugevad sessiooniküpsised, CSRF-kaitse, CSP ja no-store vahemälureeglid.

### 1.2.4

- Kloori kasutaja loomisel muutus parool kohustuslikuks.
- Parool peab olema 15–128 märki ning see salvestatakse ainult soolatud Argon2id kontrollväärtusena.
- Parooli muutmine tühistab teised aktiivsed sessioonid.
- Parooliga üksi ei saa Minecrafti omandiõigust ega teenimisõigust teeselda.

### 1.2.3

- Krediitide teenimine seoti olemasoleva parooliga kaitstud Kloori profiiliga.
- Päevased ülesanded annavad serveri kontrollitud 10 + 10 Kloor Creditit päevas.
- Lisati serveripoolne idempotentsus, päevapiirid, ledger ja auditikirjed.

### 1.2.1–1.2.2

- Minecrafti nimi eraldati Kloori avalikust kasutajanimest.
- Sõbrad, blokid, sessioonid ja krediidid seoti püsiva sisemise kasutaja ID-ga.
- Minecrafti nime muutmine ei muuda enam Kloori profiili ega sõprussuhteid.
- Lisati tõstutundetu unikaalne Kloori kasutajanimi ja nime muutmise ooteaeg.

### 1.2.0

- Lisati tootmis-API, MariaDB skeem, sessioonid ja rangelt valideeritud IPC/API piirid.
- Lisati väljalaske kontrollid, SHA-256 summad, automaatne build ja pakendi turvareeglid.
- Lisati Windows NSIS, portable ja Microsoft Store'i pakendamise alused.

## 1.0.x–1.1.x – launcheri alus

- Esmane Electroni ja Reacti Windows launcher Kloori kujundusega.
- Microsofti OAuth PKCE sisselogimine ning Minecraft Java Editioni omandiõiguse kontroll.
- Vanilla installatsioonide loomine ja eraldatud mängukataloogid.
- Fabric, Forge ja NeoForge loaderite põhitugi.
- Mojangi versioonimanifest, assets, libraries, natives ja logging failide laadimine.
- Automaatne sobiva Eclipse Temurin Java runtime'i valik ja paigaldamine.
- Modpackide, modide, resource packide, shaderite ja serverite põhivaated.
- Windowsi installer, portable EXE, ikoonid ja töölaua otsetee.

## Püsivad ühilduvusreeglid

- Microsofti konto tõendab Minecraft Java Editioni omandiõigust; offline-režiim töötab ainult varem kontrollitud kontoga.
- Iga installatsioon hoiab oma modid, seaded, maailmad, resource packid ja shaderid eraldi.
- Allalaaditud failide host, suurus, tee ja avaldatud kontrollsumma valideeritakse enne lõplikku paigaldamist.
- Kloor Credits on suletud launcheri punktisüsteem: neid ei saa osta raha eest, üle kanda ega rahaks vahetada.
- KloorCore töötab ainult toetatud Minecrafti ja Fabric Loaderi kombinatsioonidega.
- Kontoandmed ja majandus jäävad serveri andmebaasi; EXE uuendamine neid ei kustuta.

## Uuendamise juhis kasutajale

1. Ava **Settings → Check for launcher updates**.
2. Kui uus versioon on saadaval, lase launcheril fail alla laadida ja kontrollida.
3. Sulge enne paigaldamist töötav Minecraft.
4. Käivita kontrollitud installer. Olemasolev kasutajakataloog ja installatsioonid säilivad.
5. Kui automaatne uuendus ei tööta, laadi uusim EXE ainult [kloor.eu](https://kloor.eu/) lehelt.

## Väljalaske kontrollnimekiri

- Versioon on sama root- ja launcher-paketis, veebimanifestis ning failinimes.
- Testid, TypeScripti kontroll, build, sõltuvuste audit ja lähtekoodi turvakontroll läbivad.
- EXE tegelik suurus ja SHA-256 kattuvad veebimanifesti ning `.sha256` failiga.
- Pakend ei sisalda lähtekaarte, testifaile, saladusi ega tundlikke kasutajateid.
- API migratsioonid, varukoopia, health endpoint, WebSocket ja rollback kontrollitakse.
- Avalik Windowsi väljalase peab olema Authenticode-allkirjastatud; macOS build peab olema allkirjastatud ja notariseeritud.
- Privaatsus-, kasutustingimuste ja reward-reeglite versioonid peavad vastama serveri konfiguratsioonile.

## Teadaolevad väljalaskeblokeerijad

- Windowsi avalik EXE vajab veel usaldatud Authenticode koodiallkirja.
- Privaatsus- ja kasutustingimuste dokumentides tuleb täita väljaandja juriidiline nimi ning postiaadress.
- Kahe päris kasutajaga täielik multiplayer-test tuleb teha enne suure sotsiaalfunktsioonide väljalaske kinnitamist.
