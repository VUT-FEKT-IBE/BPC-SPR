# BPC-SPR
Otázky a odpovědi na SW právo.


### Jaká práva má autor počítačového programu a jak jsou tato autorská práva omezena? Jaké jsou varianty výkonu v těchto práv v závislosti na způsobu vzniku počítačového programu (školní dílo, zaměstnanecké dílo, spoluautorské dílo)?

Počítačový program není přesně definován ale popisuje se jako "program v jákekoliv formě, včetně těch, které jsou součástí technického vybavení (HW)". Jak na SK tak EU patentový úřad jej vyjadřuje jako "serii instrukcí, kterou lze spustit na PC"

Autor má autorská práva, kde jsou tyto práva chráněna podle literální dílo a to bez ohledu na formu vyjádření. 
Ochrana pokrývá vyjádření ve formě:
  + strojový kód
  + zdrojový kód
  + jejich mezistupně
  + přípravné koncepční materiály vzniklé při vývoji
    + model architektůry SW
    + funkční specifikace
    + apod.
    
Vyloučení z ochrany jsou "myšlenky a principy na nichž je založen jakýkoliv prvek PC programu, včetně těch, které jsou podkladem jeho propojení s jiným programem". Neboli není chráněna funkcionalita programu, ale pouze její objektivní vyjádření v podobě příslušného kódu.

Školní dílo (autorský zákon §60) - škola má za obvyklých podmínek právo na uzavření licenční smlouvy o užití díla. Pokud není závažný důvod, měl by autor udělit licenci nebo bude udělena soudem.

Zaměstnanecké dílo (autorský zákon §58) - jestliže zaměstnanec vytvoří program ke splnění svých povinností vyplívajících z pracovněprávního nebo služebního vztahu a neexistuje-li mezi zaměstnavatelem a zaměstnancem odlišná dohoda, zaměstnavatel vykonává k takovému programu svým jménem a na svůj účet autorova majetková práva, kde je autor kompenzován nejčastěji mzdou. Pokud není dohoda odlišná tak zaměstnanec současně uděluje zaměstnavateli svolení k úkonům, které by zasahovali do práv osobních.
  + Spojovat s jinými programy
  + Dále je měnit 
  + Uvádět je na trh
  + Vše víše bez zvláštního souhlasu zaměstnance
 
Spoluautorské dílo (autorský zákon §8) je dílo na kterém se podílí více autorů, kdy všem zúčastněným autorům připadá stejné právo. O nakládaní s dílem musí být rozhodnuto jednomyslně. O spoluautorské dílo se jedná pokud jednotlivé části nejsou způsobilé samostatného užití, jedna část potřebuje druhou. Z právních úkonů jsou také vázáni společně a nerozdílně.\
Kolektivní dílo (autorský zákon §59) je dílo, na kterém se podílí více autorů a je vytvořeno z podnětu a pod vedením FO/PO a uváděno na veřejnost pod jejím jménem. Považují se často za zaměstnanecká díla.

### Jaké jsou zákonné a judikatorní podmínky pro dovolené reverzní inženýrství software?

Dekompilace programu, není povolena v každém případě, lze provádět pouze za účelem interoperability (je schopnost různých systémů vzájemně spolupracovat, poskytovat si služby, dosáhnout vzájemné součinnosti) a je třeba provádět jen nezbytně nutné úkony. Dekompilovat lze pouze až po vyčerpaní všech možností jako je obracení na autora. Platí pouze za speciálních podmínek. Při dekompilaci lze pouze provádět rozmnožovaní kódu a překlad formy kódu ve smyslu čl.4 SW směrnice - stále nebo dočasné rozmnožovaní, překlady zpracovaní, a jiné úpravy programu. Taktéž nelze dekompilovat pokud program, se kterým chceme dosáhnout interoperability neexistuje alespoň ve formě návrhu. Dále může dekompilovat pouze oprávněná osoba, nelegální držitelé licence dekompilaci nemohou provádět. Všechny potřebné informace mohou být požity pouze k dosažení interoperability. 

