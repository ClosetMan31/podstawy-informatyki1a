 # Nagłówki HTTP

## Nagłówki odpowiedzi

1. **Content-Length**
   - **Opis**: Określa długość treści odpowiedzi w bajtach. Jest używany do określenia ile danych zostało przesłanych.

2. **Content-Type**
   - **Opis**: Określa typ mediów treści odpowiedzi. Informuje o formacie danych, np. `text/html`, `application/json`.

3. **Server**
   - **Opis**: Podaje informacje o serwerze, który obsłużył żądanie.

4. **Access-Control-Allow-Credentials**
   - **Opis**: Wskazuje, czy przeglądarka powinna zezwolić na użycie poświadczeń (takich jak ciasteczka, nagłówki autoryzacji) w żądaniach między domenami.

5. **Access-Control-Allow-Origin**
   - **Opis**: Określa, które domeny mają dostęp do zasobów na serwerze. Jest używany w mechanizmie CORS (Cross-Origin Resource Sharing).

## Nagłówki zapytania

1. **Connection**
   - **Opis**: Określa, czy połączenie powinno być utrzymane otwarte po zakończeniu bieżącego żądania. Wartości mogą być `keep-alive` lub `close`.

2. **Host**
   - **Opis**: Określa nazwę hosta i port, do którego jest kierowane żądanie. Jest to wymagane w przypadku żądań HTTP/1.1.

3. **Priority**
   - **Opis**: Używany do określenia priorytetu żądania. Może być używany do optymalizacji kolejności przetwarzania żądań.

4. **Sec-Fetch-Mode**
   - **Opis**: Określa tryb żądania, np. `navigate`, `no-cors`, `cors`, `same-origin`. Jest częścią mechanizmu Fetch Metadata, który pomaga chronić przed atakami typu cross-site request forgery (CSRF).

5. **Sec-Fetch-Site**
   - **Opis**: Określa kontekst źródła żądania, np. `same-origin`, `same-site`, `cross-site`. Pomaga w zabezpieczeniu aplikacji webowych przed atakami CSRF.