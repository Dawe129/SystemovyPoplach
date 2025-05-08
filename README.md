# Postup ke spuštění programu
# Zapojení komponent:

## LCD displej (Grove LCD RGB Backlight):
SDA připojte na A4 (Arduino UNO)
SCL připojte na A5 (Arduino UNO)
VCC na 5V
GND na GND

## Ultrazvukový snímač HC-SR04:
Trig na D9
Echo na D10
VCC na 5V
GND na GND

## Klávesnice 4x3:
Řádky na A0, 2, 3, 4
Sloupce na 5, 6, 7

## Buzzer:
na D8
na GND

# Nahrání programu:
Otevřete Arduino IDE.
Nahrajte do Arduina kód z tohoto repozitáře.

## Ujistěte se, že máte nainstalované knihovny:
Keypad
Grove_LCD_RGB_Backlight (nebo rgb_lcd.h od Seeed Studio)

# Připojení napájení:
Připojte Arduino k PC nebo k napájecímu adaptéru (5V).

