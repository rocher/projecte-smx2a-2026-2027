# REPO projecte-smx2a-2026-2027

Llista de projectes d'SMX2A del curs 2026-2027.

### AlmostReal

Esborrany Projecte AlmostReal

AlmostReal – La botiga del futur En què consisteix el projecte? AlmostReal és un projecte que busca modernitzar les botigues de roba mitjançant la tecnologia, la intel·ligència artificial i la realitat virtual. La idea principal és crear una rèplica digital en 3D d'una botiga física, que els clients puguin visitar des d'un ordinador o amb unes ulleres de realitat virtual, com si estiguessin dins de la botiga real. Per crear aquest espai virtual, es podria gravar la botiga amb un mòbil o un dron i utilitzar eines de reconstrucció 3D per generar un model inicial. Després, es podria editar amb Blender i incorporar-lo a Unreal Engine, on es crearia l'entorn interactiu. Idees i funcions principals Botiga virtual en 3D: els clients podrien caminar per la botiga virtual i veure on es troba cada peça de roba. Mode PC i realitat virtual: es podria explorar la botiga amb el teclat i el ratolí o amb ulleres de realitat virtual, per tenir una experiència més immersiva. Assistent virtual amb IA: un assistent podria respondre preguntes com ara «On són les dessuadores negres?» o «Quin conjunt em recomanes per sortir?». Recomanacions de roba: el sistema podria recomanar conjunts segons els colors, l'estil, la talla i el pressupost del client. Mapa i rutes: quan el client triés una peça, el sistema la destacaria dins de la botiga virtual i li mostraria el camí per arribar-hi. Control d'estoc: una base de dades permetria consultar els productes disponibles, les talles, els colors i la seva ubicació. Panell d'administració: els treballadors podrien gestionar els productes, actualitzar l'estoc i consultar informació de la botiga. Com es podria desenvolupar? Per fer el projecte, es podrien utilitzar diferents eines: Blender: per crear i modificar els models 3D. Unreal Engine: per construir la botiga virtual interactiva i el mode de realitat virtual. Python: per programar algunes funcions de la IA i la comunicació entre sistemes. MySQL o PostgreSQL: per guardar els productes, les talles i l'estoc. Linux Server: per allotjar els serveis i la base de dades. HTML, CSS i JavaScript: per crear el panell web d'administració. Part d'informàtica i xarxes Com que és un projecte del cicle de SMX, també es treballaria la part d'infraestructura informàtica. Es podria configurar un servidor Linux, una base de dades, una xarxa local, adreces IP, usuaris i permisos, mesures de seguretat i sistemes de monitoratge per comprovar que els serveis funcionen correctament. Objectiu final L'objectiu és crear una demostració funcional d'una botiga de roba intel·ligent on un client pugui entrar en un entorn 3D, parlar amb un assistent d'IA, rebre recomanacions i trobar els productes fàcilment. No caldria construir una botiga completa des del principi: es podria començar amb una versió petita i anar afegint funcions a mesura que avanci el projecte. AlmostReal vol demostrar com es poden combinar la realitat virtual, la intel·ligència artificial, les bases de dades, els servidors i les xarxes per crear una nova manera de comprar roba.

### [Game Truk](https://github.com/AdamHmamSetti/GameTruk)

Aquest projecte consisteix un camió adaptat a videojocs i entrenament de torneijos. L’objectiu principal es crear un entorn on les persones puguin gaudir de diferents videojocs amb amics, utilizant consoles i ordinadors gaming.

El Game Truk disposara d’una infraestructura informàtica, formada per una xarxa locals, servidors, equips, consoles i sistemes de comunicació.

Ens plantegem la utilizació de sis connexions Starlink de 300 Mbps. Aquestes connexions es gestionaran en un servidor (Ubuntu server) , utilizant la tecinca del Channel Bonding.

L’infrastuctura de xarxa estara formada switshes, WI-FI i connexions Ethernet. Els ordinador gaming es conectaran a conexió ethernet.

Com a sistema operatiu dels servidors utilizarem ubuntu server, basat en el kernel de linux. Aquest sistema ens deixara gestionar serveis en xarxa , usuaris, permisos i seguretat.
![Game Truck](camiongaming.png)

(Electricitat i Infraestructura)

Endolls 220 V del camió per tota l’electricitat.
Star Links posats al camió.
Infraestructura del camió perquè entri totes les coses i no interfereixi amb el medi ambient i els carrers per passar amb el camió.
Plaques solars sota el camió per alimentar una part de tot el que utilitzarem.
El manteniment de les plaques solars amb neteja periòdicament i costos.
Els costos per l’electricitat, llum ventilació i els seus manteniments.
Aïllament acústic per dins del camió.
Llums led.
![Game Truck](Electricitat_i_Infraestructura.png)


(Gaming i Equipament)

