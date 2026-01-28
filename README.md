

This repository contains the design files, firmware (coming soon), and documentation for my first full-size custom mechanical keyboard build. It features per-key RGB lighting, a rotary encoder, a small OLED screen, hotswap switches, and is powered by the RP2350 Stamp.

The images above are real custom/RGB keyboard builds for inspiration (my actual build photos coming soon!).
![Custom RGB Mechanical Keyboard Close-Up](https://images.pexels.com/photos/2115257/pexels-photo-2115257.jpeg)
![Illuminated Gaming Keyboard with RGB](https://p0.hippopx.com/preview/366/346/551/keyboard-led-gaming-illuminated.jpg)
![White and Red Mechanical Keyboard](https://images.pexels.com/photos/13728045/pexels-photo-13728045.jpeg)
![Orange RGB Mechanical Keyboard](https://c1.wallpaperflare.com/preview/130/391/604/mechanical-keyboard-gaming-keyboard-orange-led.jpg)
![Mountain Everest Max with Display and Knob (Inspiration)](https://www.cryovex.com/wp-content/uploads/2025/05/mountain-everest-max-modular-gaming-keyboard-review-Made-with-PosterMyWall.jpg)

## Features
- **Microcontroller**: RP2350 Stamp (Raspberry Pi Pico 2-based)
- **Switches**: 104× Gateron Yellow (linear, hotswap)
- **Per-Key RGB**: 104× SK6812MINI-E addressable LEDs
- **Input**: Rotary encoder (ALPS EC11)
- **Display**: Small OLED screen
- **Connectivity**: USB-C
- **Protection**: Resettable fuse, ESD/surge protection, logic level shifter
- **Build**: Custom PCB from JLCPCB, hand-assembled (or via JLC assembly)

## Bill of Materials
See the separate `BOM.md` file for the full parts list and cost breakdown (~$215–226 USD).

## Next Steps / TODO
- Upload KiCad PCB design files
- Add firmware (likely QMK or KMK)
- Build photos and assembly guide
- Case design (3D printed, acrylic, or custom?)

Feel free to fork, suggest improvements, or ask questions!  
Built by Ronan – January 2026
