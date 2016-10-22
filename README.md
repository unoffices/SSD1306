# OrangePI_OLED
Add OLED display with sys info to your OPI board

+-----+-----+----------+------+---+--OrangePiPC--+---+------+---------+-----+--+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 |     |     |     3.3v |      |   |  1 || 2  |   |      | 5v       |     |     |
 |   2 |   8 |    SDA.0 | ALT5 | 0 |  3 || 4  |   |      | 5V       |     |     |
 |   3 |   9 |    SCL.0 | ALT5 | 0 |  5 || 6  |   |      | 0v       |     |     |
 |   4 |   7 |   GPIO.7 |  OUT | 1 |  7 || 8  | 0 | ALT3 | TxD3     | 15  | 14  |
 |     |     |       0v |      |   |  9 || 10 | 0 | ALT3 | RxD3     | 16  | 15  |
 |  17 |   0 |     RxD2 |  OUT | 0 | 11 || 12 | 0 | ALT3 | GPIO.1   | 1   | 18  |
 |  27 |   2 |     TxD2 | ALT3 | 0 | 13 || 14 |   |      | 0v       |     |     |
 |  22 |   3 |     CTS2 | ALT3 | 0 | 15 || 16 | 0 | ALT3 | GPIO.4   | 4   | 23  |
 |     |     |     3.3v |      |   | 17 || 18 | 0 | ALT3 | GPIO.5   | 5   | 24  |
 |  10 |  12 |     MOSI | ALT4 | 0 | 19 || 20 |   |      | 0v       |     |     |
 |   9 |  13 |     MISO | ALT4 | 0 | 21 || 22 | 0 | ALT3 | RTS2     | 6   | 25  |
 |  11 |  14 |     SCLK | ALT4 | 0 | 23 || 24 | 0 | ALT4 | CE0      | 10  | 8   |
 |     |     |       0v |      |   | 25 || 26 | 0 | ALT3 | GPIO.11  | 11  | 7   |
 |   0 |  30 |    SDA.1 | ALT4 | 0 | 27 || 28 | 0 | ALT4 | SCL.1    | 31  | 1   |
 |   5 |  21 |  GPIO.21 | ALT3 | 0 | 29 || 30 |   |      | 0v       |     |     |
 |   6 |  22 |  GPIO.22 | ALT3 | 0 | 31 || 32 | 0 | ALT3 | RTS1     | 26  | 12  |
 |  13 |  23 |  GPIO.23 | ALT3 | 0 | 33 || 34 |   |      | 0v       |     |     |
 |  19 |  24 |  GPIO.24 | ALT3 | 0 | 35 || 36 | 0 | ALT3 | CTS1     | 27  | 16  |
 |  26 |  25 |  GPIO.25 | ALT3 | 0 | 37 || 38 | 0 | ALT3 | TxD1     | 28  | 20  |
 |     |     |       0v |      |   | 39 || 40 | 0 | ALT3 | RxD1     | 29  | 21  |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+--OrangePIPC--+------+----------+-----+-----+
