# KSH Metter — AION 2

Darmowa nakładka do **AION 2 Global (Steam)**. Sprawdzaj swój DPS, obrażenia poszczególnych umiejętności i wyniki drużyny bez wychodzenia z gry.

Polski interfejs · angielskie nazwy umiejętności · Windows 11 x64

## Pobierz

**[Przejdź do pobierania →](https://github.com/Kashello/KSH-Metter-aion2/releases)**

Wybierz wydanie i pobierz plik kończący się na **Windows-x64-Setup.exe**. Nie potrzebujesz pobierać kodu źródłowego ani instalować narzędzi programistycznych.

## Wymagania

- Windows 11, wersja 64-bitowa.
- AION 2 Global (Steam), uruchomiony w trybie okienkowym bez ramek.
- [Npcap](https://npcap.com/#download) — składnik potrzebny do odczytu danych walki.
- Microsoft WebView2 — jeśli go brakuje, instalator KSH Metter pobierze go podczas instalacji.
- Internet do pobrania brakujących składników i aktualizacji katalogu umiejętności.

## Instalacja i pierwsza walka

1. Pobierz instalator z sekcji [Releases](https://github.com/Kashello/KSH-Metter-aion2/releases) i uruchom go.
2. Zainstaluj Npcap z [oficjalnej strony](https://npcap.com/#download). Jest instalowany osobno.
3. Uruchom **KSH Metter** ze skrótu. Ekran przygotowania pokaże, czy wszystko jest gotowe.
4. Uruchom grę w trybie okienkowym bez ramek i rozpocznij walkę.

Nick, klasa i umiejętności są rozpoznawane automatycznie — niczego nie przypisujesz ręcznie. Jeśli uruchomisz meter już podczas gry, użyj kilku różnych umiejętności, aby mógł rozpoznać Twoją postać z danych walki.

Panel DPS pojawia się po rozpoznaniu obrażeń i ukrywa się po zakończeniu walki.

## Co zobaczysz w nakładce?

- **DPS i łączne obrażenia**.
- **Paski umiejętności** z nazwami, ikonami, obrażeniami i udziałem w wyniku.
- **Ranking członków party**, których program rozpoznał w danych drużyny.
- **Ping**.
- **Obsługiwane efekty kontroli postaci**, np. ogłuszenie, z pozostałym czasem trwania.

## Ustaw nakładki po swojemu

Naciśnij **Alt+E** podczas gry, a następnie przeciągnij wybrany panel za jego górną belkę. Każdy panel ma osobne położenie, zapisywane automatycznie.

Ponowne **Alt+E** lub przycisk **Gotowe** kończy ustawianie. Jeżeli skrót jest zajęty, program pokaże skrót zastępczy.

## Ustawienia, analiza i historia

Program działa pod **ikoną kota w zasobniku Windows**, obok zegara. Jeśli jej nie widać, sprawdź ukryte ikony pod strzałką.

Kliknij ikonę prawym przyciskiem, aby otworzyć ustawienia, analizę, sprawdzenie gotowości lub zakończyć program.

Historia walk zapisuje się tylko wtedy, gdy wybierzesz **Zapisz walkę**. Niezapisana walka może zostać zastąpiona następną i nie pozostaje po zamknięciu programu. Ustawienia i zapisane walki są przechowywane lokalnie na Twoim komputerze.

## OBS i Meld Studio

1. W menu ikony kota włącz **Źródło do streamu (OBS / Meld)**.
2. Wybierz **Kopiuj link do OBS / Meld**.
3. W programie do streamowania dodaj źródło **Przeglądarka / Browser** i wklej link.
4. Umieść je nad obrazem gry i ustaw rozmiar odpowiadający rozdzielczości gry.

Źródło pokazuje nakładki bez nagrywania całego pulpitu. Wystarczy ustawić je raz; zawartość i widoczność aktualizują się automatycznie.

## Aktualizacje

Nową wersję programu pobierzesz z [Releases](https://github.com/Kashello/KSH-Metter-aion2/releases). Zamknij KSH Metter z menu ikony kota, a następnie uruchom nowy instalator. **Obecna wersja nie aktualizuje programu automatycznie.**

Nazwy i ikony umiejętności są odświeżane automatycznie w tle. Jeśli katalog jeszcze nie zna nowego skilla, brak nazwy lub obrazka nie zatrzymuje liczenia obsługiwanych obrażeń.

## Gdy coś nie działa

| Problem | Co zrobić |
| --- | --- |
| Program informuje o braku Npcap | Użyj przycisku pobierania w aplikacji lub przejdź na [npcap.com](https://npcap.com/#download) i zainstaluj składnik. |
| Nie widać DPS | Otwórz **Sprawdź gotowość** z menu ikony kota. Sprawdź połączenie i rozpoznanie postaci, a następnie użyj kilku różnych umiejętności podczas walki. |
| Nie można przesuwać paneli | Włącz tryb ustawiania przez **Alt+E** i przeciągaj za górną belkę. |
| Nakładki nie ma na streamie | Dodaj źródło przeglądarkowe według instrukcji powyżej. Samo przechwytywanie gry może nie obejmować nakładki. |
| Brakuje ikonki skilla | Nie trzeba jej przypisywać ręcznie. Program korzysta z dostępnego katalogu i odświeża go w tle. |

W razie problemu zgłoś go w [Issues](https://github.com/Kashello/KSH-Metter-aion2/issues) lub na [Discordzie](https://discord.gg/YgpYQg45Mp). Podaj wersję programu, klasę postaci i krótki opis sytuacji; możesz dołączyć zrzut komunikatu.

## Wersja testowa

Odczyt walki jest eksperymentalny i wynik może być niepełny. **Healing i Support nie są obecnie obsługiwane.** Aktualizacje gry mogą wymagać nowej wersji metera.

Instalator nie jest podpisany cyfrowo. KSH Metter jest niezależnym projektem, niepowiązanym z NCSOFT; nie gwarantuje zgodności z regulaminem gry. Grafiki gry należą do ich właścicieli, a Npcap ma osobną licencję. Informacje licencyjne są dołączone do instalatora.

---

[kashello.pl](https://kashello.pl/) · [Twitch](https://www.twitch.tv/kashelloo) · [Discord](https://discord.gg/YgpYQg45Mp)
