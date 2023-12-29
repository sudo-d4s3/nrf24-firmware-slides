# nrf24-firmware-slides

## How to build html
```bash
pandoc slides.md -t revealjs -o slides.html --embed-resources --standalone --slide-level=3 -V theme=blood_mod -V revealjs-url=./reveal.js
```

if you have any issues make sure your version of pandoc is atleast 3.1.0.<br>
the package in the debian repo is a major version out of date
