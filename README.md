## Rövid ismertető:

A webalkalmazás egyéni és közösségi (család, osztály, munkacsoport, műszak, stb.) büdzsé könnyű és gyors vezetését teszi lehetővé. A felhasználók lehetnek vendégek (nem regisztrált felhasználók), illetve regisztrált felhasználók.

## Funkcionális követelmények

### Vendég (vagy nem bejelentkezett, regisztrált) felhasználó
  Vendég (vagy nem bejelentkezett, regisztrált) felhasználóként a következő adatok/funkciók érhetőek el:
  
  - Főoldal
  - Impresszum
  - FAQ/GYIK
  - Bejelentkezés
  - Regisztráció
    
### Regisztrált felhasználó
  Regisztrált és bejelentkezett felhasználóként a következő adatok/funkciók érhetőek el (a vendég felhasználóén túl):
  
  - Profil szerkesztése
  - Közösség műveletei, közösség létrehozása, elhagyása, közösséghez csatlakozás
  - Egyéni és közösségi pénzműveletek: múltbeli és jövőbeni bevétel és kiadás megadása, jelenlegi egyenleg
  - A bevétel és a kiadások kategorizálhatóak (rendszeres és rendszertelen, illetőleg a rövid leírás szerint is: hitelkiadás, étel, albérlet, stb.
  - Egyéni kiadások tervezése: dátumra megadott, kívánt pénzösszeg esetén napi/heti/havi bontású megtakarítandó összeget mutat.
  - Közösségi kiadások tervezése (ha a felhasználó a közösség adminisztrátora): Adott dátumra, vagy utólag megadott közös kiadás elosztása a közösség látszámának. Ha meg van adva fizetési határidő, a határidő lejárta előtt az adott nem fizetett közösségi tag értesítést kap. A határidő lejárta után mindenki értesítést kap a nem fizető tagokról.
  
## Nem funkcionális követelmények
  - Vendég (nem bejelentkezett) felhasználó semmilyen regisztrált adathoz nem férhet hozzá.
  - Regisztrált felhasználó elől a rá nem tartozó (más közösségek, egyének büdzséi) adatok teljes elrejtése (felhasználóra, közösségre nem lehet keresni, kizárólag a saját vagy a közösségének adataira)
  - Telefonos optimailizáció
  - Többszöri rossz jelszó után a felhasználó email címére értesítés küldése a lehetséges betörési kísérletről
