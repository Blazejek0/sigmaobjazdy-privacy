# Polityka Prywatności — SigmaObjazdy

**Data ostatniej aktualizacji: 14 maja 2026**

Niniejsza Polityka Prywatności opisuje zasady przetwarzania danych osobowych użytkowników aplikacji mobilnej **SigmaObjazdy** (dalej: „Aplikacja"), służącej do śledzenia tras GPS pojazdów oraz dokumentacji fotograficznej dla kierowców firmy Sigma Pomiary.

---

## 1. Administrator Danych Osobowych

Administratorem Twoich danych osobowych jest:

**Sigma Pomiary Sp. z o.o. **
Żegańska 16 / 10, 04-713 Warszawa, Polska
NIP: 9522199666
REGON: 384368633

**Kontakt w sprawach ochrony danych:**
E-mail: sigmapomiarydev@gmail.com
Telefon: +48500715992

---

## 2. Jakie dane zbieramy

Aplikacja zbiera następujące kategorie danych osobowych:

| Dane | Cel | Wymagane? |
|---|---|---|
| **Numer telefonu** | Identyfikator kierowcy w systemie | TAK |
| **Lokalizacja precyzyjna (GPS)** | Śledzenie trasy przejazdu | TAK (do funkcji śledzenia) |
| **Zdjęcia + lokalizacja zdjęć** | Dokumentacja fotograficzna miejsc objazdu | NIE (opcjonalne) |
| **Identyfikator zlecenia (QR)** | Powiązanie kierowcy z konkretnym zleceniem | TAK |
| **Informacje techniczne** (model urządzenia, wersja Androida, identyfikator aplikacji) | Diagnostyka błędów i awarii | TAK (zbierane automatycznie przy awariach) |

**Dane NIE zbierane:**
- ❌ Imię i nazwisko
- ❌ Adres e-mail
- ❌ Adres zamieszkania
- ❌ Dane biometryczne
- ❌ Kontakty / książka adresowa
- ❌ Treści SMS / wiadomości
- ❌ Historia przeglądarki

---

## 3. Cel i podstawa prawna przetwarzania

| Cel | Podstawa prawna (RODO) |
|---|---|
| Świadczenie usług śledzenia tras dla zleceń Sigma Pomiary | Art. 6 ust. 1 lit. b RODO — wykonanie umowy |
| Identyfikacja kierowcy przypisanego do zlecenia | Art. 6 ust. 1 lit. b RODO — wykonanie umowy |
| Dokumentacja fotograficzna (opcjonalnie) | Art. 6 ust. 1 lit. b RODO — wykonanie umowy |
| Diagnostyka błędów i awarii Aplikacji | Art. 6 ust. 1 lit. f RODO — uzasadniony interes (zapewnienie stabilności usługi) |
| Wypełnianie obowiązków prawnych (np. księgowość) | Art. 6 ust. 1 lit. c RODO — obowiązek prawny |

---

## 4. Komu udostępniamy Twoje dane

Twoje dane mogą być przekazane następującym kategoriom odbiorców:

### 4.1. Podmioty świadczące usługi techniczne
- **Google Ireland Limited** (Google LLC) — usługi Firebase Realtime Database, hosting infrastruktury. Lokalizacja serwerów: Unia Europejska (Frankfurt, Niemcy). Dane przekazywane: pozycja GPS w czasie rzeczywistym podczas aktywnego śledzenia.
- **Functional Software, Inc. (Sentry)** — narzędzie do raportowania błędów Aplikacji. Lokalizacja serwerów: Niemcy (region UE). Dane przekazywane: informacje techniczne o awariach (model telefonu, wersja Androida, stos błędu), **bez** numeru telefonu i danych osobowych użytkownika.

### 4.2. Organy publiczne
W przypadku gdy obowiązek udostępnienia danych wynika z przepisów prawa (np. wezwanie sądu, organ ścigania).

### 4.3. NIE udostępniamy danych
- ❌ Firmom marketingowym
- ❌ Brokerom danych
- ❌ Sieciom reklamowym
- ❌ Podmiotom niepowiązanym z umową świadczenia usług

---

## 5. Czas przechowywania danych

| Kategoria danych | Okres przechowywania |
|---|---|
| Lokalizacja GPS (trasy) | Przez okres realizacji umowy oraz **5 lat** po jej zakończeniu (dokumentacja księgowa) |
| Zdjęcia z lokalizacją | Jak wyżej |
| Numer telefonu | Do momentu rezygnacji ze świadczenia usług + 6 miesięcy |
| Logi błędów (Sentry) | **30 dni** od wystąpienia awarii, następnie automatyczne usunięcie |
| Pozycja w czasie rzeczywistym (Firebase) | **Tylko podczas aktywnego śledzenia** — nadpisywana co kilka sekund, nie jest archiwizowana |

---

## 6. Twoje prawa

Zgodnie z RODO przysługują Ci następujące prawa:

1. **Prawo dostępu** do swoich danych osobowych (art. 15 RODO)
2. **Prawo do sprostowania** błędnych danych (art. 16 RODO)
3. **Prawo do usunięcia** danych — „prawo do bycia zapomnianym" (art. 17 RODO)
4. **Prawo do ograniczenia przetwarzania** (art. 18 RODO)
5. **Prawo do przenoszenia danych** w ustrukturyzowanym formacie (art. 20 RODO)
6. **Prawo do sprzeciwu** wobec przetwarzania (art. 21 RODO)
7. **Prawo do wniesienia skargi** do Prezesa Urzędu Ochrony Danych Osobowych (ul. Stawki 2, 00-193 Warszawa)

**Jak skorzystać z praw:** wyślij e-mail na adres podany w punkcie 1 z opisem żądania. Odpowiemy w ciągu **30 dni**.

---

## 7. Bezpieczeństwo danych

Wdrażamy następujące środki techniczne i organizacyjne zapewniające bezpieczeństwo przetwarzania:

- 🔒 **Szyfrowanie transmisji**: wszystkie dane przesyłane do serwera są chronione protokołem HTTPS (TLS 1.2+)
- 🔒 **Szyfrowanie sesji w urządzeniu**: numer telefonu i PIN przechowywane są w zabezpieczonej pamięci urządzenia (Android Keystore)
- 🔒 **Autoryzacja dostępu**: dostęp do danych ze strony pracowników Sigma Pomiary kontrolowany poprzez system uprawnień
- 🔒 **Backup lokalny**: dane trasy zapisywane są również lokalnie w urządzeniu — w razie awarii sieci nie są tracone
- 🔒 **Audyty bezpieczeństwa**: okresowy przegląd zabezpieczeń aplikacji

---

## 8. Uprawnienia systemowe wymagane przez Aplikację

Aplikacja prosi o następujące uprawnienia systemowe Android:

| Uprawnienie | Po co używane |
|---|---|
| **Lokalizacja precyzyjna (GPS)** | Wyznaczanie pozycji pojazdu podczas śledzenia trasy |
| **Aparat** | Robienie zdjęć dokumentacyjnych |
| **Galeria (READ_MEDIA_IMAGES)** | Wybór istniejącego zdjęcia z lokalizacją z metadanych |
| **Powiadomienia** | Wyświetlenie informacji o aktywnym śledzeniu |
| **Foreground Service Location** | Możliwość śledzenia trasy gdy aplikacja działa w tle |
| **Internet** | Wysyłanie tras i zdjęć na serwer |

**Aplikacja NIE prosi o:**
- ❌ Dostęp do kontaktów
- ❌ Dostęp do SMS / połączeń telefonicznych
- ❌ Mikrofon
- ❌ Dostęp do plików spoza katalogu galerii
- ❌ Lokalizację w tle bez aktywnej notyfikacji

---

## 9. Dzieci

Aplikacja **NIE jest przeznaczona dla dzieci poniżej 16 roku życia**. Świadomie nie zbieramy danych osób niepełnoletnich. Jeżeli dowiemy się, że posiadamy dane dziecka, niezwłocznie je usuniemy.

---

## 10. Zmiany Polityki Prywatności

Niniejsza polityka może być okresowo aktualizowana. O istotnych zmianach poinformujemy:
- 📧 E-mailem do administratorów konta Sigma Pomiary
- 📱 Komunikatem w aplikacji przy pierwszym uruchomieniu po aktualizacji

Data ostatniej aktualizacji jest podana na początku tego dokumentu.

---

## 11. Kontakt

W razie pytań dotyczących przetwarzania danych osobowych:

- 📧 **E-mail**: sigmapomiarydev@gmail.com
- 📞 **Telefon**: +48500715992
- 📮 **Adres pocztowy**: Żegańska 16 / 10, 04-713 Warszawa, Polska

---

*Dokument przygotowany zgodnie z Rozporządzeniem Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. w sprawie ochrony osób fizycznych w związku z przetwarzaniem danych osobowych i w sprawie swobodnego przepływu takich danych (RODO).*
