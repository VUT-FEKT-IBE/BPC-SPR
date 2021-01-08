# BPC-SPR
Otázky a odpovědi na SW právo.


### Jaká práva má autor počítačového programu a jak jsou tato autorská práva omezena? Jaké jsou varianty výkonu v těchto práv v závislosti na způsobu vzniku počítačového programu (školní dílo, zaměstnanecké dílo, spoluautorské dílo)?

Počítačový program není přesně definován ale popisuje se jako "program v jákekoliv formě, včetně těch, které jsou součástí technického vybavení (HW)". Jak na SK tak EU patentový úřad jej vyjadřuje jako "serii instrukcí, kterou lze spustit na PC"

Autor má autorská práva, kde jsou tyto práva chráněna podle literální dílo a to bez ohledu na fromu vyjádření. 
Ochrana pokrývá vyjádření ve formě:
  + strojový kód
  + zdrojový kód
  + jejich mezistupně
  + přípravné koncepční materiály vzniklé při vývoji
    + model archytektůry SW
    + funkční specifikace
    + apod.
Vyloučení z ochrany jsou "myšlenky a principy na nichž je založen jakýkoliv prvek PC programu, včetně těch, které jsou podkladem jeho propojení s jíným programem". Neboli není chráněna funkcionalita programu, ale pouze její objektivní vyjádření v podobě příslušného kódu.


Školní dílo (autorský zýkon §60) - škola mají za obvyklých podmínek právo na uzavření licenční smlouvy o užití díla. Pokud není závažný důvod měl by autor udělit licenci nebo bude udělena soudem.

Zaměstnanecké dílo (autorský zýkon §58) - jestliže zaměstnanec vytvoří program ke splnění svých poviností vyplívajícíh z pracovněprávního nebo služebního vztahu a neexistuje-li mezi zaměstnavatelem a zaměstnancem odlišná dohoda, zaměstnavatel vykonával k takovému programu svým jménem a na svůj účet autorova majetková práva. Pokud není dohoda odlišná tak zaměstanec současně uděluju zaměstnavateli svolení k úkonům, které by zasahovali do práv osobních.
  + spojovat s jinýmy programy
  + dále je měnit 
  + uvádět je na trh
  + vše víše bez zvláštního souhlasu zaměstnance
  
Spoluautorské/kolektivní dílo (autorský zýkon §59) je dílo, na kterém se podílí více autorů a je vytvřeno z podnětu a pod vedením FO/PO a uváděno na veřejnost pod jejím jménem. Považují se často za zaměstnanecká díla.

### Jaké jsou zákonné a judikatorní podmínky pro dovolené reverzní inženýrství software?

Dekompilace programu, není povolena v každém případě, lze provádět pouze za účelem interoperability (je schopnost různých systémů vzájemně spolupracovat, poskytovat si služby, dosáhnout vzájemné součinnosti) a je třeba provádět jen nezbytně nutné úkony. Dekompilovat lze pouze až vyčerpaní všech možností jako je obracení na autora. Platí pouze za speciálních podmínek. Při dekompilaci lze pouze provádět rozmnožovaní kódu a překlad formy kódu ve smyslu čl.4 SW směrnice - stále nebo dočasné rozmnožovaní, překlady zpracovaní, a jiné úpravy programu. Taktéž nelze dekompilovat pokud program, se kterým chceme dosáhnout inteoperability nexestuje alespon ve formě návrhu. Dále může dekompilovat pouze oprávněná osoba, nelegalní držitelé licence dekompilaci nemohou provádět. Všechny potřebné informace mohou být požity pouze k dosažení interoperability. 

### Jak mohou být právem chráněna rozhraní (datová, uživatelská, aplikační)? Je právem chráněna funkcionalita software?

Je uvedeno že myšlenky a principy na nichž je založen prvek programu nejsou chráněny autorským zákonem. SW směrnice - myšlenky a zásady na kterých je založen kterýkoliv prvek programu, nebo jeho rozhraní, nejsou chráněny. 

Datová - jedná se o rozhraní, která slouží k ukládaní a přenosu dat v určitém formátu. Dle SW směrnice tyto rozhraní nebudou chráněna. Lze uvažovat, kdyby to bylo dílo dá se uvažovat o standardní ochraně.

Uživatelská - Pokud by bylo GUI zcela převzato, mohla by být zasaženo do autorských práv ke GUI jako samostatnému autorskému dílu, nepodlehajícímu zvlašnímu režimu ochrany (viz právo prvák letní), neboli čistě GUI není chráněno až na nějaké vyjímky například. Aby bylo chráněno musí dosáhnout tvůrčího standardu.