Oprávněný nabyvatel - může být ten kdo si program zakoupil, pronajal, získal licenci přímo od držitele práv, a i od původního oprávněného nabyvatele.\
Oprávněný uživatel - je problematická, oprávněný uživatel může být buď na základě smlouvy nebo zákona §66 (oprávněným uživatelem je oprávněný nabyvatel rozmnoženiny, který k ní má vlastnické nebo jiné právo za účelem využití). Řešil to jak nejvyšší soud ale i soudní dvůr EU, který stanovil, že se lze jednat i o jinou osobu než, z kterou to bylo uzavřeno (lze přeprodat licenci) ale původní uživatel musí odstranit SW ze svého pc a nepoužívat jej. Nejvyšší soud řešil poslané CD s licenčním klíčem.

Třístupňový test - hledaní vyjímky, musí to být jen vyjímky stanovené v zákoně, aplikace vyjímek je dovolena jen pokud to není v rozporu s užitím díla a nejsou tím nepřiměřeně dotčeny oprávněné zájmy autora. I při dovoleném reverzním inženýrství musíme projít tímto testem.

### Jak mohou být právem chráněna rozhraní (datová, uživatelská, aplikační)? Je právem chráněna funkcionalita software?

Je uvedeno že myšlenky a principy na nichž je založen prvek programu nejsou chráněny autorským zákonem. SW směrnice - myšlenky a zásady na kterých je založen kterýkoliv prvek programu, nebo jeho rozhraní, nejsou chráněny. 

Datová - jedná se o rozhraní, která slouží k ukládaní a přenosu dat v určitém formátu. Dle SW směrnice tyto rozhraní nebudou chráněna. Lze uvažovat, kdyby to bylo dílo dá se uvažovat o standardní ochraně.

Uživatelská - Pokud by bylo GUI zcela převzato, mohla by být zasaženo do autorských práv ke GUI jako samostatnému autorskému dílu, nepodléhajícímu zvláštnímu režimu ochrany (viz právo prvák letní), neboli čistě GUI není chráněno až na nějaké vyjímky například. Aby bylo chráněno musí dosáhnout tvůrčího standardu.

Aplikační - Buď je nebo není chráněno autorským zákonem, že nikde není specifikováno jestli se jedná o myšlenku nebo vyjádření. SDEU neřešil ale lze předpokládat, že by to bylo podobné jako z GUI. Pokud by se jednalo o vyjádření tak je chráněno. Momentálně Google vs Oracle, o kterém by měl soud rozhodnout v 2021. Google pro Android využil stejné API jako je v javě. V prvním řešení bylo rozhodnuto že API není chráněno. Poté odvolací soud rozhodl že API je chráněno, že byla splněna podmínka originality. Momentálně je případ u nejvysšího soudu USA.

### Jaké jsou základní rozdíly mezi autorskoprávní a patentovou ochranou? Lze chránit v ČR software jako takový? Jaké jsou podmínky patentovatelnosti vynálezu realizovaného počítačem (computer implemented invention)?

Autorskoprávní ochrana programů, je neschopna chránit funkcionalitu daného programu, neboli dokáže chránit pouze objektivní vyjádření v kódu popřípadě jeho vizuální stránku, ale funkcionalita samostatná není chráněna. K přiměřenému chránění samostatné funkcionality je použita patentová ochrana. Patentově nelze chránit počítačové programy ale tzv. vynálezy uskutečňované počítačem.  
Podmínky patentovatelnosti:
  + Vynález neboli ne program, ale vynález realizovaný počítačem
  + Novost - vynález se považuje za nový, není-li součástí stavu techniky
  + Vynálezecká činnost
  + Průmyslová využitelnost - může-li být vynález vyráběn nebo využíván ve všech odvětvých průmyslu
  
