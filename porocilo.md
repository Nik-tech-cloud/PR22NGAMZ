## Podatki glede na kraj

V tem sklopu bomo analizirali podatke, ki se osedotočajo na ***lokacijo kriminalne storitve\***. Pogledali si bomo tudi kraj v povezavi z drugimi zanimivejšimi atributi. Kraj načeloma lahko določamo glede na ***upravno enoto\***, kjer je bil kriminal storjen. Prav tako pa lahko pogledamo, katera ***policijska uprava\*** je prijavila kriminal. Tu smo imeli nekaj splošnih domnev, ključna od teh pa je bila ta, da sta kriminal in število prebivalstva povezana.

### Kriminal po posameznih občinah

Najprej najsplošnejša analiza. Kje je največ kriminala. Tu smo preprosto pogledali število pojavitev kaznivih dejanj za vsako občino. Očitno je zelo veliko kriminala v občini Ljubljana. Sledi ji Murska Sobota, nato Maribor. Sklepamo lahko da imajo **večje, številnejše občine več primerov kriminala**.

Ker smo opazili tudi primere iz leta 1945 (zelo stare primere), smo pogledal še graf po letu rojstva članov naše ekipe.  S filtriranimi podatki smo dobili dovolj podobne rezultate. Gotovo so bili starejši primeri bolj redki.

Graf smo ustvarili tudi za podatke o kaznivih dijanjih po posameznih občinah po letu 2018. To smo si ogledali samo zato, da vidimo bolj sodobne podatke. Med grafi lahko opazimo da je kriminal v določenih krajih upadel. V določenih pa narastel. Lep primer tega je Novo mesto, kjer je kriminal močno narastel.

### Korelacija med stevilom prebivalstva in krajem

Ob gledanju grafa bi lahko mislili, da je Ljubljana vodilna zgolj zaradi **številčnosti prebivalstva**. Tu smo si pogledali morebitne korelacije med kriminalom in številom prebivalstva.

Te grafi so izredno zanimivi saj nam namigujejo kje so bili do danes prebivalci najbolj kriminalno povezani. Grafi prikazujejo koliko kriminala se je zgodilo na prebivalca v vsem času. In koliko kriminala se naredi na kvardatin kilometer v vsem času. Ter koliko kriminala se naredi na gostoto prebivalca. Presenečata Kočevje in Murska sobota, ki v dveh grafih stopita na prvo mesto in celo premagata Ljubljano.

Naredili smo še se graf za kriminal na prebivalca po letu 2018. Lahko opazimo da je novo mesto stopilo v ospredje. Murska soboa je na drugem mestu, Ptuj na tretjem.

### Pojavnost kriminala glede opis kraja

Naredili smo še graf, kjer smo ločili število kaznivih dejanj po opisu kraja po občinah. Kakor lahko opazimo, je kriminal najgosteje **skoncentriran okoli nastavitvenih prostorov**, kar je obratno od prepričanja, da se kriminal najpogosteje dogaja na nekih temačnih ulicah, kjer bogate pare ropajo berači (Batman).

### Kriminal po policijskih upravah

Zanimalo nas je tudi katera policijska uprava ima največ dela s kriminalci. Podobno kot pri krajih, smo prešteli pojavitev števila kaznivih dejanj za vsako policijsko upravo.

Vidimo, da ima največ dela s kriminalom PU Ljubljana, na drugem mestu je Maribor, potem Celje... To je smiselno, saj se ujema z grafom kriminala po posameznih občinah.

## Podatki glede na vrsto kriminala

Pri tem delu smo analizirali podatke glede na vrsto kriminala. Cilj je bil ugotoviti, katere so najbolj pogoste vrste kriminala, ter koliko časa traja do leta zaključnega dokumenta vrste. 

V samih podatkih se nahajajo trije atributi ki skupaj opisujejo vrsto kriminalitete. Prvi atribut opisuje glavno vrsto kriminalitete, ki je lahko splošna, ali pa gospodarska. Drugi atribut nam pove, ali gre za organizirano vrsto ali ne. Tretji pa pove, ali gre za mladoletniško vrsto ali ne. Vse kombinacije teh treh atributov združimo v en sam atribut. Skupaj dobimo 8 kombinacij (splošna, gospodarska, splošna mladoletniška, splošna organizirana, gospodarska organizirana, gospodarska mladoletniška, splošna organizirana mladoletniška, gospodarska organizirana mladoletniška).

### Število kaznivih dejanj

Najprej smo analizirali katere vrste so najbolj pogoste. Iz vseh datotek smo prešteli pojavitev posamezna vrste kriminala. Te podatke smo nato vizualno prikazali z grafom. Izkazalo sej je, da je domneva o tem da je splošna vrsta kriminala najbolj pogosta, resnična. Tudi to, da po številu kaznivih dejanj splošna in gospodarska vrsta prevladata, ni presenetljivo, saj so ostale vrste, z izjemo splošne mladoletniške, zelo redke. 

Podobno smo naredili graf za število zaključenih kaznivih dejanj gleda na vrsto od leta 2009 do 2020. Pojavijo se zanimivi vzorci, ki kažejo na to, da se v določenih letih pri vseh vrstah množično zaključijo kazniva dejanja. Imamo tudi nasprotne vzorce, kjer je v določenih letih velik poudarek pri zaključku ene vrste v primerjavi z drugimi.

### Povprečno število let do zaključnega dokumenta

Sledi še vizualizacija povprečnega števila let od storitve do zaključnega dokumenta za vsako vrsto kriminala. Za ta graf smo seštevali razliko let med letom zaključnega dokumenta in letom storitve. Seštevek smo nato delili s številom pojavitev določene vrste. Graf končni podatkov je zelo zanimiv. Kazniva dejanja gospodarske vrste v povprečju rabijo več časa do zaključka kot pa kazniva dejanja splošne vrste. Prav tako lahko opazimo, da se za vse ne organizirane vrste mladoletniške porabi manj časa v primerjavi z enakovrednimi navadnimi vrstami. 