Aplikační - Buď je nebo není chráněno autorským zákonem, že nikde není specifikováno jestli se jedná o myšlenku nebo vyjádření. SDEU neřešil ale lze předpokládat, že by to bylo podobné jako z GUI. Pokud by se jednoalo o vyjádření tak je chráněno. Momentálně Google vs Oracle, o kterém by měl soud rozhodnout v 2021. Google pro Android využil stejné API jako je v javě. V prvním řešení bylo rozhodnuto že API není chráněno. Poté odvolací soud rozhodl že API je chráněno, že byla splněna podmínka originality. Momentálně je případ u nejvyšího soudu USA.

### Jaké jsou základní rozdíly mezi autorskoprávní a patentovou ochranou? Lze chránit v ČR software jako takový? Jaké jsou podmínky patentovatelnosti vynálezu realizovaného počítačem (computer implemented invention)?

Autorskoprávní ochrana programů, je neschopna chránit funkcionalitu daného programu, neboli dokáže chránit pouze objektivní vyjádření v kódu popřípadě jeho vizuální stránku, ale funkcionalita samostatná není chráněna. K přiměřenému chránění samostatné funkcionality je použito patentová ochrana. Patentově nelze chránit počítačové programy ale tzv. vynálezi uskutečnované počítačem.  
Podmínky patentovatelnosti
  + vynález neboly ne program ale vynález realizovaný počítačem
  + novost - vynález se považuje za nový, není-li součástí stavu techniky
  + vynálezecká činost
  + průmyslová využitelnost - může li být vynález vyráběn nebo využíván ve všech odvětvých průmyslu
Obecně v ČR SW je chráněn pouze autorským zákonem pokud nespadá pod vynálezy uskutečnované počítačem ty lze chránit patenty.  
Vynálezi uskutečnované počítačem jsou udělovány i v ČR. Do této dle zákona, nelze patentovat "plány, pravidla a způsob vykonávaní duševní šinnosti, hraní her nebo vykonávání obchodní činosti, jakož i programy počítačů".
Do vynálezu realizovaného počítačem lze zahrnout počítačový program myšlený jako produkt. Podmínka je technický charakter příslušného vynálezu. Je dán jestliže je počítačový program schopný vyvolat dotatečný technický účinek, když beží na PC nebo je na něm nahrán. nesmí se jednat o běžnou interakci mezi SW a HW.  
Na konec hlavní podmínkou, že nelze patentovat SW jako takový ale musí splňovat urřité podmínky, jejich společním jmenovatelem je přítomnost dalšího technického prvku. 

### Jak lze chránit v ČR databáze? Jak Soudní dvůr Evropské unie vykládá pojem "podstatný vklad do pořízení, ověření nebo předvedení obsahu databáze" ve vztahu k přiznání ochrany zvláštním právem pořizovatele databáze?

### Může být počítačový program autorem počítačového programu? Jak se aktuálně právo staví k výtvorům umělé inteligence?

### Co je to licenční smlouva? Vyjmenujte podstatné a pravidelné náležitosti a popište účel uzavření licenční smlouvy ve vztahu k distribuci software.

Licenční smlouva je smlouva na jejíž základě poskytovatel, poskytuje oprávnění k užítí všech nebo jednotlivých způsobů užití. Nabyvatel se zavazuje, není-li sjednáno jinak, poskytnout odměnu. 
Licenční smlouva nemusí být v písemné formě. Lze ji uzavřít například ústně. Musí být uzavřena písemně pouze v případech kdy je poskytována jako výhradní. Výhradní licence autor nesmí poskytnou licenci třetí osobě a je obvykle povinen nepoužívat SW, ke kterému licenci udělil. V případě nevýhradní licence může autor použivat SW způsobem, k obsahu licence a poskytnout licence dalším osobám. 
Elektronické uzavíraní"
+ Click-wrap
  + Potvrzení před prvním užitím
+ Shrink-wrap
  + Rozbalení krabicového SW
+ Browse-wrap
  + Souhlas před stažením SW
  
Obsah licence: 
+ Základní
  + Smluvní strany
  + Specifikace autorského díla
    + předmět
    - není nutno popisovat funkcionalitu
  + Právo a způsob užití
  + Rozsah licence
  + Odměna za poskytnutí licence
  + Přiměřená dodatečná odměna
  + Délka trvaní licence
