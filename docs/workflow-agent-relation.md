---
section: Arbetsflöden katalogisering
title: Relationer till agenter, delar och verk
order: 34
date: 2018-09-28
tags:
- editor
- under arbete
---

## Relationer till agenter, delar och verk (7XX)

700, 710 och 711 är komplicerade fält i MARC21 som kan uttrycka olika saker om en agent, medverkande, relationer, och att en instans innehåller flera verk. 

Den här hjälpen visar hur man skapar relationer av olika typer. Länka i första hand till befintliga auktioriteter för personer, organisationer och möten. Om det inte finns en auktoritet så kan du skapa en auktoritet. Se hjälpen för att Skapa ny agent Person samt Organisation. Det finns även hjälp för att redigera befintliga auktoriteter. Se även hjälp för att lägga till Agent - Organisation

*I de första versionerna av nya Libris bör man inte länka till eller skapa nya verk, det är under utveckling.*

## Relationer

#### Relation uttryckt som Funktion (‡4)
Utgå ifrån Instans av Verk. Medverkande och funktion / Medverkan

Välj Medverkan när en agent har en relation till det verk som beskrivs i instansen.
* Medverkan och funktion / Medverkan / Agent / Person (700 1/- ‡a)
  Länka till entitet.

  I undantagsfall, skapa lokal entitet och välj Person
   * Lägg till Efternamn
   <br/>```Exempel: Andersson```
  
   * Förnamn
   <br/>```Exempel: Frans```
   
   * Levnadsår (700 ‡d)
    <br/>```Exempel: 1974-```

  * Funktion - klicka på plustecknet intill Funktion (700 ‡4)
    Länka till entitet.
    <br/>```Exempel: relator/trl (= översättare)```
    

#### Relation till verk uttryckt genom text (700 ‡i)
Det finns fasta termer i RDA för att uttrycka en relation till ett verk och som motsvarar delfält i i Exportformatet. Det är ännu inte möjligt att länka till dessa i nya Libris. Svensk översättning för relationerna behöver gås igenom.

Välj Relation vid plustecknet  vid Verk

Välj typ Relation i menyn

Välj Entitet vid plustecknet  vid Relation

Lägg till Verk som entitet. 
Vid plustecknet för Verk lägger man till delfält:

*  Benämning
  <br/>```Exempel: Parafraserar```
  
 *  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: Pride and prejudice```
 
*  Medverkande och funktion / Primär medverkan


Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.

   * Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a  ǂd )
   
   Länka i första hand till en agent.
    <br/>```Exempel: Austin,  Jane, 1775-1817```
 

#### Obestämt relation till ett verk (700)
Om relationen är viktig att beskriva och inte kan beskrivas på annat sätt, gör en allmän anmärkning (500 ‡a)

* Anmärkning (hasNote) Bygger på förf:s diss. med titeln: En sund själ i en sund kropp : hälsopolitik i Stockholms folkskolor 1880-1930

Välj Relation vid plustecknet  vid Verk

Välj typ Relation i menyn

Välj Entitet vid plustecknet vid Relation

Lägg till Verk som entitet. 

*  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: En sund själ i en sund kropp```
 
*  Medverkande och funktion / Primär medverkan


Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.

   * Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a  ǂd )
   
 Länka i första hand till auktoritet.
   <br/>```Exempel: Hammarberg, Lena, 1943-```
 

#### Flera verk kopplade till instansen
 Medverkan och funktion / Har del / Primär medverkan

Välj Primär medverkan när agenten har relation till ett annat verk än det som beskrivs i instansen

* Har del / skapa lokal entitet - välj Verk (långt ner i listan, ge inte upp! - i senare versioner kommer vi att förenkla detta.)
  * Har titel / Huvudtitel  - skriv in titeln
    <br/>```Exempel:  Mind over matter```
  
  
####  Fler delfält
  Fler delfält att lägga till vid plustecknet för Titeln som rör titeln:
  * Specificering i form av grupptitel (700 ‡k)
  * Delbeteckning (700 ‡n)
  * Deltitel (700 ‡p)
  
  Fler delfält att lägga till vid plustecknet för Verk som rör titeln:
    * Tid för verket (700 ‡f)
    * Språk  / Benämning (700 ‡l)
    * Besättning för framförande (700 ‡m) *Under utveckling*
    * Version (700 ‡o)
    * Tonart (700 ‡r)
    * (700 ‡s) *Under utveckling*
 

  Lägg därefter till Agenten:
  * Medverkan och medverkan / Primär medverkan / Agent/ Person
  
  Länka i första hand till agent. För att lägga till som lokal entitet:
  
  * Medverkan och funktion / Primär medverkan / Agent / Person / Efternamn
    <br/>```Exempel: Roberts```

  * Medverkan och funktion / Primär medverkan / Agent/ Förnamn
    <br/>```Exempel: Nora```
  
