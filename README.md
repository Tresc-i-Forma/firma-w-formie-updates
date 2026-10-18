# Firma w Formie

Księgowość jednoosobowej działalności gospodarczej od [Treść i Forma](https://tresciforma.pl): podatkowa księga
przychodów i rozchodów według wzoru z 2026 r., import faktur z KSeF, dane do JPK_PKPIR. Program działa lokalnie,
na Windows: baza danych, dokumenty i kopie zapasowe zostają na Twoim komputerze.

To repozytorium zawiera tylko gotowe wydania programu (bez kodu źródłowego).

## Pobierz

[**Najnowsza wersja**](https://github.com/Tresc-i-Forma/firma-w-formie-updates/releases/latest): plik
`Firma-w-Formie-Setup-<wersja>.exe`. Kolejne wersje program instaluje sam (O programie → Sprawdź aktualizacje).

## Wersja testowa

- **Bez licencji, bezpłatnie:** księga przychodów i rozchodów, import faktur z KSeF (pliki XML albo token KSeF),
  dane do JPK_PKPIR w CSV, kopie zapasowe i archiwum roku. Pozostałe funkcje (rozliczenia PIT i ZUS, zamykanie
  miesięcy, JPK_PKPIR w XML, PIT-36L, IP Box) wymagają licencji.
- Program jest w fazie testów. **Przez pierwsze miesiące prowadź księgę równolegle** w dotychczasowym narzędziu
  i porównuj wyniki.
- Program nie jest doradztwem podatkowym: za poprawność ewidencji i rozliczeń odpowiada podatnik.
- Obecnie obsługuje podatek liniowy; skala podatkowa, ryczałt i podatnicy zwolnieni z VAT są w przygotowaniu.

## Instalacja

- Windows 10 albo 11 (64-bit). Instalacja na koncie bieżącego użytkownika, bez uprawnień administratora;
  PostgreSQL jest w instalatorze.
- Instalator nie jest jeszcze podpisany certyfikatem, więc Windows (SmartScreen) pokaże ostrzeżenie „nieznany
  wydawca”: kliknij „Więcej informacji”, potem „Uruchom mimo to”.
- Program łączy się z internetem tylko po to, żeby pobrać faktury z KSeF, sprawdzić kontrahenta po NIP w wykazie
  podatników VAT (Biała lista MF) i sprawdzić aktualizacje w tym repozytorium.

## Uwagi i błędy

Zgłaszaj przez [tresciforma.pl](https://tresciforma.pl). **Nie wysyłaj danych firmy, faktur ani zrzutów ekranu
z kwotami i danymi kontrahentów**; wystarczy opis problemu i numer wersji (O programie).
