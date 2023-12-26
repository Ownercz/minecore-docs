## Vanilla server
### Ochrana pozemku

Jako první musíš napsat `/t create název_pozemku` například `/t create ostrava`.  
Nyní máš název pozemku a potřebuješ k němu nastavit samotnou oblast. 

Oblast nastavíš příkazem `/t claim`, to ti claimne oblast 16x16 (1 chunk) kde zrovna stojíš.  
Počet chunků, které můžeš mít u svého pozemku, je maximálně 16. Tedy můžeš zastavět oblast 256x256.

Odebrat kus pozemku můžeš pomocí `/t unclaim`.
Odebrat kompletně pozemek můžeš pomocí `/t delete`.

### Přidání kamaráda
Nejdřív jdi na svůj pozemek. Kamaráda přidáš příkazem `/t add NICK` , například `/t add Davo` přidá kamaráda s nickem Davo do tvého pozemku. 

Kamarád pak přijme tvé pozvání `/accept`

Odebrání můžeš udělat poté příkazem: `/t kick NICK`

### Přejmenování pozemku
Stůj ve svém pozemku, který chceš přejmenovat, následně napiš `/t set name Brno`. To nastaví jméno tvého pozemku na Brno.

### Kde všude mám pozemek?
Mapu pozemku si můžeš zobrazit pomocí příkazu `/towny map`.
Můžeš si taky zapnout/vypnout zobrazení okrajů chunku, díky kterým uvidíš, kde přesně ti končí pozemek příkazem `/res toggle constantplotborder`.

Neustálé vypisování mapy do chatu můžeš zapnout/vypnout `/res toggle map`.

Zelené = tvůj pozemek, šedé = ničí pozemek, červené = cizí/pvp.

### Seznam pozemků
/t list - klikneš a můžeš se portnout

### uvítací zpráva
/t set board
/t set board none - smazat
