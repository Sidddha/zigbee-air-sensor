# Zeegbee air quality sensor
Целью данного проекта является разработка конечного устройства обладающего следующим функционалом:
* Измерение температуры воздуха
* Измерение влажности воздуха
* Измерение содержания CO2
* Работа от батареи не менее 6 месяцев
* Беспроводное подключение по протоколу Zigbee, IEEE 802.15.4
* Отображение информации на TFT дисплее
## Железо
В качестве главного вычислительного устройства выбран модуль на основе распространенного и недорогого микроконтроллера [ESP32-H2-MINI-1U-N4](docs/esp32-h2_datasheet_en.pdf) на 32 битной архитектуре RISC-V, соответствующий стандарту [IEEE 802.15.4](docs/802.15.4-2003.pdf)

Для измерения температуры и влажности воздуха выбран комбинированный датчик [AHT10](docs/AHT10_en.pdf) с интерфейсом I2C.

Для измерения CO2 выбран датчик [CCS811](docs/CCS811_Datasheet.pdf)

Для индикации выбран RGB TFT дисплей 80x160 точек с контроллером [ST7725S](docs/ST7735S_V1.1.pdf)
