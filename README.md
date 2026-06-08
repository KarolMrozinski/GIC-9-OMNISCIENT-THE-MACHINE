# GIC-9 OMNISCIENT // THE MACHINE

**GIC-9 OMNISCIENT** to zaawansowane środowisko typu „Command & Control” w estetyce cyberpunkowej, zaprojektowane jako interaktywny pulpit nawigacyjny. Projekt wykorzystuje bibliotekę **CesiumJS** do wizualizacji danych geoprzestrzennych oraz oferuje bogaty zestaw narzędzi monitorujących, symulacji taktycznych i efektów wizualnych w czasie rzeczywistym.

## 🚀 Funkcje

- **Wizualizacja 3D (CesiumJS):** Dynamiczny glob z obsługą warstw chmur, satelitów oraz jednostek taktycznych.
- **Interfejs Cyberpunk:** Ciemny motyw, efekty glitch, animowane logi terminala i zaawansowane wskaźniki statusu.
- **Tryby Operacyjne:**
  - `Shadow Mode`: Zmiana palety barw i zwiększona agresywność efektów wizualnych.
  - `Ghost Mode`: Przełączanie widoczności interfejsu (ukrywanie HUD).
- **Symulacje Taktyczne:**
  - Dynamiczne śledzenie jednostek (Covert Assets).
  - Monitoring natężenia ruchu (Traffic Analyzer).
  - Symulacje uderzeń (Asteroid Strike, Blackout).
  - Neural Lattice (siatka neuronowa).
- **Interaktywność:**
  - System komend głosowych/tekstowych (Copilot).
  - Biometryczny monitoring w czasie rzeczywistym.
  - System powiadomień (Toasty, Alert Modals).

## 🛠 Technologie

- **HTML5 / CSS3 / JavaScript (ES6+)**
- **CesiumJS** (wersja 1.105)
- **Google Fonts** (JetBrains Mono)

## 📂 Struktura plików

- `index.html`: Główny plik aplikacji zawierający strukturę interfejsu, style CSS (w tym animacje glitch i overlaye) oraz logikę JavaScript (sterowanie Cesium, obsługa zdarzeń klawiatury, symulacje).

## 💻 Uruchomienie

Projekt nie wymaga kompilacji (tzw. "zero-config").
1. Pobierz plik `index.html`.
2. Otwórz go w nowoczesnej przeglądarce internetowej.
3. *Uwaga:* Ponieważ projekt korzysta z zewnętrznej biblioteki CesiumJS poprzez CDN, wymagane jest aktywne połączenie z Internetem do załadowania zasobów.

## ⌨️ Sterowanie (Skróty klawiszowe)

- `h`: Przełączenie widoczności interfejsu (Ghost Mode).
- `m`: Wyciszenie/włączenie audio (Toggle Audio).
- `Space`: Szybki skan (SCAN).

## ⚖️ Licencja

Projekt powstał w celach demonstracyjnych i edukacyjnych.

---

*Stworzono przy użyciu GIC-9 OMNISCIENT v23.0 // ARCHITECT EDITION.*
