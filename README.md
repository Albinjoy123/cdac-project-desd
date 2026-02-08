Developed a hot-swappable dual-application
system on STM32F407, where two
independent firmware images are stored at
fixed flash addresses and switched at
runtime using a button interrupt. Each
application integrates a lightweight
embedded Al/ML model to classify
temperature data into Cold, Warm, or Hot
categories. Temperature data from a DHT11
sensor is transferred to an ESP32 via SPI and
uploaded to AWS Lambda using HTTP POST
An OLED display (12C) and UART logging
(PuTTY) are used for real-time temperature
visualization, ML inference output, and
system debugging