Obecně v ČR SW je chráněn pouze autorským zákonem pokud nespadá pod vynálezy uskutečňované počítačem ty lze chránit patenty.  
Vynálezy uskutečňované počítačem jsou udělovány i v ČR. Do této dle zákona, nelze patentovat "plány, pravidla a způsob vykonávaní duševní činnosti, hraní her nebo vykonávání obchodní činnosti, jakož i programy počítačů".
Do vynálezu realizovaného počítačem lze zahrnout počítačový program myšlený jako produkt. Podmínka je technický charakter příslušného vynálezu. Je dán jestliže je počítačový program schopný vyvolat dodatečný technický účinek, když běží na PC nebo je na něm nahrán. Nesmí se jednat o běžnou interakci mezi SW a HW.  
Na konec hlavní podmínkou, že nelze patentovat SW jako takový ale musí splňovat určité podmínky, jejich společným jmenovatelem je přítomnost dalšího technického prvku. 

### Jak lze chránit v ČR databáze? Jak Soudní dvůr Evropské unie vykládá pojem "podstatný vklad do pořízení, ověření nebo předvedení obsahu databáze" ve vztahu k přiznání ochrany zvláštním právem pořizovatele databáze?

Databázi lze definovat jako "vnitřně organizované soubory informací, údajů, dat, tedy soubory poznatků o jakýchkoliv skutečnostech".\
Databáze podle §88 - soubor nezávislých děl, údajů, nebo jiných prvků systematicky nebo metodicky uspořádaných a individuálně přístupných elektronickými nebo jinými prostředky, bez ohledu na formu jejich vyjádření.\
V ČR lze databáze chránit dvěmi způsoby a to pomocí autorského zákona a ochranu právem sui generis - zvláštní právo zřizovatele.\
Z pohledu autorského zákona prvně databáze ovlivnila Bernská úmluva, a poté TRIPS (specifikuje že chrání způsobem výběru či uspořádáním originální soubory libovolných materiálů a dat) na kterou navázala WCT, která řeší vše až na problematiku dočasné technické rozmnoženiny. Autorským zákonem je chráněna struktůra databáze a ne její obsah.\
Autorem databáze může být pouze FO nebo skupina takových osob, ale také pokud to umožňuje právní řád tak PO.\
Ochrana zvláštním právem pořizovatele databáze. Pořizovatelem databáze je osoba, která na svou odpovědnost databázi pořídí nebo osoba, pro kterou z jejího podnětu učiní jiná osoba. Pořizovatel databáze má právo na vytěžování nebo zužitkovaní celého obsahu databáze nebo její kvalitativně nebo kvantitativní části a udělit oprávnění k tomuto i jiné osobě. Vytěžováním se rozumí trvalé přenesení jejího obsahu na jiný nosič. Na elektro databáze se nevztahuje vyjímka pro osobní použití. Co se týká vytěžení jen části databáze záleží jestli se jedná o podstatnou nebo nepodstatnou část. Jelikož nepodstatnou část lze vytěžit a zužitkovat jak dle směrnice tak i dle autorského zákona.

SDEU si vykládá, že i zásadní údaje, při posuzovaní zda se jedná o vytěžovaní podstatné či nepodstatné části aktuální hodnota údajů není relevantní. Rozhodné je jaké finanční prostředky či úsilí bylo vloženo do pořízení, ověření nebo převeden obsahu této části a nikoliv jaká je cenová hodnota těchto dat v době jejich vytěžení či zužitkování.
Také vyjádřil že co nepředstavuje podstatnou část tak představuje podstatnou. Platí to do chvíle než je databáze vytěžována systematicky.

### Může být počítačový program autorem počítačového programu? Jak se aktuálně právo staví k výtvorům umělé inteligence?

Momentálně dle autorského zákona může být autorem pouze FO takže pokud SW vytvoří SW tak daný SW není autorem nového SW. Pokud je při vývoji SW vysoká účast člověka tak se to bere jako výsledek lidské činnosti a AI je použito jako pomocník při vývoji. Takže při tomto je SW chráněn autorským právem. Při nízké účasti člověka záleží na případ od případu není to jednoznačné. Porovnávají se tam prvky objektivní vnímatelnosti, tvůrčí svobody, možnosti vyjádření apod. Obecně AI jejich výtvorů není definována. Rozlišujeme dva druhy AI - silná, slabá. Slabá AI - funguje bez black-boxu neboli dokáži predikovat výstup a vím jak to funguje na pozadí. Silná AI - funguje na základě black-boxu takže nevím jak funguje na pozadí. U slabé je vlastníkem licence autor AI, zatímco při silné AI se žádný případ neřešil ani není stanovené nějaké právo takže se momentálně nedá jednoznačně říci.

