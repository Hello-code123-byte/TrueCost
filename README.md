# TrueCost
Free, single-file 3D print cost and time estimator for Bambu Lab printers. Drop in an STL/3MF or enter slicer numbers to get filament, electricity and filter-wear costs. Runs in your browser, no uploads, no accounts. Independent project, not affiliated with Bambu Lab.

# TrueCost

Know what it costs before you hit print.

TrueCost is a free, single-file web tool that estimates the real cost and
print time of a 3D print. It's built with Bambu Lab P2S owners in mind
(including VentoBox filter wear), but the maths works for any printer if you
enter your own numbers.

> Independent project. Not affiliated with, endorsed by, or sponsored by
> Bambu Lab. "Bambu Lab" and "P2S" are trademarks of their respective owners.

## Features
- Drag and drop `.stl` or `.3mf` files, or enter filament grams and print
  time from your slicer
- 7 filament presets (PLA, PETG, ABS, ASA, TPU, Nylon, PC) and 4 nozzle
  sizes (0.2 to 0.8 mm)
- Inputs for spool size, spool price, infill and electricity rate
- Cost breakdown: filament, electricity (including heat-up), and VentoBox
  filter wear, with one total next to the print duration
- Built-in self-test for file parsing
- Private: files are read in your browser and never uploaded
- Dark by default, automatic light mode, works on phones

## Usage
Open `index.html` in a browser, or host it anywhere (GitHub Pages works well).
No build step, backend or account needed.

## Accuracy
Estimates from a model file are approximate. For the most accurate numbers,
use the filament weight and time from your slicer in manual mode.

## Dependencies
- [JSZip](https://stuk.github.io/jszip/) (loaded from a CDN) to read `.3mf`
  files. Used under the MIT license.

## License
MIT. See [LICENSE](LICENSE).
