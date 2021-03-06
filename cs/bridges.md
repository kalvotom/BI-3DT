# Mosty

Pro tisk přemostění je důležité mít správně nastavený profil ve sliceru. Správný most by měl vypadat jako na obrázku níže. Není žádoucí, aby byl most prověšený, nebo aby měl přetrhaná vlákna.

![Most](../images/bridges/bridge.jpg)

(Obrázek z [videa](https://www.youtube.com/watch?v=wK2APNwEoSk) © BCN3D Technologies.)

## Správně nastavený most

Pro kalibraci mostu se upravuje hodnota v aplikaci Slic3r v sekcích:

 -  Print Settings→Speed→Bridges 
 -  Print Settings→Advanced→Flow.

Pro dnešní cvičení si stáhnětě nový [config](../configs/bridges/slic3r_config_bundle.ini).


## Úkol

Zuří XLIII. světová válka v roce 2297. Již v roce 2015 bylo možné 3D tisknout
mosty, proto vás nyní velitelství pověřilo vytisknout most na 3D tiskárně.
V naší výcvikové budově máme zmenšenou kopii 3D tiskárny, která bude poté na
bitevním poli tisknout skutečné mosty. 

Každý most má svoje ohodnocení. Čím hodnotnější most se vám podaří vytisknout,
tím lépe se ubráníte zlým kryptofašistům. Ohodnocení mostu ale není stejně
rovnoměrné co se týče jeho výšky/šířky. Most široký 20 a dlouhý 30 není stejně
ohodnocený jako most široký 30 a dlouhý 20. Hodnotnější je delší most.
Jinak řečeno, pro zisk bodů se vyplatí dělat mosty spíše delší než širší.

Jako generátor mostu použijte soubor [bridge.scad](../stls/bridges/bridge.scad)
a mosty generujte v OpenSCADu (úprava implementace modulu za účelem získání
více bodů je považována za podvod). Jednotky jsou v milimetrech a jedná se
pouze o velikost mostu bez velikosti pilířů.
Pilíře se nesnažte podříznout, negativně by to ovlivnilo tiskové vlastnosti.

Vycházejte z konfigurace pro Slic3r
[slic3r_config_bundle.ini](../configs/bridges/slic3r_config_bundle.ini)
(pozor, jiný bundle než minule!).

Ohodnocení mostu je vždy vidět na jeho horní straně.

### Hodnocení

 1. bod za vytištění opravdu ošklivého propadlého mostu
 2. bod za vytištění ošklivého mostu
 3. bod za vytištění hezkého mostu

Výše uvedené body se nesčítají. Kdo po sobě neuklidí, nemá na body nárok.
Bodované mosty musí být aspoň 30 mm dlouhé.

### Bonus

Armádní studentské dvojici, které se podaří vytisknout nejhodnotnější most,
budou započítány 3 bonusové body. 2. nejlepší 2 body 3. nejlepší 1 bod.

Tato soutěž probíhá napříč všemi paralelkami. Průběžné výsledky **nejsou
sdělovány soutěžícím**. Do soutěže vstupují pouze mosty, za které jste dostali
body výše. Není tedy možné např. odevzdat hezký krátký most za 3 body a zároveň
soutěžit s opravdu ošklivým propadlým mostem.
