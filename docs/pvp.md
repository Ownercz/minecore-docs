# Frakční PVP server
## Základní příkazy:

- **/spawn** - port na spawn
- **/napoveda** - nápověda k frakcím
- **/obchod** - port do shopu
- **/duel [nick]** - vyzveš hráče na souboj
- **/ma j** - připojení do MobArény
- **/newbie disable** - **vypnutí ochrany nováčka**
- - **zapne se pvp a budeš moct brát itemy ze země**

## Frakce:

- **/f help** – vypíše všechny příkazy factions
- **/f create [název frakce]** – vytvoří frakci
- **/f join [název frakce]** – připojíš se do frakce (pokud jsi pozvaný nebo je veřejná)
- **/f open** – otevře frakci pro všechny, připojí se bez pozvání
- **/f leave** – opustíš frakci
- **/f home** – port na home lokaci frakce
- **/f player [nick]** – zobrazí informace o hráči

## Pro Leadery/Officery frakcí:

- **/f claim [velikost]** – zabere území
- **/f faction [název]** – zobrazí informace o frakci
- **/f map** – zobrazí mapu
- **/f unclaim** – odemkne chunk
- **/f invite [nick]** – dáš povolení k přístupu do tvé frakce, nějakému hráči
- **/f sethome** – vytvoří home lokaci frakce
- **/f kick [nick]** – kickne hráče z tvé frakce (hráč se může znova připojit)
- **/f officer [nick]** – učiníš hráče Officerem frakce
- **/f leader [nick]** – hráč se stane Leaderem (Leader může být jen jeden)
- **/f ally [název frakce]** – alience s frakcí
- **/f neutral [název frakce]** – neutralita
- **/f enemy [název frakce]** – válka
- **/f truce [název frakce]** – příměří

## Permise:

- **/f perm [frakce] [permise] [zařazení] no/yes**
- - Zařazení - (leader, officer, member)

### Jednotlivé permise

- **BUILD**: Stavění (kdo má povoleno) (leader, officer, member, ally)
- **DOOR**: Použití dvěří (kdo má povoleno) (leader, officer, member, recruit, ally)
- **BUTTON**: Požití tlačítek (kdo má povoleno) (leader, officer, member, recruit, ally)
- **LEVER**: Použití páček (leader, officer, member, recruit, ally)
- **CONTAINER**: Použití Beden (leader, officer, member)
- **INVITE**: pozvání hráčů (leader, officer)
- **KICK**: kiknutí členů (leader, officer)
- **SETHOME**: nastaví home (leader, officer)
- **TERRITORY**: claim nebo unclaim (leader, officer)
- **DISBAND**: rozpustí frakci (leader)
