# phictrl
Old Philips projector control module



## Распределение периферии по портам/пинам.

### Светодиод на отладочной плате (LED) - отладка алгоритмов.

  - USER_LED : PC13

### Кнопка пользователя

  - USER_PB : PA0

### UART2 - Терминальный доступ к микроконтроллеру,

  - A2 (PA2,12) - TX2
  - A3 (PA3,13) - RX2
  - 115200 Baud,8,1,n

### Обмен с AD73360 SPI1

 - SPI1 CS/SCK/MISO/MOSI : PA4/PA5/PA6/PA7
 - Альтернатива - SPI1 CS/SCK/MISO/MOSI : PA15/PB3/PB4/PB5
 - Управление обменом

### Обмен с ILI, SPI2

 - SPI2 CS/SCK/MISO/MOSI : PB12/PB13/PB14/PB15

### Обмен с Orenge PI, SPI3 или UART1

 - SPI3 CS/SCK/MISO/MOSI : PA15/PB3/PB4/PB5
 - UART2 TX/RX : PA9/PA10
 - Baud >> 115200
