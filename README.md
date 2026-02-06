# Podstawy psychopatologii i klasyfikacji zaburzeń psychicznych

## 📖 Opis projektu

Projekt zawiera interaktywny materiał edukacyjny dotyczący podstaw psychopatologii i klasyfikacji zaburzeń psychicznych. Jest to pełnowartościowy kurs multimedialny obejmujący prezentacje, materiały audio oraz graficzne ilustrujące różne typy zaburzeń psychicznych.

## 🎯 Cel projektu

Celem projektu jest dostarczenie kompleksowego, interaktywnego materiału szkoleniowego dla studentów, pracowników służby zdrowia oraz osób zainteresowanych tematyką psychopatologii. Kurs prezentuje w przystępny sposób klasyfikację i charakterystykę głównych zaburzeń psychicznych.

## 📂 Struktura projektu

```
psychopatologia/
├── index.html                                              # Główny plik prezentacji interaktywnej
├── goodbye.html                                            # Strona końcowa kursu
├── podstawy-psychopatologii-i-klasyfikacji-zaburzen-psychicznych-BfuUtTtw.pdf  # Materiał PDF
├── assets/                                                 # Zasoby multimedialne
│   ├── *.mp3                                              # Pliki audio z narracją
│   ├── Zaburzenia-afektywne-dwubiegunowe.jpg             # Grafika: Zaburzenia afektywne dwubiegunowe
│   ├── Zaburzenia-depresyjne.jpg                         # Grafika: Zaburzenia depresyjne
│   ├── Zaburzenia-lękowe.jpg                             # Grafika: Zaburzenia lękowe
│   ├── Zaburzenia-obsesyjno-kompulsyjne-(OCD).jpg        # Grafika: OCD
│   ├── Zaburzenia-osobowości.jpg                         # Grafika: Zaburzenia osobowości
│   ├── Zaburzenia-związane-z-substancjami-i-uzależnienia.jpg  # Grafika: Uzależnienia
│   ├── Zespół-stresu-pourazowego.jpg                     # Grafika: PTSD
│   └── small.png                                          # Grafika pomocnicza
└── lib/                                                    # Biblioteki JavaScript i CSS
    ├── player-0.0.11.min.js                               # Odtwarzacz multimedialny
    ├── lzwcompress.js                                     # Kompresja danych
    ├── icomoon.css                                        # Ikony
    ├── fonts/                                             # Czcionki
    ├── rise/                                              # Moduł prezentacji
    ├── sandbox/                                           # Style
    ├── learn_dist/                                        # Moduł dystrybucji
    └── mondrian/                                          # Dodatkowe moduły
```

## 📚 Zawartość edukacyjna

Kurs obejmuje następujące tematy związane z zaburzeniami psychicznymi:

### Główne kategorie zaburzeń:
- **Zaburzenia depresyjne** - objawy, klasyfikacja i metody rozpoznawania
- **Zaburzenia afektywne dwubiegunowe** - charakterystyka epizodów maniakalnych i depresyjnych
- **Zaburzenia lękowe** - typy lęków patologicznych i ich objawy
- **Zaburzenia obsesyjno-kompulsyjne (OCD)** - natręctwa i kompulsje
- **Zaburzenia osobowości** - klasyfikacja według DSM i ICD
- **Zespół stresu pourazowego (PTSD)** - przyczyny, objawy i leczenie
- **Zaburzenia związane z substancjami i uzależnienia** - mechanizmy uzależnień

### Materiały multimedialne:
- 📊 Graficzne przedstawienia poszczególnych zaburzeń
- 🔊 Narracja audio wyjaśniająca kluczowe pojęcia
- 📄 Dokument PDF z pełną treścią kursu

## 🚀 Instalacja i uruchomienie

### Wymagania wstępne

- Przeglądarka internetowa (zalecane: Chrome, Firefox, Edge)
- Serwer HTTP (opcjonalnie, do lokalnego uruchomienia)

### Metoda 1: Bezpośrednie otwarcie pliku

Dla prostego podglądu można otworzyć plik `index.html` bezpośrednio w przeglądarce:

