# Kopie zapasowe i odzyskiwanie danych

## Cel

Celem niniejszej sekcji jest określenie zasad tworzenia, przechowywania oraz przywracania kopii zapasowych danych przetwarzanych w systemie informatycznym przychodni lekarskiej. Regularne tworzenie kopii zapasowych ma na celu zabezpieczenie danych przed ich utratą, usunięciem lub uszkodzeniem.

---

## Zakres danych objętych kopią zapasową

Kopie zapasowe obejmują:

- Dane pacjentów (dane osobowe, dokumentacja medyczna, historia wizyt)
- Konta użytkowników i uprawnienia
- Rejestr logowań i działań w systemie
- Konfiguracje systemowe (ustawienia aplikacji, harmonogramy)

---

## Harmonogram tworzenia kopii zapasowych

- **Kopie dzienne (inkrementalne)** – wykonywane codziennie w
godzinach nocnych
- **Kopie pełne** – raz w tygodniu (np. w sobotę o 02:00)
- **Przechowywanie**:
- Kopie dzienne: przechowywane przez minimum 7 dni
- Kopie tygodniowe: przechowywane przez minimum 1 miesiąc

---

## Miejsce przechowywania kopii

- Kopie zapasowe są przechowywane:
   - Lokalnie (na serwerze kopii zapasowych)
   - Zdalnie (w zaszyfrowanym repozytorium w chmurze lub na nośniku
zewnętrznym)
- Kopie są szyfrowane algorytmem AES-256
- Dostęp do kopii mają wyłącznie administratorzy systemu

---