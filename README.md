# REPO projecte-smx2a-2026-2027

Llista de projectes d'SMX2A del curs 2026-2027.

  - [AlmostReal](#AlmostReal), [almostreal.cat](https://almostreal.cat)
  - [GameTruk](#GameTruk), [gametruk.cat](https://gametruk.cat)
  - [GymLeveling](#GymLeveling), [gymleveling.cat](https://gymleveling.cat)
  - [IHateSpam](#IHateSpam), [ihatespam.cat](https://ihatespam.cat)
  - [La-Fusta-Lactea](#La-Fusta-Lactea), [la-fusta-lactea.cat](https://la-fusta-Lactea.cat)
  - [MyBread](#MyBread), [mybread.cat](https://mybread.cat)
  - [OfAI](#OfAI), [ofai.cat](https://ofai.cat)
  - [UnderLabs](#UnderLabs), [underlabs.cat](https://underlabs.cat)

### [AlmostReal](https://github.com/samjorge28/AlmostReal)

Esborrany Projecte AlmostReal

AlmostReal – La botiga del futur En què consisteix el projecte? AlmostReal és un projecte que busca modernitzar les botigues de roba mitjançant la tecnologia, la intel·ligència artificial i la realitat virtual. La idea principal és crear una rèplica digital en 3D d'una botiga física, que els clients puguin visitar des d'un ordinador o amb unes ulleres de realitat virtual, com si estiguessin dins de la botiga real. Per crear aquest espai virtual, es podria gravar la botiga amb un mòbil o un dron i utilitzar eines de reconstrucció 3D per generar un model inicial. Després, es podria editar amb Blender i incorporar-lo a Unreal Engine, on es crearia l'entorn interactiu. Idees i funcions principals Botiga virtual en 3D: els clients podrien caminar per la botiga virtual i veure on es troba cada peça de roba. Mode PC i realitat virtual: es podria explorar la botiga amb el teclat i el ratolí o amb ulleres de realitat virtual, per tenir una experiència més immersiva. Assistent virtual amb IA: un assistent podria respondre preguntes com ara «On són les dessuadores negres?» o «Quin conjunt em recomanes per sortir?». Recomanacions de roba: el sistema podria recomanar conjunts segons els colors, l'estil, la talla i el pressupost del client. Mapa i rutes: quan el client triés una peça, el sistema la destacaria dins de la botiga virtual i li mostraria el camí per arribar-hi. Control d'estoc: una base de dades permetria consultar els productes disponibles, les talles, els colors i la seva ubicació. Panell d'administració: els treballadors podrien gestionar els productes, actualitzar l'estoc i consultar informació de la botiga. Com es podria desenvolupar? Per fer el projecte, es podrien utilitzar diferents eines: Blender: per crear i modificar els models 3D. Unreal Engine: per construir la botiga virtual interactiva i el mode de realitat virtual. Python: per programar algunes funcions de la IA i la comunicació entre sistemes. MySQL o PostgreSQL: per guardar els productes, les talles i l'estoc. Linux Server: per allotjar els serveis i la base de dades. HTML, CSS i JavaScript: per crear el panell web d'administració. Part d'informàtica i xarxes Com que és un projecte del cicle de SMX, també es treballaria la part d'infraestructura informàtica. Es podria configurar un servidor Linux, una base de dades, una xarxa local, adreces IP, usuaris i permisos, mesures de seguretat i sistemes de monitoratge per comprovar que els serveis funcionen correctament. Objectiu final L'objectiu és crear una demostració funcional d'una botiga de roba intel·ligent on un client pugui entrar en un entorn 3D, parlar amb un assistent d'IA, rebre recomanacions i trobar els productes fàcilment. No caldria construir una botiga completa des del principi: es podria començar amb una versió petita i anar afegint funcions a mesura que avanci el projecte. AlmostReal vol demostrar com es poden combinar la realitat virtual, la intel·ligència artificial, les bases de dades, els servidors i les xarxes per crear una nova manera de comprar roba.

### [GameTruk](https://github.com/AdamHmamSetti/GameTruk)
Aquest projecte consisteix en la creació d’una petita empresa, que és un camió gaming, on la gent podrà venir a jugar a videojocs amb els seus amics, fer tornejos i passar-ho bé.

El sector on es trobarà seran en diferents festivitats en Pobles i Ciutats.

La idea és tenir un espai divertit perquè la gent pugui jugar i competir.

Perquè tot funcioni bé, necessitarem muntar una infraestructura amb una xarxa local, servidors, ordinadors, consoles i connexions a internet.

Per tenir una bona connexió utilitzàrem sis Starlink de 300 Mbps, els gestionarem amb un Ubuntu Server utilitzant el Channel Bonding que serveix combinar diferents connexions.

La xarxa estarà formada per switches, WI-FI cable Ethernet. Els PC gaming anirà amb cable Ethernet.

![Game Truck](camiongaming.png)

(Electricitat i Infraestructura)

Endolls 220 V del camió per tota l’electricitat.
Star Links posats al camió.
Infraestructura del camió perquè entri totes les coses i no interfereixi amb el medi ambient i els carrers per passar amb el camió.
Plaques solars per alimentar una part de tot el que utilitzarem.
El manteniment de les plaques solars amb neteja periòdicament i costos.
Els costos per l’electricitat, llum ventilació i els seus manteniments.
Aïllament acústic per dins del camió.
Llums led.


(Gaming i Equipament)

El manteniment de les consoles i si surten incident per exemple un mal fet amb una consola o una cosa amb càmeres i costos per l'incident
Zona Vr amb ulleres realitat virtual x2 que sortirà més de preu
Pantalla visible fora del camió pels següents tornejos, posar publicitat o per jocs com el Just Dance.
Consoles retro.
Llicències per les consoles i també pels jocs que hi hagin.


(Experiència del Client i Decoració)

Decoració i personalització del camió per fora i per dins.
Petites begudes i menjar, snacks per la gent.
seients ergonòmics fàcils de netejar i còmodes per la gent.
Lloc on la gent pugui fer fotos per les xarxes socials.
Packs per la gent que compleix anys amb coses personalitzades.


(Personal, Preus i Web)

Personal per parlar amb la gent decidir horaris, quan juga la gent i els preus que costarà per hora jugada dins del camió.
Preus i serveis.
Publicitat dins de la pàgina web.
Reserves directament per la pàgina web.



En el que ens centrarem en el nostre projecte és en un sistema de Channel Bonding per ajuntar totes les xarxes de Starlink per aconseguir ajuntar-les totes en una sola.

També ens encarregarem amb Ubuntu server i amb un hub d'Ethernet en un ordinador fer servir això amb una petita demostració de què funciona bé, fent servir el Channel Bonding.

Fer una pàgina del nostre projecte per donar a conèixer a la gent que la vegi de què tracta, amb informació del que és el GameTruk.


### [GymLeveling](https://github.com/saericdo/GymLeveling)
## Enfocament del projecte
El nostre projecte és un projecte d’un gimnàs gamificat, el seu nom és **GymLeveling**, l’objectiu del nostre gimnàs és poder anar sense sentir-se obligat, posar-te en forma i entrenar sense tenir la sensació d’estar patint, tenir la rutina d’anar al gimnàs no com una obligació, sinó com una acció que fas pel teu propi gust. A més a més, volem incentivar als joves amb la gamificació per tal que gaudeixin d’un sistema modern i divertit.

## Qui som
Som una petita empresa local anomenada **GymLeveling S.L.**, el nostre gimnàs es troba al C/ Del Torrent 21, Corçà, 17121, Girona i actualment és l’única ubicació on es pot trobar el nostre local. Darrere del projecte estem dues persones que anaven a un gimnàs convencional, i ara el nostre objectiu és implementar nous sistemes per fer del gimnàs un lloc on tinguis ganes d’anar.
## Que oferim
### Sistemes
Nosaltres oferim gamificar el gimnàs, aquí incloem diversos punts, com per exemple competicions per punts, missions, ratxes, etc. tot això estaria en una aplicació on tindries tots aquests elements i més, aquella aplicació anirà rebent actualitzacions i implementant millores, tot al seu temps.

### Millores i solucions de problemes
Això aporta una gran millora al sistema d’un gimnàs convencional, ja que hi ha elements que et faran voler anar, ja sigui perquè seràs a un dia de aconseguir alguna recompensa per la qual estàs estalviant, perquè vols completar la missió, o simplement perquè no vols perdre la teva ratxa, qualsevol que sigui la raó et motiva a anar. Evidentment, aquesta millora resol un dels principals problemes d’anar a un gimnàs per la majoria de gent, que són les ganes d’anar-hi, i a molta gent que va per motivació i ho acaba deixant, amb aquesta millora, estaràs molt més motivat cada dia per anar-hi. A més a més, si hi ha algun dia que no pots anar, et donaria una solució d’exercici per fer a casa, per sempre poder fer l’exercici necessari.


### Elements claus
Hi ha diversos elements claus que nosaltres afegim en el nostre projecte:
Una polsera identificativa i no intercanviable per cada client, que servirà per entrar al gimnàs, competir en les competicions, i tenir la possibilitat d’obtenir punts, bàsicament serà el cor de l’aplicació.
Com ja s’ha dit al punt [sistemes](#sistemes) s'afegiran missions tant diàries com setmanals, juntament amb competicions mensuals i ratxes de dies que has complert.
Correcció de tècnica en màquines i mediador del rang en funció del pes que aixequis i les repeticions que facis.
Aquests són els pilars més fonamentals del nostre projecte, però té més funcions i afegirà més funcions en un futur.

### Per qui està dirigit
El nostre projecte està dirigit per qualsevol persona que vagi o vulgui anar a un gimnàs, o fins i tot per gent que només vulguin entrenar a casa, el nostre projecte no entén d’edats ni de gènere, és vàlid per qualsevol persona que vulgui portar una vida saludable a partir de l’entrenament. L’ús seria molt simple, amb una aplicació amb una interfície molt intuïtiva i clara, i un objectiu clar, incentivar-te a anar al gimnàs.
## Quins elements inclou i no inclou el nostre projecte
El nostre projecte afegeix diferents elements, com ara
Una pàgina web
Una aplicació mòbil
Una base de dades
Uns servidors
El hardware (polseres, sensors…)
El nostre projecte no allotja:
Màquines del gimnàs
El gimnàs
Els productes reclamables
Màquines expenedores
Sistemes de seguretat

## Quins elements són fets per tercers
Dels elements que no allotgem, n’hi ha alguns que ens preparen tercers amb els que estem afiliats, com
Les màquines del gimnàs
Els productes obtenibles mediant l’aplicació mòbil
Els sistemes de seguretat
Cada tipus d’aquests elements ens els proporcionen empreses que tenim afiliades i que ens actualitzen quan és necessari.



### [IhateSpam](https://github.com/IamBrosky/ihatespam)

IHateSpam és un projecte que consisteix en crear una demo d’una IA capaç de detectar i gestionar el spam que rebem en les trucades, SMS i correus electrònics. És una idea relacionada amb la ciberseguretat que podria desenvolupar qualsevol empresa tecnològica.

Quan rebem un missatge, SMS o trucada, la IA analitza el número o correu per decidir si és spam. Si no ho és, arriba amb normalitat. Si ho detecta com a spam, respon automàticament per nosaltres en comptes de bloquejar-lo. Podem triar com respon segons un nivell de l'1 al 10 que nosaltres triarem, des de respostes educades fins a respostes més - fins i tot al punt d'insultar.

El sistema també desa els números i els correus analitzats en una base de dades per reconèixer-los en un futur. A més, permet crear una llista de contactes segurs per evitar respondre familiars, bancs o contactes importants. També inclou un filtre que detecta possibles estafes i phishing, el que fa això és evitar respondre missatges o trucades perilloses.

Finalment, tindreu una pàgina web per descarregar una extensió per als navegadors web i una aplicació des de les quals podrem configurar la IA i consultar un historial amb els missatges rebuts, les respostes enviades i el temps que hem aconseguit fer perdre les persones que ens contacten.

![Esquema](esquema_pro.png)

### [La-Fusta-Lactea](https://github.com/Imad815/la-fusta-lactea)

#### Context

La FUSTA és una fusteria que fabrica mobles a mida de manera artesanal. Els seus clients són sobretot empreses, hotels, restaurants i locals públics.
Actualment, l'empresa està poc digitalitzada i molts processos es fan de manera tradicional. Per aquest motiu, la nova direcció vol modernitzar l'empresa per millorar l'organització, reduir costos, controlar millor els processos i aprofitar millor els materials.
La FUSTA és una petita empresa que es dedica a fabricar i vendre mobles a mida. El nostre projecte és de digitalització: hem de preparar una infraestructura informàtica nova i posar en marxa sistemes nous que substitueixin els processos tradicionals.
Nosaltres, com a responsables del projecte, haurem d'analitzar les necessitats de La FUSTA i proposar una solució informàtica que ajudi a modernitzar l'empresa.

#### Descripció del sistema

##### Què aporta el sistema

Ara La FUSTA fa moltes coses a mà. La informació està repartida, es perd temps, hi ha errors i costa controlar els materials. El sistema informàtic ho vol solucionar i promet:

- Tenir tota la informació (clients, projectes, treballadors i comptabilitat) en un sol lloc.
- Treballar més ràpid i amb menys errors.
- Aprofitar millor la fusta i gastar menys.
- Controlar millor la feina i les incidències.
- Protegir les dades amb còpies de seguretat i ciberseguretat.

##### Com funciona

El sistema té aquestes parts principals:

- **Infraestructura:** espais, cables, electricitat, seguretat, xarxa i ordinadors. És la base de tot.
- **Servidor:** l'ordinador central que guarda els programes i les dades de l'empresa.
- **Programa de gestió (ERP):** serveix per portar els clients, els projectes, la comptabilitat, els treballadors i les incidències.
- **Web:** perquè els clients coneguin l'empresa i puguin contactar-hi.
- **Gestió del tall de fusta:** ajuda a planificar el tall per aprofitar bé el material.
- **Còpies de seguretat i ciberseguretat:** protegeixen les dades i els equips.

Cada persona treballa des del seu ordinador, connectat a la xarxa. El servidor guarda totes les dades i fa còpies de seguretat perquè no es perdi res.

##### Qui l'utilitza

- **Direcció i administració:** porten la comptabilitat i controlen l'empresa.
- **Personal d'oficina:** porten els clients, els projectes i els pressupostos.
- **Treballadors del taller:** consulten les feines, el tall de fusta i avisen si hi ha una incidència.
- **Clients:** miren la web per conèixer l'empresa i demanar informació.
- **Visitants:** només fan servir el Wi-Fi, que està separat de la xarxa de l'empresa.

#### Abast

El nostre projecte consisteix a crear una proposta de sistema informàtic que permeti gestionar millor les diferents àrees de La FUSTA.

##### Què entra al projecte

- La gestió de clients i projectes.
- La web.
- El tall de fusta.
- La comptabilitat.
- Els treballadors.
- Les incidències.
- Les còpies de seguretat i la ciberseguretat.
- La infraestructura necessària: equips informàtics, xarxa i cablejat.

El nostre objectiu és aconseguir un sistema segur, fàcil d'utilitzar, fiable i que pugui créixer amb l'empresa.

### MyBread

#### Context

L’idea d’aquest projecte es poder digitalitzar un Fleca. Volem crear una tecnología que faciliti la feina dels treballadors, millori l'experiència dels clients i ajudi a vendre més evitant el desperdici d’aliments.

Actualment en una fleca tradicional podem trobar diferent problemes relacionats amb l’organització de les comandes, el control dels productes, l’atenció al client i la gestió de les vendes.

##### Problemes que volem solucionar

Farem una proposta ràpida de problemes i solucions que podem donar

**Cues al comprar el pa** → Comandes anticipades i recollida, poden per exemple programar el pa cada dia a la mateixa hora

**Control de stock** → Crear un cataleg amb disponibilitat dels productes
n
**Es tira el pa a final del dia** → Ofertes d’última hora

**Les comandes van amb paper i boli** → Fer un sistema centralitzat amb la gestió de les comandes, per tindre un ordre

**S’ha de controlar l’inventari manualment** → Una gestió digital de l'estoc

**Clients que compren sempre el mateix** → Un sistema amb “comandes preferides” i recurrents, tenir un perfil dels clients amb registre de què demanen i a quines hores. També pot ajudar a fer més d’aquell producte, a posar més personal a determinades hores o a anar més ràpid alhora d’atendre

**Pot costar analitzar les vendes que es fan** → Un panell amb estadístiques, com a l’anterior, es pot ajudar a fer estadístiques sobre que compren més, a quines hores…

Amb MyBread volem solucionar aquest problemes amb una plataforma digital que conecti amb els clients i els treballadors i faciliti la gestió del negoci.




#### Abast

##### Que proposem

**Una botiga online:**

Proposem fer una botiga online, tant web com aplicació que aparegui un catàleg amb fotografíes dels productes, i on el client (i preparat també per a la gent gran, que son els principals clients del pà a primera hora) puguin de manera intuitiva el pa, l’hora de recollida i si pagar online o a botiga.

**Gestió interna:**

Fer un panell privat per als treballadors. Aquest panell estaria posat als ordinadors de la fleca, i permetria als treballadors veure comandes pendents, control·lar les existències restants, actualitzar els productes i consultar les vendes dels dies.

**Productes restants:**

A final de dia, els productes que no s’haguin venut, es poden vendre amb descompte, amb packs promoció, o ofertas d’última hora. Aixó es un programa qui et diu quins productes baixar i a quin preu. Pot arribar a estar conectat amb les estadístiques per a saber els productes que s’acaben de vendre a última hora i els que no, i baixar el necessari els que calguin.

**Fidelització:**

A la mateixa web / aplicació per a la botiga online, es pot afegir un programa de punts, cupons, descomptes al dia d’aniversari i recompenses per a clients habituals.

**Estadístiques:**

Tenir estadístiques de tot el que passi a la botiga. Poder veure les ventes del dia, quins productes s’han venut més, les hores de màxima demanda, i per exemple els productes que s’han perdut per fer de més.

**Recollida ràpida**:

El client quan fa la reserva del pa per exemple reb un codi QR, per quan vagi a la botiga a recollir la comanda, únicament calgui escanejar el codi, i treure la bossa préviament preparada, per anar molt més ràpid.

##### Objectius

Els nostres principals objectius son:

* Digitalitzar la gestió d’una panaderia
* Reduir els errors humans en les comandes i en l’inventari
* Millorar l'experiència de compra per al client
* Disminuir el desperdici d’aliments amb promocions al final de dia
* Modernitzar i reinventar un nou negoci de fleca, més modern i fàcil.

##### Arquitectura del sistema

[https\://www\.odoo.com/ca\_ES](https://www.odoo.com/ca_ES)

S’ha de tindre 2 web, una al núvol per tota la part frontend i una en local per a tota la part backend, que es connectin.

**FRONTEND \- Web per als clients**

HTML CSS

Aquesta part permetrà als clients consultar els productes, fer comandes online i gestionar les seves reserves

**BACKEND- Logística del projecte**

Amb això farem la gestió interna, les comandes i la connexió amb la base de dades.

**Base de dades**

MySQL: Clients, Productes, Comandes i Stock

També s’ha d’afegir seguretat, copias de seguretat diàries, protegir les contrasenyes, i un sistema de permisos per als treballadors i l’administrador.



### OfAI

#### 1.IDEA GENERAL
OFAI es un model d'IA personal,
destinada a brindar suport als metges (oftalmolegs) davant
consultes o si aquestos necessiten ajuda.

#### 2.INFRAESTRUCTURA
Per desenvolupar el projecte OFAI, utilitzarem les tecnologies i els components següents:

* Docker
* Web Pública
* Web Privada
* Base de Dades
* Intranet
* Models d'IA
* Maquinari

#### 2.CONTEXT
Per aquest projecte farem ús de dockers,
una web publica (una per les diferents consultes dels usuaris),
una web privada (per als professionals), una base de dades i una intranet.

També no farem ús d'un model creat per nosaltres desde 0,
si no que, en farem ús de models oberts d'us gratuit que els aconseguirem
de la web "Ollama" i veurem altres opcions per correr els models d'Inteligencia Artificial

#### 3.ABAST
L'abast del nostre projecte seria l'opinió de profesionals de l'informació que rebem de l'IA.
Perque no podem solicitar l'ajuda d'Oftalmolegs,
obviem el feedback dels professionals
al moment de veure les respostes de l'IA.

#### 4.DESENVOLUPAMENT DE L'INTELIGENCIA ARTIFICIAL
La idea es veure el desenvolupament de diferents Intel·ligencia Artificial provinents
d'un mateix hardware rebent la mateixa informació.

Aquesta mateixa s'entrenará mitjançant els casos que els oftalmolegs proporcionaran.
Una vegada ens donen l'informació els doctors donaran el seu feedback de cada resposta
i amb aquest feedback que se lis retora veure com es desenvolupen.

#### 5.FINALITAT DEL PROJECTE
La finalitat del projecte no és molt complicat.
El que nosaltres ens centrarem en veure, és en el fet de que els tres models
del mateix hardware ens donin respostes i mitjançant el feedback veure com es desenvolupen.

Al final, en una certa quantitat de temps, veure quina de les Inteligencies Artificials s'ha desenvolupat millor.
La qual, si bé no busquem que remplaci als mateixos oftalmolegs,
que fàcilitin el seu treball, descartant opcions
de quin problema pot estar patint el pacient.

Aquesta és la finalitat del nostre projecte.

### UNDERLABS
UnderLabs es una petita start-up que vol desenvolupar una plataforma tecnològica orientada al sector dels videojocs, dissenyada per oferir una solució integrada per a l’execució, la gestió i l’accés a continguts interactius de diferents entorns digitals.
El sistema disposarà d’un entorn de programari propi, compatible amb diferents formats i sistemes de distribució de videojocs, tant físics com digitals, així com amb serveis i comptes vinculats a plataformes informàtiques externes.

La comercialització dels productes i serveis es durà a terme mitjançant un portal web oficial, des del qual els usuaris podran adquirir els components físics del sistema i descarregar les solucions de programari disponibles.
Paral·lelament, es desplegarà una infraestructura de servidors destinada a proporcionar serveis de connectivitat, allotjament de sessions multijugador i gestió d’entorns de joc en línia.

Addicionalment, el projecte incorporarà una línia pròpia de perifèrics especialitzats, centrada inicialment en el disseny i la comercialització de dispositius de control adaptats a les característiques de la plataforma.
Aquests productes s’integraran dins del catàleg de la botiga en línia, amb l’objectiu d’ampliar l’oferta de solucions disponibles i garantir una major integració entre els diferents components del sistema.

En conjunt, la iniciativa pretén establir un ecosistema tecnològic integral dins de l’àmbit dels videojocs, combinant desenvolupament de programari, solucions de maquinari, serveis d’infraestructura en xarxa i perifèrics especialitzats en una única plataforma de distribució i accés.

L'abast d'aquest projecte serà el següent: el sistema de programari propi, el servidor en línea i la pàgina web.
El que no entra dins de l'abast: el maquinari on funcionarà el sistema i el perifèrics de marca pròpia.
