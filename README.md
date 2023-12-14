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

# Zeegbee air quality sensor
The goal of this project is developing a device with the following functionality:  
* Measure air temperature
* Measure humidity
* Measure CO2 concentration
* Battery operation for at least 6 months
* Wireless connection through Zigbee protocol, IEEE 802.15.4
* Displaying information on the TFT screen
## Hardware
A module based on MC [ESP32-H2-MINI-1U-N4](docs/esp32-h2_datasheet_en.pdf) is chosen as the main computing unit.

Combined sensor [AHT10](docs/AHT10_en.pdf) is chosen for temperature and humidity measuring 

[CCS811](docs/CCS811_Datasheet.pdf) sensor is chosen for CO2 measuring

[ST7725S](docs/ST7735S_V1.1.pdf) display is chosen for indication