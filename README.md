# Recenze filmové série Duna

## Část 1 Představení
Série Duna se převážně odehrává kolem půvabné a podivuhodné planety **Arrakis**, která je žilou té nejdůležitější surovinou zvanou **Spice** (koření). 

Zapomocí Spice se dá cestovat vesmírem a říká se, že *kdo má kontrolu nad Arrakisem, má kontrolu nad celou vesmírnou ekonomií*. Arrakis ale obývají místní obyvatelé zvaní **Fremeni**, pouštní nomádi, ~~kteří s planetou v podstatě splynuli~~ kteří jsou jedni s planetou. Fremeni ovšem nejsou jediná věc, která planetu obývá.
Pod písečnými dunami se plíží obrovské písečné žížaly, které vnímají každičký pohyb a jsou vždy připraveny zdroj zvuku pohltit.

### Klíčové hrozby na Arrakisu
* **Písečný červ (Shai-Hulud):** Obří tvor chránící koření.
* **Intriky impéria:** Politický boj o moc.
* **Nehostinné klima:** ~Voda je tu drahocenná~ Voda je tu cennější než zlato.

---

## Část 2 Vizuál a atmosféra
Planeta je sice celá pokryta pískem, ale je velmi vizuálně podivuhodná. Prostředím vyvolává pocit volnosti, ale zároveň nejistoty. Celková atmosféra Arrakisu je taková tajemná a děsivá.

### Kontrola přípravy před sledováním filmu
Zde je můj osobní checklist, co musíte stihnout, než si pustíte Dunu:
- [x] Připravit si velký popcorn a pití
- [x] Ztlumit světla v pokoji pro správnou atmosféru
- [ ] Přečíst si úvodní knihu od Franka Herberta

---

## Část 3 Zázemí projektu a užitečné odkazy
Pokud vás svět Duna zajímá hlouběji, doporučuji navštívit [oficiální stránky filmu Duna](https://www.dunemovie.com) nebo si přečíst podrobné informace na [Wikipedii o Arrakisu](https://cs.wikipedia.org/wiki/Arrakis).

### Ukázka atmosféry (Ilustrace)
Zde je ukázka vizuálního zpracování planety uložená přímo v repozitáři:
![Pustá krajina Arrakisu](images/arrakis-landscape.jpg)

### Technické pozadí aneb výpočet vzdáleností ve vesmíru
Pro představu, jak funguje navigace pomocí koření, si můžeme ukázat jednoduchý Python skript na výpočet skoků:

```python
def vypocet_skoku(parsec, koeficient_spice):
    # Koření umožňuje bezpečný průchod prostorem
    bezpecna_vzdalenost = parsec * koeficient_spice
    return f"Skok úspěšný na vzdálenost: {bezpecna_vzdalenost} světelných let"

# Testovací výpočet pro planetu Arrakis
print(vypocet_skoku(125.5, 4.2))
