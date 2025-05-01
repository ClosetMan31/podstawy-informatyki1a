a. Topologie fizyczne
1. Magistrala (Bus)
Opis: Wszystkie urządzenia są połączone do jednej wspólnej linii transmisyjnej.
Zalety:
Prosta i tania w implementacji.
Łatwa do rozbudowy.
Wady:
Awaria w jednym miejscu może wpłynąć na całą sieć.
Trudności w diagnozowaniu problemów.
Ograniczona wydajność przy dużym natężeniu ruchu.
Zastosowanie: Stosowana w małych i średnich sieciach, gdzie urządzenia są oddalone od siebie, np. w sieciach lokalnych (LAN).
2. Pierścień (Ring)
Opis: Urządzenia są połączone w zamknięty krąg, a dane krążą w jednym kierunku.
Zalety:
Niski koszt instalacji.
Prosta kontrola ruchu w sieci.
Wady:
Awaria jednego urządzenia lub kabla przerywa komunikację.
Wydajność spada wraz z rosnącą liczbą urządzeń.
Zastosowanie: Stosowana w starszych sieciach, takich jak Token Ring.
3. Gwiazda (Star)
Opis: Wszystkie urządzenia są połączone z centralnym urządzeniem (np. przełącznik lub koncentrator).
Zalety:
Łatwość w diagnozowaniu i naprawie problemów.
Skalowalność (łatwa rozbudowa).
Awaria jednego urządzenia nie wpływa na całą sieć.
Wady:
Zależność od centralnego urządzenia (awaria centrali może spowodować awarię całej sieci).
Wymaga więcej kabli niż inne topologie.
Zastosowanie: Najczęściej używana w sieciach LAN, np. w biurach, szkołach.
b. Topologie logiczne
1. Punkt-punkt (Point-to-Point)
Opis: Bezpośrednie połączenie między dwoma urządzeniami, bez pośredników.
Zastosowanie: Stosowane w połączeniach między dwoma punktami, np. w łączach WAN, VPN.
2. Przekazywanie żetonu (Token Passing)
Opis: W sieci krąży specjalny "żeton", który daje uprawnienie do wysyłania danych – tylko urządzenie posiadające żeton może nadawać.
Zastosowanie: Stosowane w sieciach Token Ring lub innych sieciach o kontrolowanym dostępie do medium.
3. Wielodostępowa (Multiple Access)
Opis: Urządzenia mają równy dostęp do medium transmisyjnego, ale muszą rozwiązywać kolizje (np. CSMA/CD w Ethernet).
Zastosowanie: Stosowane w sieciach Ethernet, Wi-Fi i innych, gdzie urządzenia współdzielą łącze transmisyjne.