SW paradox máme vývojáře, který vytvoří AI1 a tuto AI1 licencujeme uživateli A. AI1 vytvoří AI2 a tu bude využívat uživatel 2 a v té chvíli vzniká otázka, kdo mi to má licencovat. Jestli vývojáři, uživatel A nebo AI1. Neví se přímo na koho se obrátit a jestli nevyžadovat i licenci k AI1. Z tohoto plyne jakási nejistota jestli byla licence uzavřena platně nebo ne. Autorské právo je postaveno na objektivní pravidlo, kdo něco vytvořil tvůrčí činností tak ten je autor a může mi to licencovat. Jelikož si nejsem jistý od koho licencovat a jestli se vůbec jedná o tvůrčí výsledek tak může paralizovat jakoukoliv licenční smlouvu a její užívaní.

AI jako objekt práva nemá právní osobnost a způsobilost, momentálně chybí přesvědčivý argument. 
Shrnutí: nejvíce relavantními jsou nároky tvůrců AI a uživatelů - něco jako spoluautorství. AI může být "tvůrčí", ale ne autor.


### Co je to licenční smlouva? Vyjmenujte podstatné a pravidelné náležitosti a popište účel uzavření licenční smlouvy ve vztahu k distribuci software.

Licenční smlouva je smlouva na jejíž základě poskytovatel, poskytuje oprávnění k užítí všech nebo jednotlivých způsobů užití. Nabyvatel se zavazuje, není-li sjednáno jinak, poskytnout odměnu. 
Licenční smlouva nemusí být v písemné formě. Lze ji uzavřít například ústně. Musí být uzavřena písemně pouze v případech kdy je poskytována jako výhradní. Výhradní licence autor nesmí poskytnou licenci třetí osobě a je obvykle povinen nepoužívat SW, ke kterému licenci udělil. V případě nevýhradní licence může autor používat SW způsobem, k obsahu licence a poskytnout licence dalším osobám. 
Elektronické uzavíraní:
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
    + Předmět
    - Není nutno popisovat funkcionalitu
  + Právo a způsob užití
  + Rozsah licence
  + Odměna za poskytnutí licence
  + Přiměřená dodatečná odměna
  + Délka trvání licence
+ Ostatní
  + Právo podlicencovaní, či přeprodání
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
 
Je to smlouva na jejímž základě vzniká závazek, jehož předmětem je zhotovení, údržba, oprava nebo úprava věci nebo činnosti. Většinou se sepisuje pokud je činnost financovaná zákazníkem a produkt v našem případě SW je vytvářen dle požadavků zákazníka. Často se pojí se SW na zakázku.\
Klíčovým ujednáním je specifikace předmětu plnění neboli SW. Oproti specifikaci standardního SW musí být míra specifikace o hodně rozsáhlejší a detailnější. Toto musí proběhnout, aby se předešlo sporům. Proto by specifikace neměla pokrývat pouze funkcionalitu ale také parametry, které nejsou přímo spojené s funkcionalitou ale mohou ji zásadně ovlivnit. Například HW nároky.\
Účelem uzavření licence by měla být nejen schopnost ho používat ale i různě s ním manipulovat. Například nemožnost přeprodávat nebo poskytovat SW třetí straně. Zde se aplikuje občanský zákoník, kde má zákazník licenci možnost používat licenci pouze za účelem sjednaného ve smlouvě. Proto se často sjednává širší oprávnění zákazníka/široká licence. Takže účel uzavření licenční smlouvy je za účelem využití daného SW, kde je specifikováno co vše s tím SW lze dělat. Například přeprodej třetím stranám, neomezené množství vlastních licencí na neomezenou dobu, nebo bránit dodavateli aby program sám užíval nebo prodával licenci jiným osobám, popřípadě právo měnit a upravovat dodaný SW. Dále lze sjednat přístup ke zdrojovým kódům + ošetřit její kvalitu (komentáře, dokumentace, atd.).

