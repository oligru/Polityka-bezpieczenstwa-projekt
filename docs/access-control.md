# Zarządzanie dostępem i hasłami

## Cel

Celem zarządzania dostępem jest zapewnienie, że tylko uprawnione osoby mają dostęp do systemów informatycznych przychodni oraz do danych medycznych pacjentów. System powinien wspierać autoryzację opartą na rolach i umożliwiać nadzorowanie logowań.

## Role i uprawnienia

Dostęp do systemu jest przyznawany zgodnie z przypisaną rolą użytkownika:

- **Administrator** – pełny dostęp do systemu, w tym do konfiguracji i zarządzania użytkownikami
- **Lekarz** – dostęp do danych medycznych pacjentów, kalendarza wizyt i dokumentacji
- **Rejestrator/Rejestratorka** – dostęp do terminarza, danych kontaktowych pacjentów, bez dostępu do dokumentacji medycznej
- **Pacjent** – dostęp tylko do własnych danych i historii wizyt

---

## Autoryzacja i uwierzytelnianie

- Logowanie do systemu wymaga podania **loginu i hasła**.
- Hasła muszą spełniać minimalne wymagania:
  - Minimum 8 znaków
  - Co najmniej jedna wielka litera, jedna cyfra i jeden znak specjalny
- Po 5 nieudanych próbach logowania konto zostaje tymczasowo zablokowane.

---

## Zasady nadawania i cofania dostępu

- Dostęp przyznawany jest przez administratora systemu na podstawie pisemnego wniosku kierownika działu.
- W przypadku zmiany stanowiska lub zakończenia współpracy, konto użytkownika musi zostać **niezwłocznie zablokowane lub usunięte**.
- Dostęp do systemu powinien być okresowo weryfikowany (co najmniej raz na 6 miesięcy).

---

## Monitorowanie i audyt

- Wszystkie logowania do systemu są rejestrowane w logach systemowych.
- Dostęp do logów ma tylko administrator systemu.
- W przypadku wykrycia nietypowych działań, administrator jest zobowiązany do podjęcia działań zgodnie z procedurą reagowania na incydenty.

---