# FlaskGame

Zastanawiam się czy napisanie skomplikowanej aplikacji przy pomocy [Flaska](https://github.com/BotenAqua/WarframeInventoryHelper "Główne repozytorium") to nie jest lekka przesada na start a akurat wpadł mi do głowy raczej zabawny pomysł na grę z wykorzystaniem kości

## Pomysł

Gra będzie się opierała o prostą mechanikę symulacji rzutu kością (1-6) ale głównie chcę zaimplementować połączenie z usługami AWS w dużo mniejszej skali.

## Wykorzystane narzędzia

### Flask

Celem całego projektu jest przyspieszenie nauki Flaska

### Amazon Web Services

+ **DynamoDB** - Baza użytkowników i poziomów
+ **Cognito** - Zapisywanie postępów użytkowników poprzez prywatne profile 
+ **Amazon API Gateway** - Łączenie się z **DynamoDB** oraz **Cognito**