### Co je to SLA? Vyjmenujte náležitosti a popište účel uzavření SLA.

SLA - service level agreement je tzv. inominátní smlouva, která upravuje úroveň poskytovaní určité služby. Předmětem můžou být služby jako podpora, údržba a podobné spojené s dodávkou SW, služby v oblasti cloud computingu nebo služby v oblasti telekomunikací. Často není uzavíraná samostatně, ale je spíše doplňující smlouva.
Typické prvky:
+ Vymezení samostatné služby, tedy její definice
  + Podpora SW
  + Odstraňovaní vad
  + PC program poskytovaný jako služba
+ Parametry služby a způsob vyhodnocení - důležité preciznost jejich vymezení.
  + Z pohledu parametrů je důležité přesně vymezit, kdy se využijí (vyjímka z dostupnosti pro plánované odstávce).
    + Dostupnost
    + Reakční doba
    + Doba do odstranění závad
  + Z pohledu vyhodnocení je důležité jak bude provedeno
    + Období
      - Rok
      - Měsíc
      - Týden
      - Apod.
    + Jaký mechanismus
      - Jak bude měřena dostupnost služby
+ Kreditace - klíčový prvek, forma sankce za nedodržení úrovně služby
  + Podoba
    + Sleva z ceny
    + Smluvní pokuta - může překročit smluvní částku za službu narozdíl od slevy
    + Případně délku budoucího období poskytnutí služby zdarma tzv. free service days

### Jaký je rozdíl mezi zárukou a odpovědností za vady a jak se tyto typicky uplatňují u software?

Záruka - je dobrovolné prohlášení prodávajícího ohledně jakosti jím prodávaného zboží. Při poskytnutí se prodávající zavazuje, že věc bude funkční pro obvyklé použití nebo si zachová její vlastnosti. Stačí pokud je uvedeno na obalu, v reklamě, letáku. Záruku lze poskytnout i jen na část věci.

Odpovědnost - Dopadá na prodávajícího ze zákona. Její trvání je po dobu dvou let. Kupující uplatňuje právo z vady. Jeli na obalu, návodu, reklamě uvedena doba, po kterou lze věc použít, používá se ustanovení o záruce za jakost. Víše zmíněné neplatí v případě pokud se prodává daná věc už z určitou vadou a její cena je snížena, na opotřebení běžným způsobem, u použité věci odpovídající míře používaní nebo opotřebení, kterou věc měla při převzetí nebo nevyplívá-li to z povahy věci.

U SW se zodpovídá za vady,  tyto vady dělíme na faktické a právní. Faktické vady jsou nevhodné či nedostatečné funkcionality SW může souviset jak z bugy tak nevhodnou implementací, nekompatibilitě nebo například taky bezpečnostní chyby, nedostatečná bezpečnost SW. Právní vady spočívají zatížením SW nárokem jiné osoby v rozporu se smlouvou, na základě byl SW pořízen. 

Obecně se na SW vztahuje režim odpovědnosti za vady. Z toho vyplívá, že by dodávaný SW měl být bez chyb. Do chyb se počítá odchýlení od sjednaných vlastností a nevhodnost k výslovně stanovenému účelu. Na bezúplatný SW se odpovědnost za vady nevztahuje (Opensource). 

Obecně se lze domáhat buď opravit chyby pokud je to možné nebo přiměřené slevy z ceny. Pokud není možné vadu odstranit lze odstoupit od smlouvy nebo požadovat snížení ceny. 

### Co je podstatou softwarových veřejných licencí a jak tyto fungují po právní stránce? Kdy zvolíte jakou veřejnou softwarovou licenci a proč?

Veřejná licence je specifickým způsobem sjednaná licenční smlouva. SW licencovaný pod veřejnou licencí je vetšinou poskytován bez úplaty. Tímto způsobem se lze zbavit odpovědnosti za chyby v programu, které nezpůsobují právní vady. Obsahuje podmínku uvedení autora. 

