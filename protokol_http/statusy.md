/**
 * Grupy statusów HTTP:
 * 
 * 1XX Informacyjne:
 * - 100 Continue: Serwer otrzymał początkową część żądania i klient może kontynuować przesyłanie.
 * - 101 Switching Protocols: Serwer akceptuje żądanie zmiany protokołu.
 * - 102 Processing: Serwer przetwarza żądanie, ale nie ma jeszcze odpowiedzi.
 * 
 * 2XX Sukces:
 * - 200 OK: Żądanie zakończyło się sukcesem.
 * - 201 Created: Żądanie zakończyło się sukcesem i zasób został utworzony.
 * - 202 Accepted: Żądanie zostało zaakceptowane do przetworzenia, ale nie zostało jeszcze zakończone.
 * - 204 No Content: Żądanie zakończyło się sukcesem, ale nie ma treści do zwrócenia.
 * 
 * 3XX Przekierowania:
 * - 301 Moved Permanently: Żądany zasób został trwale przeniesiony pod nowy URI.
 * - 302 Found: Żądany zasób znajduje się tymczasowo pod innym URI.
 * - 304 Not Modified: Żądany zasób nie został zmodyfikowany od ostatniego żądania.
 * 
 * 4XX Błędy klienta:
 * - 400 Bad Request: Serwer nie może przetworzyć żądania z powodu błędu klienta.
 * - 401 Unauthorized: Żądanie wymaga uwierzytelnienia.
 * - 403 Forbidden: Serwer rozumie żądanie, ale odmawia jego wykonania.
 * - 404 Not Found: Żądany zasób nie został znaleziony.
 * 
 * 5XX Błędy serwera:
 * - 500 Internal Server Error: Ogólny błąd serwera.
 * - 501 Not Implemented: Serwer nie obsługuje żądanej funkcjonalności.
 * - 502 Bad Gateway: Serwer otrzymał nieprawidłową odpowiedź od serwera pośredniczącego.
 * - 503 Service Unavailable: Serwer jest tymczasowo niedostępny.
 */