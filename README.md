# Simulacija upozorenja na temperaturu

**Inačica:** demo-v04

Projekt simulira provjeru ručno unesene temperature. Ne koristi fizički senzor, ne mjeri vlagu i ne upravlja ventilatorom.

## Pokretanje

1. Kopirajte cijelu mapu `tim-01-pametni-senzor` na svoje računalo.
2. U pregledniku otvorite `src/index.html`. Instalacija dodataka ili poslužitelja nije potrebna.
3. Unesite `30` i kliknite **Provjeri temperaturu**. Očekujte upozorenje.
4. Unesite `28`. Očekujte dopušteno stanje. Prazan unos treba prikazati pogrešku.

Valjani raspon temperature je od **-40 do 85 °C**, uključujući krajnje vrijednosti. Upozorenje se pojavljuje za vrijednosti strogo veće od **28 °C**, najkasnije pet sekundi nakon klika.

## Namjerno pogrešna inačica za tutorial 08

Otvorite `variants/pogreska-prag/index.html`. Ova inačica namjerno koristi prag od **35 °C** umjesto zahtijevanih **28 °C**. Unos vrijednosti `30` zato otkriva pogrešku.

**Ne koristite ovu inačicu kao ispravnu projektnu inačicu.**

## Dokumentacija

* [Zahtjevi](docs/ZAHTJEVI.md)
* [Testovi](docs/TESTOVI.md)
* [Kanban kartice](docs/KANBAN.md)
* [Scenarij demonstracije](docs/SCENARIJ_DEMO.md)
* [Prijedlog teme](docs/PRIJEDLOG_TEME.md)
* [Prazni predložak prijedloga](docs/PRIJEDLOG_TEME_PRAZNO.md)
* [Izvori](docs/IZVORI.md)
* [AI evidencija](docs/AI_EVIDENCIJA.md)
* [Dnevnik rada](docs/DNEVNIK_RADA.md)
* [Dnevnik odluka](docs/DNEVNIK_ODLUKA.md)
* [Zapisnici](docs/ZAPISNICI.md)
* [Suradnja](docs/SURADNJA.md)

![Kontekst aplikacije](docs/slike/sustav.png)

U ovoj vježbi veličina simulacije služi učenju alata. Složenost godišnjeg projekta dogovara se zasebno.
