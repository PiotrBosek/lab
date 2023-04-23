# Lab 2
## Zad 1
* Skorzystanie z komendy ip config w kosoli systemowej i sprawdzenie konfiguracji sieciowej komputera(Korzystanie z systemu windows)
 <img width="495" alt="image" src="https://user-images.githubusercontent.com/130838129/232223350-17509e8a-1307-41c8-9fae-548051aae023.png">
*  Windows posiada też inny sposób by to sprawdzić poprzez zastosowanie takiej kolejności wykonywania działania Ustawienia -> Sieć i Internet -> Zaawansowane ustawienia sieci -> Właściwości sprzętu i połączenia. W ten sposób widzimy wszystkie połączenia sieciowe.
 <img width="488" alt="image" src="https://user-images.githubusercontent.com/130838129/232223519-50445a6e-e59e-4b5c-b7a2-102f4e3e4110.png">

* W systemie linux mamy możliwość użycia tylko komendy ip config w konsoli systemowej cmd.

## Wyjaśnienie pojęć
* Adres fizyczny – adres pamięci pojawiający się w postaci liczby binarnej na szynie adresowej procesora w momencie odwoływania się do pamięci operacyjnej lub przestrzeni adresowej urządzeń wejścia-wyjścia.
* DHCP – protokół komunikacyjny umożliwiający hostom uzyskanie od serwera danych konfiguracyjnych, np. adresu IP hosta, adresu IP bramy sieciowej, adresu serwera DNS, maski podsieci. Protokół DHCP jest zdefiniowany w RFC 2131 ↓ i jest następcą BOOTP.
* Adres IP to liczba nadawana interfejsowi sieciowemu, grupie interfejsów (adresy typu broadcast, multicast), bądź całej sieci komputerowej, służąca identyfikacji elementów sieci oraz będąca jednym z elementów umożliwiających komunikację między nimi.
* Maska podsieci, maska adresu – liczba służąca do wyodrębnienia w adresie IP części będącej adresem podsieci i części, która jest adresem hosta w tej podsieci. Pola adresu IP, dla których w masce znajduje się bit równy 1, należą do adresu podsieci, a pozostałe bity do adresu urządzenia w tej podsieci.
* Brama domyślna inaczej Brama sieciowa – maszyna podłączona do sieci komputerowej, za pośrednictwem której komputery z sieci lokalnej komunikują się z komputerami w innych sieciach.
* Domain Name System – hierarchiczny rozproszony system nazw sieciowych, który odpowiada na zapytania o nazwy domen. Dzięki DNS nazwa mnemoniczna jest tłumaczona na odpowiadający jej adres IP.

## zad 3
* Komenda netstat wyświetla w postaci symbolicznej zawartość różnego rodzaju struktur danych sieciowych dotyczących aktywnych połączeń.
 <img width="535" alt="image" src="https://user-images.githubusercontent.com/130838129/232224074-9d16bbfb-f5f5-4304-a72f-c8c237d6b14b.png">
* Komenda netstat -ptona umożliwia nam zapoznanie się z odpowiednimi operacjami:
* p - pokazuje rodzaj protokołu
* t - wyświetla bieżący stan obciążenia połączenia
* o - dołącza identyfikatory PID, dzięki czemu możemy sprawdzić informacje o właścicielach portów dla każdego połączenia
* n - wyświetla aktywne połączenia TCP
* a - służy do wyświetlenia wszystkich aktywnych połączeń protokołu TCP i UDP, na których komputer nasłuchuje
 <img width="535" alt="image" src="https://user-images.githubusercontent.com/130838129/232224184-ad3b18fc-be1f-4a03-bbca-3a13d3f3fc0a.png">

## zad 4
* Ping – polecenie używane w sieciach komputerowych TCP/IP i służące do diagnozowania połączeń sieciowych. Pozwala na sprawdzenie, czy istnieje połączenie pomiędzy hostami testującym i testowanym. Umożliwia on zmierzenie liczby zgubionych pakietów oraz opóźnień w ich transmisji, zwanych lagami.
* Zakres agh:
 <img width="413" alt="image" src="https://user-images.githubusercontent.com/130838129/232224405-2b7304ab-8124-466e-8025-164a7fb63250.png">
