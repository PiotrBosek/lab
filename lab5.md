# Lab 5
## Zad 1
* RFC 5321-Celem protokołu SMTP jestprzesyłać pocztę niezawodnie i wydajnie.
   SMTP jest niezależny od konkretnego podsystemu transmisji i wymaga jedynie niezawodnego uporządkowanego kanału strumienia danych.
* RFC 1939-węzeł, który daje wsparcie podmiotowi MTS oferuje usługę przesyłania poczty osobom mniej wyposażonym w węzły.
   Protokół Pocztowy - Wersja 3 jest przeznaczony do zezwolenia stacji roboczej na dynamiczny dostęp do zrzutu poczty na serwerze
   hostując w użyteczny sposób. 
* RFC 3501-Ten dokument jest napisany z punktu widzenia realizatora  klienta lub serwera IMAP4rev1.
 Poza przeglądem protokołów wsekcji 2 , nie jest zoptymalizowany dla kogoś, kto próbuje zrozumieć działanie protokołu.
 * RFC 5322- Ten dokument określa składnię IMF, dla wiadomości tekstowych przesyłanych pomiędzy użytkownikami komputerów w ramach tzw. „poczty elektronicznej”.
Ten dokument określa składnię tylko dla wiadomości tekstowych. W  w szczególności nie przewiduje przesyłania obrazów,
audio lub innego rodzaju danych strukturalnych w wiadomościach poczty elektronicznej.

## Zad 2
* Wysłanie wiadomości na swój adres email w domenie agh:
<img width="412" alt="image" src="https://user-images.githubusercontent.com/130838129/232294926-987d36a7-c9fd-4337-b1dc-05ed9164eab2.png">

## Zad 3
* Używam obecnego klienta pocztowego
## Zad 4 
<img width="677" alt="image" src="https://user-images.githubusercontent.com/130838129/232296412-9a02000d-a11e-4dd0-a2f8-1f04e91ac775.png">

## Zad 5
* Wykonane
## Zad 6
<img width="546" alt="image" src="https://user-images.githubusercontent.com/130838129/232297162-59567b4b-d068-49a9-96f4-7acee74cc0e1.png">

## Zad7 
* Na używanej przeze mnie poczcie, jest to opcja premium .
 <img width="689" alt="image" src="https://user-images.githubusercontent.com/130838129/232297563-c17fc4b9-dd0b-4575-8e84-c6802607070c.png">

## Zad 8
* W poczcie używanej przeze mnie nie ma takiej możliwości.

## Zad 9
<img width="731" alt="image" src="https://user-images.githubusercontent.com/130838129/232300243-9c5149db-970b-4bc7-bd51-4b76b1dc9747.png">

## Zad 10
<img width="541" alt="image" src="https://user-images.githubusercontent.com/130838129/232300419-2e367323-56e9-4c60-9bba-0789703a386d.png">
<img width="1069" alt="image" src="https://user-images.githubusercontent.com/130838129/232300666-8ea9d078-d61f-4d67-9df6-f46a024b187d.png">
<img width="1123" alt="image" src="https://user-images.githubusercontent.com/130838129/232300807-b415b589-2632-4fa0-a4fb-20cc3b31023b.png">

## Zad 11
* Wielkość przesyłanego maila jest w większościuzależniona od zawartości załącznika. Duży rozmiar przesyłanego pliku zwiększy rozmiar wiadomości.
 Na pocztach rozmiar pliku wysyłanego jest ograniczony.
## Zad 12
* Protokół POP3(Post Office Protocol 3) jest przeznaczony do pracy "offline". 
Po połączeniu z serwerem cała nieprzeczytana korespondencja wraz z załącznikami transmitowana jest ze skrzynki pocztowej na serwerze do foldera na komputerze lokalnym.
Odebrane listy zostają następnie oznaczone jako odczytane i, w zależności od ustawień, pozostawione lub (domyślnie) kasowane z serwera.
Po zakończeniu tych operacji, czytanie listów i przygotowywanie odpowiedzi może być przeprowadzone lokalnie bez konieczności utrzymywania połączenia z Internetem.

* Podczas stosowanie IMAP(Internet Message Access Protocol) cała poczta przechowywana jest na serwerze w skrzynce pocztowej i w dodatkowych folderach pocztowych.
Po połączeniu z serwerem na komputer lokalny transmitowane są jedynie same nagłówki wiadomości.
Transmisja treści oraz załączników następuje dopiero po otwarciu danego listu, dzięki czemu możliwe jest kasowanie i filtrowanie korespondencji bez jej pobierania z serwera.
Ten sposób obsługi poczty doskonale sprawdza się w przypadku pracy na wielu komputerach, na każdym z nich widzimy z tą samą zawartość skrzynki.
Wadą protokołu IMAP jest natomiast konieczność utrzymywania stałego połączenia z Internetem podczas obsługi poczty oraz trochę większa złożoność jego konfiguracji.
Dzięki IMAP, możemy sprawdzać, np. pocztę Gmail w innych klientach poczty, takich jak Microsoft OutlookiApple Mail.

* Podsumowując, IMAPi POP3to dwa sposoby odczytywania wiadomości z poczty.
 Protokół IMAPmoże być używany na wielu urządzeniach. E-maile są synchronizowane na bieżąco.Protokół POP3może być stosowany tylko na jednym komputerze.
 E-maile nie są synchronizowane na bieżąco, tylko pobierane z wybraną częstotliwością.