El manteniment de les consoles i si surten incident per exemple un mal fet amb una consola o una cosa amb càmeres i costos per l'incident
Zona Vr amb ulleres realitat virtual x2 que sortirà més de preu
Pantalla visible fora del camió pels següents tornejos, posar publicitat o per jocs com el Just Dance.
Consoles retro.
Llicències per les consoles i també pels jocs que hi hagin.
![Game Truck](Gaming_i_Equipament.png)


(Experiència del Client i Decoració)

Decoració i personalització del camió per fora i per dins.
Petites begudes i menjar, snacks per la gent.
seients ergonòmics fàcils de netejar i còmodes per la gent.
Lloc on la gent pugui fer fotos per les xarxes socials.
Packs per la gent que compleix anys amb coses personalitzades.
![Game Truck](Experiència_del_Client_i_Decoració.png)


(Personal, Preus i Web)

Personal per parlar amb la gent decidir horaris, quan juga la gent i els preus que costarà per hora jugada dins del camió.
Preus i serveis.
Publicitat dins de la pàgina web.
Reserves directament per la pàgina web.
![Game Truck](Personal_Preus_i_Web.png)



### [GymLeveling](https://github.com/saericdo/GymLeveling)
Una polsera per a cada persona amb un identificador únic que serveix per entrar sortir i registrar-se en una màquina, després una lliga, amb rangs, la lliga és mensual i vas pujant llocs a mesura que guanyes punts els quals es guanyen fent la teva rutina, exercicis, reptes, Existeixen també reptes diaris i reptes setmanals, els reptes diaris et donarien el doble de punts i el setmanal el doble que el diari, El repte diari consistiria en una màquina segons la teva rutina, i el repte setmanal consistiria en una rutina d'un dia que pots fer cada setmana com per exemple un full body o fer cama full amb màquines que no s'usen, aquests reptes et donarien punts de lliga (els punts de lliga serveixen per pujar rànquing en lliga) i el setmanal et donaria punts de lliga i monedes( les monedes serveixen per quan en acumulis les suficients gastar-les en descomptes, productes, merchandising, etc.) cada dia si completes la teva rutina et donarien punts de lliga i monedes. Per a què serveix la lliga? Per incentivar la gent a anar al gym, en la qual si quedes en determinats llocs rebis diferents recompenses ex: top 1 títol exclusiu, -75% de descompte aquest mes, lot de proteïna i creatina i per exemple unes 50 monedes (les quantitats encara són indefinides), top 2 títol exclusiu, 25 monedes (les quantitats encara són indefinides), -50% de descompte aquest mes, lot de proteïna i creatina, top 3 títol exclusiu,15 monedes (les quantitats encara són indefinides), -25% de descompte aquest mes, lot de proteïna i creatina, top 4-10,10 monedes (les quantitats encara són indefinides). Important: els punts de lliga i les monedes de lliga són diferents (els punts de lliga es resetegen quan es reseteja la lliga i només serveixen per pujar llocs i guanyar les recompenses de lliga, després hi haurà experiència que et pugi de rang per fer exercicis i això un sistema normal d'experiència vaja). Finalment tenim una idea d'un sistema de ràtxa, en aquest hi ha dues diferents ràtxes, la primera ràtxa és de lliga, la qual es reseteja quan la lliga (aquesta no es reinicia quan falles un dia de rutina simplement aquest dia no compta i es queda en la mateixa ràtxa), (més ràtxa = més punts de lliga) l'altra ràtxa és una ràtxa general i aquesta es reseteja quan fallis un dia de la teva rutina (més ràtxa general = més monedes). Misions anuals i addicionals que apareixeran cada cert temps(les addicionals), les anuals consistiran en barbaritats (assisteix 100 dies al gimnàs o fes no sé quants km, etc.). Les addicionals en coses casuals (convida un amic amb aquest codi). Conseqüències: no portes polsera = no punts Cada màquina tindrà un sensor per tal que juntament amb la polsera detecti repeticions i pes, quantes voltes has fet a la bici, quants km i en quin temps has corregut a la cinta (tot això, evidentment, amb bona tècnica que serà detectada amb les càmeres… que aniran cap a una base de dades i un servidor que les recolliran i les posaran al rànquing, la lliga, etc. podràs tenir llista d'amics, lliga entre amics, lliga d'equips i la lliga global. Cada màquina tindrà el seu propi rànquing on sortiran els que més pes aixequin i més repeticions facin. La polsera també serà el mètode amb el qual pagaràs amb les monedes de l'aplicació, o sigui, tu t'apropes a la màquina expenedora i agafes un aquarius que val 50 monedes, doncs apropes la polsera, i pagues les 50 monedes.

Els productes que podràs aconseguir amb les monedes seran, begudes a la màquina expenedora, merchandising, proteïna, creatina, productes de gimnàs…

### [IhateSpam](https://github.com/IamBrosky/ihatespam)
IHateSpam és un projecte d'una IA que s'encarrega de l'spam que us arriba, tant trucades i SMS com correus. Quan entra alguna cosa, la IA mira el número o el correu i decideix si és spam. Si no ho és, t'hi arriba com sempre. Si ho és, en comptes de bloquejar-lo li contesta ella sola.

Tu tries com contesta amb un nivell de l'1 al 10. Als nivells baixos és educada però els fa perdre el temps, als mitjans els vacil·la i els segueix el rotllo, i als alts es posa vora i els insulta.

Cada número o correu de correu brossa que detecta es guarda en una base de dades, així la propera vegada que tornin les reconeix al moment. A més, l'usuari pot crear una llista de contactes segurs, que són números i correus als quals la IA mai no respon, perquè no conteste per error la teva família, el teu banc o la teva feina. També porta un filtre de seguretat: si alguna cosa sembla una estafa perillosa, com un phishing, la IA no contesta per no donar dades ni confirmar que el teu número funciona.

Tot això va a una web i una aplicació. Des d'aquí es veu un historial de quin correu brossa ha arribat, què ha respost la IA i quant de temps els ha fet perdre.
![Esquema](esquema_pro.png)

### La-Fusta-Lactea

#### Context
La FUSTA és una fusteria que fabrica mobles a mida de manera artesanal. Els seus clients són sobretot empreses, hotels, restaurants i locals públics.
Actualment, l'empresa està poc digitalitzada i molts processos es fan de manera tradicional. Per aquest motiu, la nova direcció vol modernitzar l'empresa per millorar l'organització, reduir costos, controlar millor els processos i aprofitar millor els materials.
Nosaltres, com a responsables del projecte, haurem d'analitzar les necessitats de La FUSTA i proposar una solució informàtica que ajudi a modernitzar l'empresa.

#### Abast
El nostre projecte consisteix a crear una proposta de sistema informàtic que permeti gestionar millor les diferents àrees de La FUSTA.
Inclourem la gestió de clients i projectes, la web, el tall de fusta, la comptabilitat, els treballadors, les incidències, les còpies de seguretat i la ciberseguretat.
També estudiarem la infraestructura necessària, com els equips informàtics, la xarxa i el cablejat.
El nostre objectiu és aconseguir un sistema segur, fàcil d'utilitzar, fiable i que pugui créixer amb l'empresa.

#### Infraestructura
- Espais: Creem una sala de comunicacions amb envans, on hi haurà el servidor i els switchos. Ha de ser neta, seca i tancada amb clau, lluny de la pols del taller. Hi posem aire condicionat perquè els - equips no s’escalfin.
- Cablejat: Fem servir cable Cat6 per als ordinadors i fibra òptica per al taller, perquè no té interferències. Els cables van per tubs o safates portacables, ben ordenats i etiquetats, amb punts de xarxa de sobra per créixer.
- Electricitat: Revisem els quadres elèctrics i fem circuits nous només per als equips informàtics, separats de les màquines. Contractem més potència, posem més endolls i instal·lem un SAI, que és una bateria per si hi ha un tall de llum.
- Seguretat física: Posem panys a les zones sensibles, càmeres a les entrades i al magatzem, i targetes d’identificació per controlar qui entra.
- Xarxa i equips: Instal·lem un tallafocs i separem la xarxa en zones (VLANs): oficina, taller, càmeres, servidors i visitants. Així, si un ordinador s’infecta, el problema no arriba a tot arreu. Afegim Wi-Fi professional, un servidor Linux i ordinadors per a l’oficina i el taller.

#### Per a què serveix cada cosa
##### Espais
- Sala de comunicacions: protegeix el servidor i els switchos de la pols i dels accessos no autoritzats.
- Aire condicionat: evita que els equips s'escalfin i s'espatllin.
##### Cablejat
- Cable Cat6: connecta els ordinadors a la xarxa a bona velocitat.
- Fibra òptica: uneix el taller amb l'oficina sense interferències de les màquines.
- Tubs i safates: mantenen els cables ordenats i protegits.
- Punts de xarxa de sobra: permeten créixer sense fer obres noves.
##### Electricitat
- Circuits nous: eviten que els pics de corrent de les màquines afectin els ordinadors.
- Més potència i endolls: permeten connectar tots els equips nous sense que salti el diferencial.
- SAI: manté els equips encesos si hi ha un tall de llum i dona temps per apagar-los bé sense perdre dades.
##### Seguretat física
- Panys: eviten que entri qualsevol persona a les zones sensibles.
- Càmeres: vigilen les entrades i el magatzem.
- Targetes d'identificació: controlen qui entra on i registren l'horari dels treballadors.
##### Xarxa i equips
- Tallafocs: protegeix la xarxa dels atacs que vénen d'Internet.
- VLANs: separen les zones perquè un problema en una no passi a les altres.
- Wi-Fi professional: dona connexió als dispositius, amb una xarxa separada per als visitants.
- Servidor Linux: guarda els programes i les dades de l'empresa, com l'ERP i els fitxers.
- Ordinadors: són les eines de feina del personal d'oficina i del taller.

### MyBread


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

### LucasProject
