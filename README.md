# Weekend w regionie – dane

Publiczny pakiet danych aplikacji „Weekend w regionie” (AppStorm), serwowany przez GitHub Pages.

- `v1/version.json` – wersja pakietu, sumy SHA-256 plików i minimalna wersja aplikacji
- `v1/places.json`, `v1/products.json` – miejsca i produkty regionalne
- `v1/areas.json` – granice parków i rezerwatów (GDOŚ) oraz przebiegi ścieżek dydaktycznych (Bank Danych o Lasach)
- `v1/img/320/<sha256>.jpg`, `v1/img/800/<sha256>.jpg` – miniatury zdjęć z Wikimedia Commons (nazwa = SHA-256 pliku 800)
- `privacy-policy.html` – polityka prywatności aplikacji (kopia; docelowy adres to https://appstorm.eu/weekend-w-regionie/polityka-prywatnosci.html)

## Źródła i licencje

Pakiet jest zestawieniem otwartych danych publicznych: dane.gov.pl (wykaz muzeów MKiDN, CC0; lista produktów tradycyjnych MRiRW, CC BY 4.0), Generalna Dyrekcja Ochrony Środowiska (Centralny Rejestr Form Ochrony Przyrody i granice z Geoserwisu, CC0), Państwowy Instytut Geologiczny (jaskinie i Centralny Rejestr Geostanowisk Polski, CC BY 4.0), Narodowy Instytut Dziedzictwa (Pomniki historii, CC BY 4.0), Lasy Państwowe – Bank Danych o Lasach (punkty widokowe, ośrodki edukacji, ścieżki dydaktyczne, obszary „Zanocuj w lesie” i parkingi leśne; CC BY 4.0), Europejska Agencja Środowiska (kąpieliska, dane Państwowej Inspekcji Sanitarnej; CC BY 4.0), Główny Urząd Geodezji i Kartografii – Państwowy Rejestr Nazw Geograficznych (wodospady, kopce i grodziska; CC BY 4.0) oraz Wikidata (zamki i ruiny zamków, pałace, wieże widokowe, zoo, ogrody botaniczne; CC0). Każdy rekord wskazuje swoje źródła, a pełną listę zbiorów z licencjami podaje aplikacja w zakładce „Więcej”.

Dwa zestawienia są własne (AppStorm, CC BY 4.0 – prosimy o podanie źródła: „AppStorm, Weekend w regionie”):

- **Podziemne trasy turystyczne** (źródło `appstorm-podziemia`) – kopalnie, podziemia wojenne i miejskie udostępnione do zwiedzania, sprawdzone na stronach operatorów; współrzędne wejść z Wikidata albo od operatorów, opisy własne. W pakiecie: blok `underground` miejsc w `v1/places.json`.
- **Szlak Zabytków Techniki Województwa Śląskiego** (źródło `appstorm-zabytki-techniki`) – obiekty szlaku jako atrakcje rodzaju `industrialHeritage`; przynależność do szlaku i nazwy według zabytkitechniki.pl (bez opisów ze strony szlaku), elementy i współrzędne z Wikidata.

Współrzędne części miejsc oraz punkty dojazdu (parkingi, początki szlaków, punkty informacji) pochodzą z OpenStreetMap: © autorzy OpenStreetMap ([openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)). Te dane są dostępne na licencji [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

Zdjęcia pochodzą z Wikimedia Commons, dopasowane przez Wikidata. Każde ma własnego autora i licencję (CC0, domena publiczna, CC BY lub CC BY-SA), zapisane w polu `photo` miejsca w `v1/places.json` razem z linkiem do strony pliku. Zdjęcia na licencji CC BY-SA udostępniamy na tej samej licencji.

Pakiet jest generowany automatycznie; zmian nie należy wprowadzać ręcznie.

Kontakt: kontakt@appstorm.eu
