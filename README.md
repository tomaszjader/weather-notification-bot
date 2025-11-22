# Automatyzacja: Codzienna pogoda na Telegram

## Opis

Ta automatyzacja uruchamia się codziennie o 08:00. Pobiera pogodę z OpenWeatherMap. Formatuje dane w node Code. Pobiera ID czatu z DataTable. Wysyła wiadomość do Telegrama. Automatyzacja działa w n8n. Codziennie o 08:00 wysyła pogodę na Telegram. Dane pobiera z OpenWeatherMap.

## Działanie

1. Cron uruchamia workflow o 08:00.


2. HTTP Request pobiera pogodę z API.


3. Set formatuje dane do krótkiej wiadomości.


4. Telegram Node wysyła wiadomość.



## Wymagania

Klucz API OpenWeatherMap.

Bot Telegram.

Skonfigurowany node Telegram w n8n.


## Przykład wiadomości

🌤 Pogoda
Miasto: Warszawa
Temp: 12°C
Warunki: Chmury
Wiatr: 3.1 m/s

Możliwe rozszerzenia

Prognoza na kolejne godziny.

Ostrzeżenia pogodowe.

Formatowanie Markdown.


## Podsumowanie

Proste i szybkie rozwiązanie. Działa automatycznie. Łatwe w rozbudowie.