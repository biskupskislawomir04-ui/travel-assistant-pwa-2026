
# Multi-Utility Travel Assistant PWA (Japan & South Korea 2026)

## O projekcie
Kompleksowa, responsywna aplikacja mobilna typu **PWA (Progressive Web App)** zaprojektowana i wdrożona w celu obsługi logistycznej, finansowej oraz komunikacyjnej 6-osobowej grupy wyprawowej w Japonii i Korei Południowej. Aplikacja została zoptymalizowana pod kątem działania w trudnych warunkach mobilnych (roaming, ograniczony dostęp do sieci, oszczędzanie baterii) i dostarcza kluczowe narzędzia operacyjne w trybie offline.

## Główna funkcjonalność i moduły
*   **Interaktywny Itinerary (Plan Podróży):** Osi czasu dla poszczególnych dni wyprawy z dynamicznym podziałem na strefy czasowe, rekomendacje logistyczne oraz segmentację dedykowaną dla seniorów (zarządzanie obciążeniem fizycznym).
*   **Moduł State Management Check-In:** System monitorowania postępu podróży w czasie rzeczywistym. Pozwala użytkownikom odznaczać 22 kluczowe punkty orientacyjne. Stan jest persistowany lokalnie w przeglądarce , eliminując potrzebę stałego połączenia z bazą danych.
*   **Offline Currency Converter:** Autorski moduł przelicznika walut (PLN, JPY, KRW, EUR) bazujący na z góry zdefiniowanych relacjach kursowych, zoptymalizowany pod kątem natychmiastowego działania bez dostępu do sieci.
*   **Group Expense Splitter (Split Bill):** Zaawansowany algorytm kalkulacji kosztów grupowych z dynamicznym przeliczeniem na osobę w wybranej walucie oraz automatyczną konwersją ekwiwalentu do PLN.
*   **Rozmówki z integracją Web Speech API (TTS):** Moduł językowy wspierający natywne odtwarzanie audio (Text-to-Speech) fraz japońskich i koreańskich z dopasowanym współczynnikiem szybkości mowy (`rate: 0.85`) w celu ułatwienia komunikacji z lokalsami.
*   **Zarządzanie Energetyczne i UI/UX:** Pełna implementacja architektury hybrydowej Light/Dark Mode redukująca zużycie baterii na ekranach OLED podczas całodniowego zwiedzania.


