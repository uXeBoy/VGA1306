# VGA1306 (VGA-out for DIY Arduboys implemented on an FPGA!)

VGA1306.v & VGA1306.pcf are for the SSD1306 Emulation (4x scaling of the 128x64 frame)

VGA1306_640x320 is a variation of the SSD1306 Emulation (5x scaling of the 128x64 frame)

---

DMG1306.v & DMG1306.pcf are for the GameBoy VGA-out Implementation!

---

VGA1306_CS.v & VGA1306_CS.pcf are a variation of the SSD1306 Emulation, allowing for correct use of the CS (chip select) pin, in case there are other devices sharing the SPI bus.

VGA1306_V.v & VGA1306_V.pcf are another variation of the SSD1306 Emulation, allowing for 'vertical addressing' as used by: https://github.com/notro/fbtft/blob/master/fb_ssd1306.c
