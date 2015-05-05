# Laboratoria PUM Lato 2014 / 2015

### Laboratorium 1
- Praca z komponentami (projektowanie GUI, obsługa w Activity)
  - Komponenty umieszczane w ramach Layoutu
  - RelativeLayout - pozwala umieszczać komponenty na określonych pozycjach względem siebie
  - LinearLayout - układanie komponentów w kolumnie / wierszu
  - Widoki - wpływają na zachowanie komponentów w layoucie
  - ScrollView - udostępnia pasek przewijania
- Przechodzenie między Activity
  - Intent wskazujący na klasę Activity do której jest przejście
  - Można przekazywać dane (intent.putExtra(NAZWA_ZMIENNEJ, wartość))
  - Odczyt w docelowej Activity (intent.getStringExtra(NAZWA_ZMIENNEJ))
- LoginActivity, SettingsActivity
  - Różne formy renderowania Activity
  - Nie wszystkie Activity wymagają szczegółowego opisu w postaci pliku XML
- Obsługa powiadomień Toast
  - Komunikat popup o określonym czasie trwania
  - Należy pobrać kontekst aplikacji (getApplicationContext())
  - Wywołanie statyczne (Toast.makeText(context, TEKST, CZAS_WYŚWIETLANIA).show())
- ActionBar - edycja menu, przechodzenie do ParentActivity (AndroidManifest.xml)
  - Pozycje menu w plikach XML
  - Wskazanie pliku XML w metodzie Activity onCreateOptionsMenu
  - Obsługa wybranej pozycji w metodzie Activity onOptionsItemSelected

### Laboratorium 2
- Lokalizacja aplikacji (aplikacje wielojęzyczne)
  - Tłumaczenia w folderach /res/values-[KOD_JĘZYKA]/strings.xml
- Layouty pionowe / poziome, dla różnych rozmiarów wyświetlacz
  - layout poziomy - layout-land, mogą występować elementy o tym samym ID
- Kompatybilność wsteczna
- Cykl zycia aplikacji
- Zapis danych
  - Zapis stanu (np. przy obracaniu ekranu)
  - Zapis danych do pliku w pamięci urządzenia
  - Ustawienia aplikacji - SharedPreferences
- Fragmenty
- RecycledView
