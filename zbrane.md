# 🔫 Přehled zbraní a herní ekonomiky

Správná správa peněz (ekonomika) je v Counter-Strike 2 klíčem k vítězství. Každá zbraň má svou specifickou cenu, odměnu za zabití (Kill Reward) a chování při střelbě.

[Zpět na hlavní stránku](README.md)

---

## Rozdělení výzbroje podle kategorií

### 1. Pistole (První kola a Eco)
* **Glock-18 (T):** Výchozí pistole teroristů, velký zásobník (20 nábojů) a možnost střelby dávkou.
* **USP-S (CT):** Výchozí pistole s tlumičem, extrémně přesná na první ránu, ale pouze 12 nábojů v zásobníku.
* **Desert Eagle:** Nejsilnější pistole ve hře, dokáže zabít na jednu ránu do hlavy i přes helmu.

### 2. Samopaly a brokovnice (Anti-Eco)
Ideální volba pro druhé kolo po vyhraném pistolkovém kole, protože dávají vysokou peněžní odměnu za zabití.

| Zbraň | Cena | Odměna za zabití (Kill Reward) | Ideální použití |
| :--- | :---: | :---: | :--- |
| **MP9** | $1250 | $600 | Rychlá obrana krátkých vzdáleností (CT) |
| **MAC-10** | $1050 | $600 | Rychlý útok (Rush) na bomb site (T) |
| **XM1014** | $2000 | $900 | Držení úzkých chodeb a blízkých pozic |

---

## Ukázka herních dat ve formátu JSON

Pro komunitní statistiky a webové aplikace se data o zbraních ukládají například takto:

```json
{
  "weapon": "AK-47",
  "team": "Terrorists",
  "price": 2700,
  "magazine_size": 30,
  "one_tap_headshot": true
}
