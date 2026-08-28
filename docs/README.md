 Asignación de Pines (Pinout) - Biel Core One 🦊

 1. Buses de Comunicación Principales

Pantalla AMOLED (CO5300)

 Interfaz MIPI-DSI dedicada (`DSI_D0+`, `DSI_D0-`, `DSI_CLK+`, `DSI_CLK-`)

Bus I2C-1 (Táctil y Sensores)

 `SCL`: GPIO 7
 `SDA`: GPIO 8
 Dispositivos: CST820 (Táctil), LSM6DSV (IMU 6 ejes), LIS2MDL (Magnetómetro)

Bus I2C-2 (Energía, Audio y Háptico)

 `SCL`: GPIO 18
 `SDA`: GPIO 19
 Dispositivos: BQ25896 (PMIC), CW2217 (Batería), AW86233 (Háptico), ES8311 (Códec Audio)

Bus SPI (NFC ST25R3916B)

 `SCK`: GPIO 11
 `MOSI`: GPIO 12
 `MISO`: GPIO 13
 `CS`: GPIO 10
 `IRQ`: GPIO 14

Bus SDMMC (MicroSD - 4-bit)

 Pines dedicados SD/MMC del ESP32-P4 (`CLK`, `CMD`, `D0`, `D1`, `D2`, `D3`)

---

 2. Audio e Infrarrojos

Interfaz I2S (Códec ES8311)

 `BCLK`: GPIO 20
 `WS`: GPIO 21
 `DOUT`: GPIO 22
 `DIN`: GPIO 23

Transceptor IR

 `IR TX`: GPIO 15
 `IR RX`: GPIO 16

---

 3. Controles e Interacción

D-Pad y Botones

 `Arriba`: GPIO 1
 `Abajo`: GPIO 2
 `Izquierda`: GPIO 3
 `Derecha`: GPIO 4
 `Botón A`: GPIO 5
 `Botón B`: GPIO 6

LED RGB (KTD2026)

 `DATA`: GPIO 9