+ Ostatní
  + Právo podlicencovaní, či přeprodaní
  + Odpovědnost za škodu a právní vady SW
  + Oprávnění k rozmnožovaní nebo úpravě SW
  + Nárok na upgrade SW
  + Způsob zániku licence a postupu po zániku
  + Automatické prodlužovaní licence
  
Hlavním účelem je ochrana díla a specifikace jak s ním lze nakládat. Například jestli lze upravovat nebo předělávat SW. Nebo ho rozmnožovat popřípadě upravenou verzi licencovat. 

### Co je to smlouva o dílo? Vyjmenujte podstatné a pravidelné náležitosti a popište účel uzavření licenční smlouvy ve vztahu k vývoji software.

Obsah smlouvy o dílo:
 + Zhotovitel a zadavatel/objednatel
 + Předmět smlouvy - co chce
 + Cena
 + Termín zhotovení - do kdy + a co bude předáno
 + Předání a převzetí díla detailnější specifikace
 + Odpovědnost za vady
 + Závěrečné ustanovení
 
Je to smlouva na jejímž základě vzniká závazek, jehož předmětem je shotovení, údržba, oprava nebo úprava věci nebo činosti. Většinou se sepisuje pokud je činost financovaná zákazníkem a produkt v našem případě SW je vytvářen dle požadavků zákazníka. Často se pojí se SW na zakázku.\
Klíčovím ujednáním je specifikace předmetu plnění neboli SW. Oproti specifikaci standardního SW musí být míra specifikace o hodně rozsáhlejší a detailnější. Toto musí proběhnout, aby se předešlo sporům. Proto by specifikace neměla pokrývat pouze funkcionalitu ale také parametry, které nejsou přímo spojené s funkcionalitou ale mohou ji zásadně ovlivnit. Například HW nároky.\
Účelem uzavření licence by měla být nejen schopnost ho použivat ale i různě s ním manipulovat. Například nemežnost přeprodávat nebo poskytovat SW třetí straně. Zde se aplikuje občanský zákoník, kde má zákazník licenci možnost použivat licenci pouze za účelem sjednáneho ve smlouvě. Proto se často sjednává širší opravnění zákazníka/široká licence. Takže účel uzavření licenční smlouvy je za účelem využití daného SW, kde je specifikováno co vše s tím SW lze dělat. Například přeprodej třetím stranám, neomezené množství vlastních licencí na neomezenou dobu, nebo bránit dodavateli aby program sám užíval nebo prodával licenci jiným osobám, popřípadě právo měnit a upravovat dodaný SW. Dále lze sjednat přístup ke zdrojovým kódum + ošetřit její kvalitu (komentáře, dokumentace, atd.).

### Co je to SLA? Vyjmenujte náležitosti a popište účel uzavření SLA.

SLA - service level agreement je tzv. inominátní smlouva, která upravuje úroveň poskytovaní určité služby. Předmětem můžou být služby jako podpora, údržba a podobné spojedné s dodávkou SW, služby v oblasti cloud computingu nebo služby v oblasti telekomunikací. Často není úzavíraná samostatně, ale je spíše doplňujicí smlouva.
Typické prvky:
+ Vymezení samostatné služby, tedy její definice
  + podpora SW
  + odstrańovaní vad
  + PC program poskytovaný jako služba
+ Parametry služby a způsob vyhodnocení - důležité preciznost jejich vymezení.
  + Z pohledu parametrů je důležité přesně vymezit, kdy se využijí (vyjímka z dostupnosti pro plánované odstávce).
    + dostupnost
    + reakční doba
    + doba do odstranění závad
  + Z pohledu vyhodnocení je důležité jak bude provedeno
    + období
      - rok
      - měsíc
      - týden
      - apod
    + jaký mechanismus
      - jak bude měřena dostupnost služby
+ kreditace - klíčový prvek, forma sankce za nedodržení úrovně služby
  + podoba
    + sleva z ceny
    + smluvní pokuta - může překročit smluvní částku za službu narozdíl od slevy
    + případně délku budoucího období poskytnutí služby zdarma tzv free service days

### Jaký je rozdíl mezi zárukou a odpovědností za vady a jak se tyto typicky uplatňují u software?

### Co je podstatou softwarových veřejných licencí a jak tyto fungují po právní stránce? Kdy zvolíte jakou veřejnou softwarovou licenci a proč?

### Definujte správce osobních údajů a popište jeho základní povinnosti dle GDPR. Jaký rozdíl mezi správcem a zpracovatelem osobních údajů?

### Jakými prostředky a čeho se může domáhat autor software při zásahu do jeho autorských práv?
