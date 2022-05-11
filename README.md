# Uppgift 3.

## Överblick
Uppgiften var ganska klurig. Blev mycket problem att få att vår TreeView att funka.

## Hur vi gjorde
Vi löste uppgiften genom att skapa en klass för varje handling som kan ske, och en basklass som representerar alla möjliga handlingar. Sen i vår kontroller så håller vi en lista på alla handlingar som skett, och en på alla handlingar som ångrats. Denna arkitektur gör det lätt att lägga till nya handlingar eftersom alla ställen som använder handlingar behandlar dem som dess basklass.

## Problem vi hade
Som sagt så var det klurigt att få vår handlingsarkitektur att fungera med TreeView komponenten. Vi löste det genom att söka upp det albumet som modifieras i trädet varje gång en handling sker eller ångras. Detta gör en O(1) operation till en O(n) operation, men det var den lösningen vi kom på.

## Användningsinstruktioner
Maven behövs för att run projektet.

Använd detta kommando för att köra det.
mvn javafx:run


## Diagramet

Efter att vi gjort programmerings delen började vi med UML-diagrammet. Vi använde samma plugin som förra gången för att göra diagrammet och det tog hälften mindre säätöä en i uppgift 1 att få pluginet att fungera.

Diagrammet finns i projektets root folder som filen diagram.png


## Grupp

William Flythström
Lucas Kujala
Ben Bergenwall
