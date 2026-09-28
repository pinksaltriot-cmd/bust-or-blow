> Yooper copy of `README.md` — da English original's right next to dis one, eh.

# Bust or Blow

A standalone meteorology sandbox. Build yerself a single atmospheric column — six levels
(eye level, 5k, 10k, 18k, 30k, 40k ft) of temperature, pressure, and wind, plus five
soil-temperature depths and a moisture dial — over a US region. Da game puts out an
official forecast, and a 7-point slider (Big Bust → Bullseye → Big Blow) dials da actual
event anywhere inside dat column's physically-bounded envelope, landin' on a full report
card: forecast vs actual, a severity index, da coined Bust–Blow Index (BBI), a narrative,
and a region map. Kinda like guessin' what Lake Superior's gonna do, ya know, only wit' a slider.

Open `index.html` in any browser — no build step, no dependencies.
Run `index.html?selftest=1` to kick off da built-in engine test suite; it prints
`SELFTEST <pass>/<total> PASS|FAIL` to da console and to `#selftest .sum`.