```bash
# Otwórz plik w domyślnej przeglądarce
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

⚠️ **Uwaga:** Niektóre funkcje mogą nie działać poprawnie bez serwera HTTP ze względu na politykę CORS.

### Metoda 2: Lokalny serwer HTTP (zalecane)

#### Użycie Python:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Użycie Node.js (http-server):

```bash
# Instalacja http-server globalnie
npm install -g http-server

# Uruchomienie serwera
http-server -p 8000
```

#### Użycie PHP:

```bash
php -S localhost:8000
```

Po uruchomieniu serwera, otwórz przeglądarkę i przejdź do:
```
http://localhost:8000
```

### Metoda 3: Uruchomienie w środowisku LMS

Projekt został zaprojektowany do działania w środowisku Learning Management System (LMS). Dla pełnej funkcjonalności zalecane jest:

1. Zaimportowanie całego katalogu do systemu LMS (np. Moodle, Canvas)
2. Skonfigurowanie kursu zgodnie z dokumentacją używanego systemu LMS
3. Udostępnienie kursu uczniom przez platformę

## 🔧 Szczegóły techniczne

### Technologie użyte w projekcie:

- **HTML5** - struktura prezentacji
- **JavaScript** - logika interaktywna
- **CSS3** - stylizacja
- **SCORM-ready** - kompatybilność z systemami LMS

### Główne komponenty:

1. **Player multimedialny** (`player-0.0.11.min.js`) - obsługa audio i video
2. **Kompresja LZW** (`lzwcompress.js`) - efektywne przechowywanie danych
3. **Moduł Rise** - system prezentacji slajdów
4. **Ikony Icomoon** - spójna ikonografia

### Kompatybilność z przeglądarkami:

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ⚠️ Internet Explorer - nie wspierany

## 📱 Dostępność i responsywność

Projekt został zoptymalizowany pod kątem:
- Responsywnego wyświetlania na różnych urządzeniach
- Dostępności dla osób z niepełnosprawnościami
- Wsparcia dla czytników ekranu
- Nawigacji klawiaturowej

## 🎓 Zastosowania

Materiał może być wykorzystany przez:
- Studentów psychologii i psychiatrii
- Wykładowców prowadzących kursy z zakresu psychopatologii
- Pracowników służby zdrowia w ramach szkoleń
- Osoby przygotowujące się do egzaminów specjalizacyjnych
- Wszystkich zainteresowanych tematyką zdrowia psychicznego

## 📄 Materiały PDF

Projekt zawiera kompletny dokument PDF:
- `podstawy-psychopatologii-i-klasyfikacji-zaburzen-psychicznych-BfuUtTtw.pdf`

Dokument można wykorzystać jako:
- Materiał uzupełniający do kursu online
- Źródło do druku i wykorzystania offline
- Podstawę do samodzielnej nauki

## 🔐 Bezpieczeństwo i prywatność

Projekt:
- Nie zbiera danych osobowych użytkowników
- Działa lokalnie w przeglądarce
- Nie wymaga połączenia z internetem (po pobraniu)
- Nie zawiera trackerów analitycznych

## 🤝 Wkład w rozwój projektu

Jeśli chcesz przyczynić się do rozwoju tego projektu:

1. Zgłaszaj błędy i sugestie przez system Issues
2. Proponuj ulepszenia w zakresie treści edukacyjnych
3. Dziel się informacjami o skuteczności materiału w procesie nauczania

## 📧 Kontakt

W przypadku pytań lub problemów z projektem, skorzystaj z systemu Issues w repozytorium GitHub.

## 📝 Wersje

- **v2.0** (aktualna) - Wersja z pełną interaktywnością i materiałami multimedialnymi

## ⚖️ Licencja

Treści edukacyjne dotyczące psychopatologii służą celom informacyjnym i edukacyjnym. Nie zastępują one profesjonalnej porady medycznej, diagnozy ani leczenia.

---

**Autor:** MatPomGit  
**Data utworzenia:** 2024  
**Ostatnia aktualizacja:** 2026

---

## 🌟 Słowa kluczowe

psychopatologia, zaburzenia psychiczne, klasyfikacja zaburzeń, DSM, ICD, zaburzenia depresyjne, zaburzenia lękowe, OCD, PTSD, zaburzenia osobowości, edukacja medyczna, kurs interaktywny, materiały edukacyjne
