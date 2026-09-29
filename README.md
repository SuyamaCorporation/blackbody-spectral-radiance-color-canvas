# Blackbody Spectral Radiance Color Canvas

Interactive canvas showing how blackbody radiation spectrum shifts with temperature, with CIE color matching for accurate perceived color display.

## Features
- Temperature slider from 500K to 40,000K with live update
- Planck's law spectral radiance curve with visible spectrum gradient background
- CIE 1931 XYZ → sRGB color conversion for accurate blackbody color swatch
- Wien's displacement law peak marker on the spectrum canvas
- Multi-temperature comparison overlay (5 preset temperatures)
- 8 real-world presets: candle, tungsten, sunrise, daylight, Sun, blue sky, Sirius, blue star
- Stefan-Boltzmann total radiance displayed

## Usage
1. Drag the temperature slider or type a value in Kelvin
2. Click preset buttons to jump to named temperatures
3. Observe the color swatch change from deep red → orange → white → blue
4. The spectrum canvas shows the Planck curve with the λ_max marker

## Tech
- Tailwind CSS CDN
- Vanilla JS / Canvas API
- Planck's radiation law + CIE CMF approximation
