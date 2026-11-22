# OKAZJE_Monitor_01

Prywatne narzędzie do własnych zakupów. Aplikacja nie jest usługą dla innych sprzedawców i nie jest publicznie dostępna.

## Cel
Wyszukiwanie publicznych ofert (antyki, książki, sztuka polska) i zapisywanie ich lokalnie do własnej analizy cen.

## Sposób połączenia
- Aplikacja działa lokalnie na komputerze właściciela, bez przeglądarki (OAuth device_code).
- Tylko odczyt: wyszukiwanie publicznych ofert przez GET /offers/listing.
- Aplikacja nie wystawia, nie edytuje ani nie zamyka ofert i nie składa zamówień ani ofert kupna.

## Uprawnienia
- allegro:api:sale:offers:read — odczyt danych o ofertach (wyszukiwanie ofert).
Pozostałe uprawnienia nie są używane.

## Częstotliwość
Niska: do kilku tysięcy zapytań dziennie, z przerwami, w granicach limitów API. Nagłówek User-Agent identyfikuje aplikację.

## Dane
Dane trafiają wyłącznie do lokalnej bazy właściciela. Nie są udostępniane ani odsprzedawane. Dane sprzedających nie są zapisywane.

## Kontakt
pawelpawel33600@gmail.com
