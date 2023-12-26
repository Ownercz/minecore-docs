# Přehled hráčských příkazů
# Survival economy server

## Warpy
Příkazem ```/warp``` zobrazíš všechny warpy na serveru.  
Těžit a branch minovat bez omezení můžeš na ```/mine``` warpu. Stavět bez omezení můžeš na ```/priroda```.  
Prosím o dodržování těchto pravidel, abychom měli stavební mapu stále krásnou a ne jak krtčí noru.  

## Stavba
Stavět můžeš kdekoliv na mapě, kde není již stávající region.  
Region chápej jako pozemek, který už někdo vlastní.  
Do mapy, kde je možné stavět, se dostaneš přes ```/priroda```.

## Ochrana pozemku
Začneme ochranou pozemku - na ```/warp priroda``` sis našel/a krásné místo.   
Zda tam není jiný region, stačí napsat ```/rg info``` - to ti vždy vypíše informace o regionu a tak zjistíš, zda tam opravdu je či není.


Fun fact: ```__global__``` region není region pro hráče, ale takový region, který je všude (ber to jako default, ty si děláš vlastní nad ním).

## Pojďme si ochránit pozemek
Máš pozemek, nikdo tam na něm není? Super! Tak vytas označovátko příkazem ```//wand```.

Nyní potřebuješ označit dva body. Ber, že máš pozemek 50x50, takže musíš začít máchnutím na první blok, který je v levém "spodním" rohu a druhý, úhlopříčný v pravém "horním" rohu.

Zde je v nákresu označen levý roh A a pravý jako B. 
```
+------------------B
|                  |
|                  |
|                  |
|                  |
|                  |
A------------------+
```

Máš označeno? Skvělé. Nyní potřebuješ napsat ```//expand vert```, aby si měl ochranu pozemku 50x50 a hlavně od bedrocku až po nebe.

Hráč může mít 4 regiony, které jsou 50x50 velké (a s ```//expand vert``` jsou chráněné na komplet výšku). Komplet výška je důležitá proto, aby se ti nikdo nemohl dostat nad pozemek a polít tě lávou.

**Máme označeno?** Skvělé! Tak pojďme vytvořit samotný region. Stačí ti příkaz  ```/rg claim NÁZEV_REGIONU```, tedy například  ```/rg claim ostrava```, pokud chceš, aby se tvůj region jmenoval Ostrava.

## Máš kamarády a chceš s nimi stavět
Získal si kamarády, skvělá práce! Tak je pojďme pozvat do tvého pozemku.

1. Zjisti si název pozemku (musíš v něm stát) ```/rg info```
2. Region se jmenuje např. ostrava a hráč se jmenuje johndeer
3. Hráče přidáš příkazem ```/rg addmember ostrava johndeer``` a odebereš příkazem ```/rg delmember ostrava johndeer```
3. Pokud hráči hodně věříš (což nedoporučujeme), tak ho můžeš přidat i jako vlastníka tvého pozemku příkazem ```/rg addowner ostrava johndeer``` a odebereš příkazem ```/rg delowner ostrava johndeer```

### Počet regionů a rozměry
- Maximální rozměr jednoho regionu je 50x50 bloků.
- Maximální počet regionů jsou 4.
- Větší regiony nebo větší počet ti rádi udělají členové AT (ale musíš mít buď dobrý důvod - např. skvělý projekt nebo jsi už všechno zastavěl).
- VIP mají vyšší počet regionů než 4.


# Vanilla server
## Ochrana pozemku

Jako první musíš napsat `/t create název_pozemku` například `/t create ostrava`.  
Nyní máš název pozemku a potřebuješ k němu nastavit samotnou oblast. 

Oblast nastavíš příkazem `/t claim`, to ti claimne oblast 16x16 (1 chunk) kde zrovna stojíš.  
Počet chunků, které můžeš mít u svého pozemku, je maximálně 16. Tedy můžeš zastavět oblast 256x256.

Odebrat kus pozemku můžeš pomocí `/t unclaim`.
Odebrat kompletně pozemek můžeš pomocí `/t delete`.

#### Přidání kamaráda
Nejdřív jdi na svůj pozemek. Kamaráda přidáš příkazem `/t add NICK` , například `/t add Davo` přidá kamaráda s nickem Davo do tvého pozemku. 

Kamarád pak přijme tvé pozvání `/accept`

Odebrání můžeš udělat poté příkazem: `/t kick NICK`

#### Přejmenování pozemku
Stůj ve svém pozemku, který chceš přejmenovat, následně napiš `/t set name Brno`. To nastaví jméno tvého pozemku na Brno.

##### Kde všude mám pozemek?
Mapu pozemku si můžeš zobrazit pomocí příkazu `/towny map`.
Můžeš si taky zapnout/vypnout zobrazení okrajů chunku, díky kterým uvidíš, kde přesně ti končí pozemek příkazem `/res toggle constantplotborder`.

Neustálé vypisování mapy do chatu můžeš zapnout/vypnout `/res toggle map`.

Zelené = tvůj pozemek, šedé = ničí pozemek, červené = cizí/pvp.

#### Seznam pozemků
/t list - klikneš a můžeš se portnout

#### uvítací zpráva
/t set board
/t set board none - smazat
