**Jest to płytka (10 × 10 cm) z procesorem Cortex M0+, zaprojektowana do testów urządzeń komunikujących się przez różne interfejsy.**

##Główne cechy:

**Procesor:** ARM Cortex M0+
**Interfejsy komunikacyjne:**
- SWD (Serial Wire Debug) – programowanie i debugowanie
- SPI (Serial Peripheral Interface)
- UART (Universal Asynchronous Receiver/Transmitter)
- CAN (Controller Area Network)
- USB (Device mode)

**Zasilanie:**
- Wbudowana przetwornica AC/DC
- Zasilanie z gniazda 230 VAC
- Wbudowane napięcia wyjściowe: 5 V i 3.3 V
**Wymiary PCB:** 10 × 10 cm

**Symulacje:** Przetwornica została zasymulowana w LTspice.

/projekt
  ├─ ltspice/         # Symulacje przetwornicy w LTspice
  ├─ Lib_CAN/      	  # Biblioteka z modelami dla Kicad
  ├─ BOM/             # Lista użytych footprintów
  ├─ README.md        # Ten plik
  └─ CAN_t_b.jpg      # Obraz z widoku 3D
