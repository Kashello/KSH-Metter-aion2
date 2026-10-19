# KSH Metter — AION 2

Darmowa, eksperymentalna nakładka do AION 2 Global (Steam) na Windows 11 x64. Polski interfejs, angielskie nazwy umiejętności.

## Pobieranie

Instalatory będą dostępne w [Releases](https://github.com/Kashello/KSH-Metter-aion2/releases). Wersja 0.1.29 jest przygotowywana jako wydanie testowe.

Repozytorium służy do udostępniania instalatorów i informacji dla użytkowników. Nie zawiera prywatnych nagrań sieciowych ani historii walk twórcy.

## Wymagania i uruchomienie

1. Pobierz i uruchom instalator Windows x64.
2. Instalator pobierze brakujący Microsoft WebView2 — potrzebny jest internet.
3. Zainstaluj osobno [Npcap z oficjalnej strony](https://npcap.com/#download). Npcap nie jest dołączony do pakietu.
4. Uruchom KSH Metter. Ekran przygotowania sprawdzi wymagania i połączenie gry.
5. Graj w AION 2 w trybie okienkowym bez ramek. Nicku, klasy i skilli nie wpisujesz ręcznie.

Przy uruchomieniu metera podczas gry rozpoznanie postaci może wymagać użycia kilku różnych umiejętności i otrzymania potwierdzeń z serwera. Przy niejednoznacznych danych program czeka zamiast przypisywać cudze obrażenia.

## Funkcje i obsługa

- Obrażenia i DPS, paski umiejętności, ikony i kolory.
- Ranking potwierdzonych członków party; odczyt pozostaje eksperymentalny.
- Ping i obsługiwane efekty kontroli postaci.
- Alt+E odblokowuje przesuwanie nakładek za górną belkę; pozycje zapisują się automatycznie.
- Ikona kota w zasobniku Windows udostępnia ustawienia, analizę i sprawdzanie gotowości.
- Historia powstaje tylko po kliknięciu „Zapisz walkę”.
- Opcjonalne źródło przeglądarkowe do OBS/Meld: włącz w trayu i skopiuj link.

## Aktualizacje

**Program nie ma jeszcze automatycznej aktualizacji EXE.** Nowe wersje będą udostępniane w Releases; należy pobrać nowy instalator i uruchomić go ponownie.

Katalog nazw i grafik skilli odświeża się automatycznie co 24 godziny i ma lokalny cache. Brak internetu lub grafiki nie blokuje liczenia obsługiwanych obrażeń. Nieznane ID nie jest zastępowane zgadywaną grafiką. Zmiany protokołu gry nadal mogą wymagać nowej wersji programu.

## Stan testów i ograniczenia

Instalację i uruchomienie potwierdził twórca na swoim komputerze. W Browserling potwierdzono wykrywanie braku Npcap i przycisk prowadzący na stronę pobierania. Nie jest to pełny test gry ani instalacji na czystym Windows 11 bez wszystkich zależności.

Parser jest częściowy. Nie potwierdzono pełnej dokładności wszystkich klas, dungeonów i walk party. Healing i Support nie mają gotowego odczytu live. Instalator 0.1.29 nie jest podpisany cyfrowo.

Program nie czyta pamięci gry, nie wstrzykuje kodu i nie obchodzi zabezpieczeń. Nie potwierdzono zgody wydawcy gry na jego używanie.

## Licencje

Kod własny jest objęty MIT; informacje licencyjne są dołączone do instalatora. Grafiki gry należą do NCSOFT lub właściwych właścicieli i nie są objęte MIT. Przed publiczną redystrybucją pakietu z tymi grafikami pozostaje ustalenie odpowiednich praw. Npcap ma osobną licencję, którą użytkownik akceptuje we własnym instalatorze.

## Kashello

[kashello.pl](https://kashello.pl/) · [Twitch](https://www.twitch.tv/kashelloo) · [Discord](https://discord.gg/YgpYQg45Mp)
