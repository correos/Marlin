# Marlin 1.1.9
<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

# Anycubic Kossel Plus - TMC2130 SPI

Configurado para drivers tmc2130 controlados por SPI

## MiniGuia Calibración

1.  M119 (comprobamos endstops)

2.  M502 (factory reset)

3.  M500 (store settings)

4.  M503 (get current settings)

5.  G33 (auto calibration)

6.   Calibramos el z-offset

Ajustamos offset: M851 Zxx.xx

Ajustamos nueva altura: M665 Hxxx.xx ( (H_anterior) - Z-offset)

7.  M500 (store settings)
