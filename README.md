# system-zarzadzania-pracownikami-backend

Projekt systemu zarządzania pracownikami z wykorzystaniem Spring Boot [Rest API] BACKEND -> 5 mikroserwisów

Mikroserwisy Systemu Zarządzania Pracownikami:

1. Usługa bramy interfejsu API:
   API Gateway to komponent, który działa jako pojedynczy punkt wejścia dla aplikacji klienckich do interakcji z różnymi mikrousługami w systemie.

2. Usługa Rejestru Usług:
   Rejestr usług jest komponentem, który ułatwia wykrywanie usług i umożliwia mikrousługom lokalizowanie i dynamiczną komunikację między sobą.

3. Obsługa użytkowników pracowników:
   Mikroserwis Użytkownika Pracownika będzie obsługiwał wszystkie Operacje związane z Użytkownikiem.

4. Obsługa Działu Pracowników:
   Mikrousługa Działu Pracowników obsłuży wszystkie Operacje związane z Działem.

5. Obsługa wynagrodzeń pracowników:
   Mikroserwis dotyczący wynagrodzeń pracowników będzie obsługiwał wszystkie operacje związane z wynagrodzeniami pracowników.
