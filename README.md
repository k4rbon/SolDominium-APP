<p align="center">
  <img src="screenshots/01-logowanie.png" width="220" alt="Ekran logowania solApp">
</p>

<h1 align="center">solApp</h1>

<p align="center">
  Prywatna aplikacja mobilna dla firmy <a href="https://soldominium.pl"><b>SOL DOMINIUM</b></a>, dla ekip montujących instalacje fotowoltaiczne i magazyny energii.<br>
  Android i iOS · projekt i wykonanie: <b>krngg.dev</b>
</p>

---

## O projekcie

solApp to wewnętrzne narzędzie firmy [SOL DOMINIUM](https://soldominium.pl), która zajmuje się instalacjami fotowoltaicznymi i magazynami energii. Zastępuje papierowe protokoły, zdjęcia rozrzucone po telefonach i arkusze z magazynem. Monter ma w jednej aplikacji montaże, dokumentację zdjęciową, stany magazynowe, listy materiałów i kalkulator wyceny. Biuro widzi wszystko na bieżąco.

Aplikacja jest prywatna i działa tylko na kontach zakładanych przez administratora. Kod źródłowy nie jest publiczny.

> Zrzuty ekranu pokazują wersję demonstracyjną ze zmyślonymi danymi.

## Montaże

<p>
  <img src="screenshots/02-montaze.png" width="220" alt="Lista montaży">
  <img src="screenshots/03-montaz.png" width="220" alt="Szczegóły montażu">
  <img src="screenshots/04-montaz-zdjecia.png" width="220" alt="Zdjęcia z montażu">
</p>

- Archiwum realizacji z wyszukiwaniem po kliencie i adresie
- Statusy: zaplanowany, w trakcie, zakończony, oraz filtr „Moje”
- Przypisywanie monterów do montażu
- Nawigacja do adresu jednym kliknięciem
- Zdjęcia i dokumenty w kategoriach: falownik, magazyn energii, konstrukcja, protokoły
- Lokalizacja GPS i czas wykonania przy każdym zdjęciu
- **Praca bez zasięgu:** zdjęcia czekają w kolejce i wysyłają się same, gdy wróci internet
- Pobranie całego montażu jednym plikiem ZIP

## Magazyn i materiałówki

<p>
  <img src="screenshots/06-magazyn.png" width="220" alt="Magazyn">
  <img src="screenshots/07-materialowki.png" width="220" alt="Materiałówki">
</p>

- Stany magazynowe z kategoriami, cenami i skanowaniem kodów QR
- Materiałówki, czyli listy materiałów na konkretną instalację, które od razu zdejmują towar ze stanu
- Przypinanie materiałówki do montażu
- Eksport każdej listy osobno albo wszystkich naraz, do **PDF** i **Excela**

## Wycena

<p>
  <img src="screenshots/08-wycena.png" width="220" alt="Kalkulator wyceny">
</p>

- Kalkulator instalacji PV podzielony na sekcje: panele, falownik, magazyn energii, zasilanie awaryjne, konstrukcja, rozdzielnie i przewody
- Własny katalog produktów i cen, edytowany z poziomu aplikacji
- Suma netto, VAT i brutto
- Gotowa wycena w PDF dla klienta

## Administracja

<p>
  <img src="screenshots/09-menu-konta.png" width="220" alt="Menu konta">
  <img src="screenshots/10-panel-admina.png" width="220" alt="Panel administratora">
</p>

- Konta pracowników z uprawnieniami nadawanymi pojedynczo
- Historia operacji: kto, co i kiedy dodał, zmienił albo pobrał
- Codzienna automatyczna kopia zapasowa bazy i plików

## Technologie

| Część | Stos |
| --- | --- |
| Aplikacja | Expo, React Native, TypeScript |
| Serwer | Node.js, Express, JWT |
| Baza danych | MongoDB |
| Dystrybucja | EAS Build, aktualizacje OTA przez EAS Update |

---

<p align="center">© krngg.dev. Wszelkie prawa zastrzeżone.</p>
