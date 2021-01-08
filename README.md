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

Pokud by bylo GUI zcela převzato, mohla by být zasaženo do autorských práv ke GUI jako samostatnému autorskému dílu, nepodlehajícímu zvlašnímu režimu ochrany (viz právo prvák letní), neboli čistě GUI není chráněno až na nějaké vyjímky.

Školní dílo (autorský zýkon §60) - škola mají za obvyklých podmínek právo na uzavření licenční smlouvy o užití díla. Pokud není závažný důvod měl by autor udělit licenci nebo bude udělena soudem.

Zaměstnanecké dílo (autorský zýkon §58) - jestliže zaměstnanec vytvoří program ke splnění svých poviností vyplívajícíh z pracovněprávního nebo služebního vztahu a neexistuje-li mezi zaměstnavatelem a zaměstnancem odlišná dohoda, zaměstnavatel vykonával k takovému programu svým jménem a na svůj účet autorova majetková práva. Pokud není dohoda odlišná tak zaměstanec současně uděluju zaměstnavateli svolení k úkonům, které by zasahovali do práv osobních.
  + spojovat s jinýmy programy
  + dale je měnit 
  + uvádět je na trh
  + vše víše bez zvláštního souhlasu zaměstnance
  
Spoluautorské/kolektivní dílo (autorský zýkon §59) je dílo, na kterém se podílí více autorů a je vytvřeno z podnětu a pod vedením FO/PO a uváděno na veřejnost pod jejím jménem. Považují se často za zaměstnanecká díla.

### Jaké jsou zákonné a judikatorní podmínky pro dovolené reverzní inženýrství software?

### Jak mohou být právem chráněna rozhraní (datová, uživatelská, aplikační)? Je právem chráněna funkcionalita software?

### Jaké jsou základní rozdíly mezi autorskoprávní a patentovou ochranou? Lze chránit v ČR software jako takový? Jaké jsou podmínky patentovatelnosti vynálezu realizovaného počítačem (computer implemented invention)?

### Jak lze chránit v ČR databáze? Jak Soudní dvůr Evropské unie vykládá pojem "podstatný vklad do pořízení, ověření nebo předvedení obsahu databáze" ve vztahu k přiznání ochrany zvláštním právem pořizovatele databáze?

### Může být počítačový program autorem počítačového programu? Jak se aktuálně právo staví k výtvorům umělé inteligence?

### Co je to licenční smlouva? Vyjmenujte podstatné a pravidelné náležitosti a popište účel uzavření licenční smlouvy ve vztahu k distribuci software.

### Co je to smlouva o dílo? Vyjmenujte podstatné a pravidelné náležitosti a popište účel uzavření licenční smlouvy ve vztahu k vývoji software.

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
