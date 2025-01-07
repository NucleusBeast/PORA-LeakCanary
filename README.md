# 📚 Knjižnica LeakCanary

**LeakCanary** je knjižnica ki pomaga odkrivati in analizirati uhajanje pomnilnika (memory leaks) v aplikacijah. Razvila jo je ekipa pri Square, in je izjemno uporabna za razvijalce Android aplikacij, ki želijo izboljšati zmogljivost in stabilnost svojih aplikacij.

## 🤔 Zakaj izbrati LeakCanary?

- **Preprosta uporaba**: LeakCanary je enostavna za uporabo, saj zahteva le nekaj vrstic kode.
- **Hitro odkrivanje uhajanja pomnilnika**: LeakCanary samodejno zazna uhajanje pomnilnika in vam pošlje obvestilo.
- **Podrobne informacije**: LeakCanary vam ponuja podrobne informacije o uhajanju pomnilnika, kar vam pomaga hitro najti in odpraviti težavo.
- **Odprtokodna**: LeakCanary je odprtokodna knjižnica, kar pomeni, da jo lahko prilagodite svojim potrebam.

## 📜 Licenca - Apache License 2.0

1. **Svobodna uporaba in distribucija** 📂
    - Koda, licencirana pod Apache 2.0, se lahko uporablja za komercialne in nekomercialne namene brez omejitev.

2. **Spreminjanje in razširjanje** 🔄
    - Omogoča spreminjanje izvorne kode in distribucijo spremenjene ali nespremenjene različice, dokler je vključena kopija licence.

3. **Priznanje avtorstva** ✍️
    - V vseh izvodih ali večjih delih izvorne kode mora biti vključena opomba o avtorstvu, izvirni licenčni pogoji in obvestilo o morebitnih spremembah.

4. **Izključitev odgovornosti** ⚠️
    - Licenca ne zagotavlja nobenih garancij za delovanje programske opreme; razvijalci niso odgovorni za morebitne težave pri uporabi.

## 📊 Statistika in aktivnost

- **Zvezdice na GitHub-u:** ⭐ LeakCanary ima več kot **29.000 zvezdic** [![GitHub stars](https://img.shields.io/github/stars/square/leakcanary?style=flat-square)](Stevilo) kar nam pove da je knjižnica zelo popularna.
- **Aktivni issue-ji:** 🐛 Trenutno je odprtih **97 aktivnih issue-jev** [![GitHub issues](https://img.shields.io/github/issues/square/leakcanary?style=flat-square)]()
- **Število forkov:** 🍴 Knjižnica ima dobrih 4000 forkov: [![GitHub forks](https://img.shields.io/github/forks/square/leakcanary?style=flat-square)]()
- **Zadnji commit:** 🕒 Zadnji commit je bil narejen 29.08.2024: [![GitHub last commit](https://img.shields.io/github/last-commit/square/leakcanary?style=flat-square)]()

## ✅ Prednosti in ❌ slabosti

### ✅ Prednosti
- **Preprosta uporaba**: LeakCanary je enostaven za uporabo in ne zahteva veliko kode.
- **Hitro odkrivanje uhajanja pomnilnika**: LeakCanary samodejno zazna uhajanje pomnilnika in vam pošlje obvestilo.
- **Podrobne informacije**: LeakCanary vam ponuja podrobne informacije o uhajanju pomnilnika, kar vam pomaga hitro najti in odpraviti težavo.
- **Odprtokodna**: LeakCanary je odprtokodna knjižnica, kar pomeni, da jo lahko prilagodite svojim potrebam.

### ❌ Slabosti
- **Zahteva dodatno konfiguracijo**: LeakCanary zahteva dodatno konfiguracijo v vašem projektu, kar lahko nekoliko poveča čas razvoja.
- **Zahteva dodatno pomnilnik**: LeakCanary uporablja dodaten pomnilnik za zaznavanje uhajanja pomnilnika, kar lahko vpliva na zmogljivost vaše aplikacije.
- **Nekatere težave z združljivostjo**: LeakCanary morda ne bo deloval z vsemi različicami Androida ali vseh knjižnic, kar lahko povzroči težave pri integraciji.
- **Nekatere težave z natančnostjo**: LeakCanary morda ne bo vedno natančno zaznal uhajanja pomnilnika, kar lahko povzroči lažne pozitivne ali negativne rezultate.

## 🛠️ Primer uporabe

### Namestitev LeakCanary

1. Knjižnica se doda v datoteko `build.gradle` applikacije:

```gradle
dependencies {
  debugImplementation 'com.squareup.leakcanary:leakcanary-android:2.7'
}
```
