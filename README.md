# 2FRESH Trello
Tento dokument shrnuje výchozí použití Trella v rámci agentury [2FRESH](http:/www.2fresh.cz/) a jejích startupů ([Costlocker](https://www.costlocker.cz) a [Atoto](https://www.atoto.cz)). Má za úkol standardizovat práci s boardy napříč veškerými tými, aby bylo maximální souhry.

1. [Základní principy](#základní-principy)
1. [Sloupce](#sloupce)

## Základní principy
Při používání Trella 2FRESH uplatňuje několik klíčových principů, které zvyšují výslednou efektivu.

1. [Jeden člověk na kartičku](#jeden-člověk-na-kartičku)
1. [Kartička nemění řešitele](#kartička-nemění-řešitele)
1. [Kartička začíná slovesem](#kartička-začíná-slovesem)
1. [Úkol trvá nejdéle den](#Úkol-trvá-nejdéle-den)
1. [Tvůrce kartičky je důkladný](#tvůrce-kartičky-je-důkladný)
1. [Nejdůležitější úkol je nahoře](#nejdůležitější-úkol-je-nahoře)
1. [Jeden úkol v jeden moment](#jeden-úkol-v-jeden-moment)
1. [Všechno je marketing](#všechno-je-marketing)

### _Jeden člověk na kartičku_
> Pokud je na kartičce více lidí, snižuje se pravděpodobnost, že se úkol vyřeší.

Cílem tohoto principu je zajistit jasnou odpovědnost za konkrétní úkol. Řešitel ví, že se má kartičky chopit a nemusí přemýšlet nad posloupností úkolů – o tu se stará projektový manažer nebo tým jako celek v rámci plánování sprintu.

Napomáhá při samotném používání Trella – jakmile řešitel stiskne klávesu `Q`, okamžitě je jasné, který úkol má dělat (buď úkol, který má ve sloupci [_In Progress_](#in-progress), nebo zcela na vršku sloupce [_Sprint_](#sprint)).

#### Co dělat, když má na úkolu dělat více lidí?
Tehdy pravděpodobně není kartička dostatečně rozpadnutá dle principu [_Kartička začíná slovesem_](#kartička-začíná-slovesem). Cílem je vytvořit atomické činnosti per řešitel (například _Nadesignovat katalog produktů_ a _Nakódovat katalog produktů_).

Pokud problém setrvává, může být ještě způsoben tím, že činnost není rozpadnutá na konkrétní kroky dle principu [_Úkol trvá nejdéle den_](#Úkol-trvá-nejdéle-den) – málokdy se stane, že jeden návrh kreslí dva grafici nebo že jeden katalog kóduji dva kodéři (jeden pravděpodobně připravuje business logiku a druhý vizuální složku).

#### Co dělat, když o stavu úkolu potřebuje vědět více lidí?
V ideálním případě kolegové úkol [_odebírají_](http://help.trello.com/article/799-subscribing-to-cards-lists-and-boards) – toho docílí tím, že otevřou kartičku a kliknout na tlačítko _Odebírat_ vpravo dole. Díky tomu budou u úkolu dostávat notifikace a u kartiček, které odebírají, se zobrazí červený zvoneček signalizující nezhlédnutou aktivitu.

Dalším důležitým prvkem jsou `@mentions` v komentářích a popisu karty, které upozoroní konkrétního kolegu.

### _Kartička nemění řešitele_
Vzhledem k principům [_Kartička začíná slovesem_](#kartička-začíná-slovesem) a [_Tvůrce kartičky je důkladný_](#tvůrce-kartičky-je-důkladný) není možné, aby kartička měnila řešitele, protože by to vyžadovalo přepsání zadání kartičky.

Cílem tohoto principu je především zachování všech činností, které vznikly, aby bylo možné se k nim případně vrátit. To má řadu důležitých vedlejších účinků:

- lze stanovit odhady pro kartičku (pokud by měnila řešitele, měnily by se odhady a nebylo by je možné zpětně dohledat)
- je možné trackovat čas na konkrétní kartičce
- z jiných kartiček je možné odkazovat na konkrétní činnost

#### Nevzniká kvůli tomu v rámci nástěnky spousta kartiček?
Ano a je to dobře. Pokud jde o to, aby řešitelé nebyli zahlceni zbytečnými kartičkami – k tomu nedochází, protože řešitelé mají stejně vyfiltrované kartičky pouze pro sebe díky klávese `Q`.

#### Co dělat, když na kartičku navazuje další činnost a chceme uchovat historii konverzace?
Vzhledem k principům [_Kartička začíná slovesem_](#kartička-začíná-slovesem) a [_Tvůrce kartičky je důkladný_](#tvůrce-kartičky-je-důkladný) vzniká nová kartička se zadáním pro konkrétního řešitele a nese odkaz na původní kartičku v případě potřeby kontextu.

Naším cílem by mělo být zajistit, aby měl řešitel jasné zadání, které by neměl dohledávat v rámci konverzace.

#### Co dělat, když potřebujeme, aby se k úkolu vyjádřil klient?
Je možné odebírat aktivitu na sloupcích – pokud vytvoříme sloupec pojmenovaný `Schválení u klienta` a domluvíme se, že ho bude klient odebírat, je situace vyřešená. To samé platí i pro sloupec `Schválení projektovým manažerem` a podobně.

### _Kartička začíná slovesem_
Jakmile kartička začíná slovesem, které charakterizuje konkrétní činnost, upřesňuje se tím zadání a volba odpovědného řešitele.

### _Úkol trvá nejdéle den_
Abychom zajistili efektivní využití času, reálnější odhady a plánování, je žádoucí větší úkoly rozpadat na konkrétní kroky. Ty je díky tomu možné přesněji odhadnout a naplánovat. Snižuje se tak riziko nepřesné alokace řešitele.

#### Přeci není možné odhadnout, jak budou některé činnosti dlouho trvat. Třeba tvorba loga může trvat 2 hodiny, ale také dva týdny. Jak postupovat tehdy?
Pokud řešitel určí odhad _2 hodiny až 2 týdny_, zeptejte se ho, které kroky konkrétně musí podniknout, aby úkol splnil. Pokud odpověď zní, že to tak prostě je, je vhodné začít hledat někoho nového.

Toto téma se často objevuje u kreativní činnosti – typicky právě loga a podobně. Je vhodné si prostudovat knihu [_Design Is a Job_](https://abookapart.com/products/design-is-a-job) a rozbít mýtus umělce, kterému musíme dát prostor pro polibek múzou. Design není synonymum pro grafiku nebo umění – skutečný designér ovládá proces, který vede k dosažení cíle a nespoléhá na štěstí.

### _Tvůrce kartičky je důkladný_
> Čím více práce si dám s kartičkou já, tím méně s ní má řešitel.

Jakmile vytváříme kartičku, je naší odpovědností a zájmem, aby byl úkol co nejlépe zadaný. Výhody z toho plynoucí jsou následující:

- přesně zadaný úkol snižuje riziko chybné implementace, protože řešitel ví, co má dělat
- dobře zadaný úkol znamená méně dotazů od řešitele, takže se nám čas strávený tvorbou kartičky ve výsledku vyplatí
- definování úkolu nám pomáhá si vyjasnit myšlenky
- kvalitně zadaný úkol nefrustruje řešitele – ten se ho může chopit a začít pracovat namísto dohledávání chybějících informací

### _Nejdůležitější úkol je nahoře_
Toto pravidlo je klíčové hlavně ve sloupci [_Sprint_](#sprint), který obsahuje prioritizovaný seznam úkolů na tento týden. Díky tomu funguje velice efektivní mechanismus – po stisknutí klávesy `Q` řešitel okamžitě ví, který úkol má dělat.

### _Jeden úkol v jeden moment_
Nikdo nedokáže řešit jeden v moment více úkolů najednou, což znamená, že ve sloupci [_In Progress_](#in-progress) může být jenom jeden úkol per řešitel. Pokud řešitel pracuje na jiném úkolu, vrací původní úkol zpět na vršek sloupce [_Sprint_](#sprint).

### _Všechno je marketing_
Toto pravidlo pochází z knihy [_Restart_](https://books.google.cz/books/about/Restart.html?id=AU5RAQAAQBAJ&redir_esc=y&hl=cs) a připomíná nám, že to, jak pojmenováváme kartičky nebo jakým způsobem komentujeme, se podepisuje na tom, jak působíme na okolí. Ať už máme na mysli kolegy, klienta nebo širokou veřejnost, naše fungování v Trello má velký vliv na naše renomé a definuje úroveň naši profesionality.

#### Nezdržuje nás, když se snažíme mluvit spisovně a vše popisujeme dlouhými větami namísto prostého vytvoření kartičky?
Na první pohled ano. Jakmile se úkolu chopí řešitel, naše důkladnost se nám vrátí ([_Tvůrce kartičky je důkladný_](#tvůrce-kartičky-je-důkladný)). Kromě toho promyšlené názvy kartiček, popisy a komentáře snižují pravděpodobnost nedorozumění.

## Sloupce

### `Inbox` (seznam podnětů)
První sloupec, _Inbox_, slouží k neřízenému sběru podnětů. Jsou to nápady, které se ve výsledku ani nemusí stát reálnými úkoly, ale bylo dobré je zachytit. Příkladem mohou být nápady pro použití technologií, které ale ještě nemáte nazkoumané, takže nemůžete vytvořit skutečný úkol. Věci v _Inboxu_ zkrátka musí ještě trošku dozrát.

V ideálním případě sloupec _Inbox_ nepotřebujete, protože máte pro sběr podnětů určený jiný nástroj. Například _Costlocker_ využívá různých kanálů, které ovšem všechny ve výsledku putují do aplikace [_ProductBoard_](https://www.productboard.com), kterém si určitě popovídáme v některém z dalších dílů. Výhodou pak je, že máte veškeré podklady na jednom místě nemusíte je hledat v e-mailech, _Slacku_ a podobně.

### `Backlog` (nadcházející úkoly)
Sloupec _Backlog_ již obsahuje konkrétní úkoly nebo větší celky, které bude potřeba dále rozpadnout, ale počítá se s tím, že se budou dělat. V ideálním případě je _Backlog_ seřazený dle priority od nejdůležitějšího po méně důležité úkoly.

_Inbox_ a _Backlog_ jsou jediné dva sloupce, které se nemusí striktně držet pravidla, že každý úkol musí začínat slovesem. S velkou pravděpodobností se totiž hrubší úkoly budou v průběhu času doupřesňovat. Například totiž můžete vědět, že je potřeba v aplikaci vytvořit _Katalog produktů_, ale neznáte konkrétní úkoly, které z toho plynou.

### `Sprint` (aktuální úkoly)
Ve _Sprintu_ shromažďujeme seznam detailních úkolů na krátké časové období (ideálně týden), ve kterém má každá kartička pouze jednoho řešitele a celý sloupec je seřazený dle priority. Ve výsledku to znamená, že pokud uživatel používá klávesu `Q`, ví v každý moment, kterým kolem má následovat – tím, který je ve _Sprintu_ zcela nahoře.

Pokud nechcete pracovat ve sprintech, ale říkáte si, že bohatě stačí pouze dobře prioritizovaný _Backlog_ a je to určitě možnost. Z psychologických důvodů ale není příliš vhodná – vzniká nekonečná fronta úkolů a tým neví, jestli plní úkoly dle plánu, nebo jestli jsou ve skluzu. Dělení na jednotlivé týdny pomáhá přehlednosti a navíc umožňuje generovat _Burndown Charty_, na nichž letmým pohledem jasně vidíte stav.

### `In Progress` (rozpracované úkoly)
Sloupec _In Progress_ říká, na kterém z úkolu ze _Sprintu_ kolegové aktuálně pracují. Tento sloupec má ovšem jedno důležité pravidlo – každý zde může mít jenom jednu kartičku, protože dokáže v jednu chvíli pracovat na jediném ukolu.

Úkol má z _In Progress_ tři možné cesty. Buď ho musíte na chvilku odložit kvůli jinému úkolu a v tu chvíli putuje zpět do _Sprintu_. Jindy se může stát, že na úkolu nemůžete pracovat, potože ho něco blokuje – tehdy patří do sloupečku _Blocked_. V ideálním případě cestuje kartička do sloupce _Acceptance_.

### `Blocked` (blokované nebo čekající úkoly)
Pokud na úkolu není možné pracovat, patří do sloupce _Blocked_, přičemž v komentáři vysvětlíte, čím je úkol blokován a ideálně odkážete na příslušný úkol a použijete `@mention` pro řešitele.

### `Acceptance` (úkoly čekající na schválení)
Jakmile je úkol hotový, putuje do sloupce `Acceptance`, ve které probíhá kontrola úkolu a jeho schválení. V některých případech můžete mít i více sloupečků _Acceptance_ – například interní, u klienta a u CEO. Díky tomu máte jasno, kdo má aktuálně úkol na starost.

### `Done` (schválené úkoly)
Pokud vše dopadne dobře, přesouvá schvalující kartičku do sloupce _Done_, který říká, že je práce dokončená.

Nabízí se otázka – archivovat úkoly, jakmile jsou dokončené? Je vhodné tak učinit například po dokončení sprintu, a to z toho důvodu, že úkoly můžete stejně kdykoli dohledat v archivu v logických celcích.

### `Production` (nasazené úkoly)
Sloupec _Production_ říká, že je úkol dokončený a je nasazený na produkci, tedy dostupný veřejnosti. Tento sloupec dává smysl hlavně při tvorbě produktů nebo dlouhodobější přípravě webů, které mají i testovací fázi.
