<p align="center"><img src="img/logo.png" width="120" alt="Fotool logo"></p>

<h1 align="center">Fotool</h1>
<p align="center"><b>Camera and lens simulator: from light to pixels</b><br>
<a href="https://andrea21s.github.io/Fotool/">andrea21s.github.io/Fotool</a></p>

Fotool shows what a photo really looks like with a given camera and lens, before you buy them or go out to shoot. Pick your gear, move focal length, aperture and shutter speed, and instantly see the photo and a 100% crop, with diffraction, lens aberrations, motion blur and noise.

It includes the JuzaPhoto database: over 1,400 cameras and 1,500 lenses and teleconverters, with compatibility between mounts, adapters and sensors.

> The interface is in Italian.

## Sections

- **Configura (Set up)**: choose camera, lens and teleconverter and see the photo in four scenes: landscape, portrait, Moon and backlight. Tiles summarise subject size, depth of field, exposure, noise and motion blur.
- **Confronta (Compare)**: up to four setups side by side. Duplicate one, change a single value and immediately see the difference in the photo and in the 100% crop.
- **Nitidezza (Sharpness)**: an optical bench showing how the light from a point reaches the pixels. It covers the Airy disk, the diffraction-limited aperture, critical sampling and the sharpest f-stop, plus a guided demo.
- **Database**: every JuzaPhoto entry, with search, filters, sorting and a link to the original page.
- **Guida (Guide)**: seven plain-language lessons, each with a small built-in simulator:
  - focal length;
  - aperture;
  - shutter speed;
  - aberrations;
  - pixels;
  - sensor size;
  - how they all work together.

## How it works

It is a single HTML page: no server, no install. It runs on phones, tablets and desktops, in light and dark mode. Your setups are saved in the browser.

The calculations use basic optics:
- diffraction (Airy disk), resolving power and pixel sampling (Nyquist);
- a simple model of lens aberrations;
- exposure with auto ISO, plus photon and read noise;
- motion blur from the Moon drifting across the sky and from handheld shooting with stabilisation.

They are estimates meant to show differences, not lab measurements.

Camera and lens data: [JuzaPhoto](https://www.juzaphoto.com).