<img width="442" alt="image" src="https://user-images.githubusercontent.com/130838129/232224533-8d089dc9-44cb-491c-a59c-66814adcc28e.png">

* Popularni dostawcy medialni:
 <img width="450" alt="image" src="https://user-images.githubusercontent.com/130838129/232224574-9af96d5c-0dee-473a-bd83-aa817b7f739e.png">
 <img width="410" alt="image" src="https://user-images.githubusercontent.com/130838129/232224583-0630d13b-73bf-4f7c-9fb8-64ee7563ebdc.png">

* Zagraniczne strony:
 <img width="423" alt="image" src="https://user-images.githubusercontent.com/130838129/232224741-3b8d73a5-be2c-4a4e-b910-7a0711a28f2b.png">
 <img width="427" alt="image" src="https://user-images.githubusercontent.com/130838129/232224703-94dc94b9-73a5-4f17-bfc4-081344951705.png">
* TTL-Czas życia pakietu, Time to Live – okres ważności pakietu danych lub innych danych, stosowany w sieciach komputerowych. Wbrew nazwie TTL nie zawsze określa czas. W przypadku czasu życia pakietów danych w sieci komputerowej jest to zwykle liczba przeskoków, które może on wykonać na swojej trasie.
* Time - czas potrzebny na wysłanie i powrotu pakietów
* Z powyższych screenów widzimy, że najdłuższy czas dotarcia był do amazonu, a najkrótszy do głównej strony agh, skoki do serwerów są wszędzie prawie same, bez zauważalnych dużych różnic.

## zad 5

* nslookup – polecenie to może być użyte w systemie Windows jak i Linux do wyszukiwania szczegółowych informacji odnoszących się do serwerów DNS włączając adres IP poszczególnych komputerów, nazwę domeny, czy aliasy jakie posiada.
 <img width="256" alt="image" src="https://user-images.githubusercontent.com/130838129/232225189-451ecdb7-043b-4ce2-8fd4-c7fb6faea24d.png">
* Pomijamy stronę biblioteki gdyż dalej jest niedostępna.
<img width="235" alt="image" src="https://user-images.githubusercontent.com/130838129/232225305-cbeeefa8-79fd-456a-a75d-560b3fbb8727.png">
<img width="227" alt="image" src="https://user-images.githubusercontent.com/130838129/232225324-0af5746a-f13d-4e2f-8455-b0b1fd43481e.png">
<img width="273" alt="image" src="https://user-images.githubusercontent.com/130838129/232225350-4e487ac4-0e90-42a9-bae2-57e81bd1b64e.png">
<img width="276" alt="image" src="https://user-images.githubusercontent.com/130838129/232225375-e781b8fe-c65e-4617-9c82-77b7fb0a73de.png">

## zad 6

Tracert służy do drukowania uporządkowanej listy routerów pośrednich, które zwracają ICMP "Przekroczony limit czasu" wiadomości.
<img width="485" alt="image" src="https://user-images.githubusercontent.com/130838129/232225692-c4ed0248-90b1-4c2c-b5a6-8f6a7fdf3703.png">
* Stronę bilioteki pomijamy jako że dalej jest niedostępna
<img width="681" alt="image" src="https://user-images.githubusercontent.com/130838129/232225816-a415cbd6-62e3-4595-a4b9-d7fee71f7e9e.png">
<img width="558" alt="image" src="https://user-images.githubusercontent.com/130838129/232225855-da2ad169-d8d4-476f-9aad-d0cd4c62a6ef.png">
<img width="644" alt="image" src="https://user-images.githubusercontent.com/130838129/232226116-eae362ff-6a0b-483d-a05e-5f08fb84c94f.png">
<img width="672" alt="image" src="https://user-images.githubusercontent.com/130838129/232226172-1f96e01d-3f13-400e-9d00-ba4aede9ed59.png">

## zad 8 

* Wireshark jest to program, który służy do analizy ruchu sieciowego.