Podstatou veřejné licence je zveřejnění díla s licenčními podmínkami, odkazem na ně. Kde nabyvatel licence není v přímém kontaktu s poskytovatelem. A využívá se hlavně v situaci kdy licenci chceme směřovat na neurčitý počet osob.
"Veřejné licence jsou veřejné návrhy k uzavření licenčních smluv, jejichž obsah je standardizován a vymezen odkazem na veřejně známe a dostupné licenční podmínky a určen neurčitému počtu osob."

Nejčastěji se veřejných licencí využívá v OSS. Typy licencí jsou silně copyleftové, slabě copyleftové a necopyleftové.\
Silně copyleftové nesou omezení při zpracovaní a šíření SW. Požadují aby původní nebo nový program, který obsahuje původní byl šířen pod původními licenčními podmínkami a současně garantují tvůrci přístup ke zdrojovému kódu. Zástupci jsou GNU GPL v2 a v3\
Slabě copyleftové vyžadují šíření odvozených programů pod stejnými licenčními podmínkami a zpřístupnění jejich zdrojových kódů. Umožňují vytváření programů, které jsou propojené a šířené společně s původním programem aniž by měnily či používaly jeho zdrojový kód a tyto programy šířit pod libovolnou licencí. Nejčastěji to jsou standardní knihovny. Nemusí se vydat zdrojové kódy vlastního kódu ale pouze musí uvést a zpřístupnit původní část programu pod původní licencí. Zástupci MPL (Mozila Public License) v 1.1 a  LGPL (Lesser General Public License) v2.1.\
Necopyleftové licence neobsahují žádnou nebo velmi omezenou copyleftovou doložku. Ukládají pouze minimální omezení k dalšímu šíření. Proto lze použít i při vývoji SW s neveřejným zdrojovým kódem aniž by bylo porušeno původních podmínek. Zástupci Apache 2.0, BSD a MIT.\
Lze měnit licence směrem od nejslabší po nejsilnější ale ne naopak. Další často používanou licencí je Creativ Commons.

### Definujte správce osobních údajů a popište jeho základní povinnosti dle GDPR. Jaký rozdíl mezi správcem a zpracovatelem osobních údajů?

Správce stanovuje účel zpracovaní osobních údajů a po většinu chce sbírat osobní údaje neboli sbírá je za předem definovaným účelem. Lze mít více správců na jedny data aka každý odpovídá sám za sebe.\
Zpracovatel je osoba/firma, která je najata správcem osobních údajů. Zpracovatel nemusí vždy existovat nebo může jich být více. Například je možné, že se osobní údaje nezpracovávají nebo si je správce zpracovává sám. Pokud zpracovatel začne rozhodovat o účelu dat sám tak se stává správcem.\
Mezi těmito entitami musí při zpracovaní být vždy sepsána písemná smlouva.\
Příklad máme firmu A která prodává zboží a bere si osobní údaje jako věk. Tato firma A se stává správcem. Firma A si řekne že chce zpracovat v jakém věku zákazníci nejčastěji nakupují určité položky. Firma to zadá nějaké firmě B nebo osobě, aby jí to zpracovala. Firma B se tím pádem stává zpracovatelem těchto osobních údajů.\

Základní povinnosti správce osobních údajů vyplívají z GDPR jsou:
+ Odpovědnost
  + Za dodržovaní zásad zpracovaní
  + Za dodržovaní povinností upravených nařízením
  + Za zabezpečení údajů
+ Povinnosti
  + Aplikace standardní ochrany osobních údajů
  + Jmenovat pověřence pro ochranu osobních údajů
  + Posuzovat vliv na ochranu osobních údajů
  + Ohlásit případy porušení zabezpečení osobních údajů jak úřadu tak postiženým osobám
  + Vést záznamy

