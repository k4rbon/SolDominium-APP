# SOL DOMINIUM

Wewnętrzna aplikacja dla monterów instalacji SOL DOMINIUM, na Androida i iOS.
Zbiera w jednym miejscu montaże, dokumentację, magazyn i wyceny. Nie jest przeznaczona dla klientów.

## Funkcje

- **Montaże:** statusy (zaplanowany, w trakcie, zakończony), przypisywanie monterów, nawigacja do adresu
- **Dokumentacja:** zdjęcia i dokumenty w kategoriach, z lokalizacją GPS przy zdjęciach
- **Praca offline:** kolejka wysyłki plików, która rusza po odzyskaniu zasięgu
- **Magazyn:** stany przedmiotów i skanowanie kodów QR
- **Materiałówki:** listy materiałów przypinane do montaży
- **Wyceny:** generowanie PDF
- **Eksport:** cały montaż jako ZIP, materiałówki jako CSV pod Excela
- **Administracja:** konta, uprawnienia i dziennik działań
- **Kopie zapasowe:** codzienny backup bazy i plików

## Technologie

| Część | Stos |
| --- | --- |
| Aplikacja | Expo SDK 58, React Native, TypeScript |
| Serwer | Node.js, Express, JWT |
| Baza danych | MongoDB |
| Build i aktualizacje | EAS Build, EAS Update |
