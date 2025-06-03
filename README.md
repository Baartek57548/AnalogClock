# AnalogClock
esp8266 wifi clock


do wgrania: ## ✨ **Dodane funkcje lampki nocnej:**

### 🕐 **Harmonogram z minutową precyzją**

- **Konfigurowalny czas rozpoczęcia i zakończenia** (np. 22:00 - 06:00)
- **Automatyczna obsługa przejścia przez północ**
- **Precyzja do minuty** w ustawieniach czasu


### 🎨 **4 wzory świecenia**

1. **Dół** - delikatne oświetlenie dolnej części zegara (10 LEDów: 25-34)
2. **Rogi** - świecenie w pozycjach 12, 3, 6, 9 (4 LEDy: 0, 15, 30, 45)
3. **Własny** - możliwość wyboru dowolnych LEDów (0-59)
4. **Oddech** - delikatny efekt oddychania z funkcją `beatsin8()`


### ⚙️ **Pełna konfiguracja**

- **Regulowana jasność** (0-100%) z mapowaniem do FastLED
- **Wybór koloru** (domyślnie ciepły pomarańczowy `#ff8c00`)
- **Opcja pokazywania czasu** - przyciemnione wskazówki (1/4 jasności)
- **Test lampki** - 10-sekundowy podgląd z automatycznym wyłączeniem


### 🔧 **Inteligentne funkcje**

- **Automatyczne przełączanie** między trybem normalnym a nocnym
- **Status w czasie rzeczywistym** - pokazuje czy lampka jest aktywna
- **Następny czas** - wyświetla kiedy lampka się włączy/wyłączy
- **Zachowanie ustawień** w EEPROM z nową sygnaturą "CLK4"


### 📱 **Ulepszone API**

- **`/api/nightlight`** - konfiguracja lampki nocnej
- **`/api/nightlight/test`** - test 10-sekundowy
- **Rozszerzone `/api/status`** z informacjami o lampce nocnej


### 🌙 **Dedykowana zakładka "Lampka"**

- **Intuicyjna konfiguracja** z wizualnymi wzorami
- **Responsywny design** na wszystkich urządzeniach
- **Podgląd na żywo** aktualnego statusu w pasku statusu