K zpracovaní osobních údajů je nutno uvést souhlas, kde by mělo být uvedeno co je zhromažďováno a za jakým účelem. Při potřebě můžu osoba o které jsou shromážďovány osobní údaje požádat o vymazaní z databáze nebo jen přístup k nim. Jsou i vyjímky, kdy lze zpracovávat osobní údaje musí k nim ale existovat zákonný důvod.\
Příklad vyjímek:
+ Plnění smlouvy
+ Plnění právní povinnosti - uložení fakturu
+ Při výkonu veřejné moci
+ Ochrana životně důležitých zájmů subjektu údajů nebo jiné FO - lékař ukládá informace o léčbě
+ Plnění úkolu prováděného ve veřejném zájmu
+ Nezbytné pro účely oprávněných zájmů příslušného správce - například půjčení peněz někomu 

### Jakými prostředky a čeho se může domáhat autor software při zásahu do jeho autorských práv?

Ochrana majetkových hodnot je primárně pomocí soukromněprávního vymáhaní. Mělo by tím být dosaženo vrácení předchozí stavu jako kdyby se nikdy nic nestalo. 
Vymáhat lze pomocí:
+ Soukromněprávního vymáhaní - napravení předešlý stav a obsahuje (inclusive - použito v přednášce) i to že by zde docházelo ke kompenzacím, náhradě škod, vydání bezdůvodného obohacení a jiné
+ Veřejněprávního vymáhaní
  + Správněprávní - zde chceme člověka potrestat 
  + Trestněprávní - zde chceme potrestat a domáhat se náhrady škody - často předáno do občanskoprávního řízení
  + Ústavněprávní
  
Obecně veřejněprávní chce potrestat osoby dle nějakých ustanovení na kterých jsme se dohodly (zákony).

Soukromněprávní je dle AZ nebo průmyslová práva (patenty). Žaloba se podává na krajský soud dle bydliště žalovaného. Před zahájením sporu by se měli zjistit informace a podat předžalobní výzvu. Poté podáváme žalobu. Žaloba by neměla mít nejasný rozsah. Mělo by tam být udáno čeho chci dosáhnout v tzv. petitu. Lze se domoci předběžných opatření, které slouží aby nevznikalo další porušovaní práv v průběhu řízení. Vymáhání dle AZ je to ohrožovací delikt takže k zásahu ještě nemuselo dojít. Máme určité nároky jako:
+ Určení autorství - kdo je kdo
+ Zákaz ohrožení - opakovaní
+ Informace - způsob, rozsah, původ atd
+ Reparace - odčiněný škody
+ Satisfakce - příjem náhrady

Specifickým nárokem je uveřejněný omluvy. V rámci kompenzace se řeší újma ta je majetková a nemajetková. Nemajetková do ní spadá zásah do nemorálních osobnostních práv, v oblasti je to řešeno satisfakcemi možno řešit i finančně. Majetková škoda se dělí na scházející a ušlí zisk - řeší se to podle občanského ne autorského zákona.

Správněprávní rovina - řeší se pomocí Úřadu obce s rozšířenou působností - přestupky. Přestupek vs trestný čin - mírnější trestu a můžou trestat větší okruh jednaní může tam být nedbalost. Trestný čin spáchán pouze úmyslně. Ochrana spotřebitele - neřeší se kompenzace vetšinou se jenom trestá. Padělek - ochranné známky, nedovolená napodobenina - autorské právo a průmyslové vzory. SW vypálen na černo spadá do nedovolené napodobeniny.

Trestněprávní rovina - mělo by to být poslední řešení ne přeskakovat před nižšíma. Řešit důležité věci. U autorského práva není potřeba minimální škoda a řeší ho §270. 


__________________________________________________________________________________________________________________________________________

Odpovědi a otázky jsou použity pro studíjní účely\
Zdroje:
+ Právo informačních technologií ISBN 978-80-7598-045-8
+ BP [Limity autorskoprávní ochrany počítačových programů](https://is.muni.cz/th/p7o93/DP_final.pdf)
+ DP [Vybrané aspekty právní ochrany databází](https://is.muni.cz/th/xj3lq/Vybrane_aspekty_pravni_ochrany_databazi.pdf)
+ dále zápisky z přednášek BPC-SPR
