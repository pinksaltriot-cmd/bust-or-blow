# Bust or Blow

A standalone meteorology sandbox. Engineer a single atmospheric column — six levels
(eye level, 5k, 10k, 18k, 30k, 40k ft) of temperature, pressure, and wind, plus five
soil-temperature depths and a moisture dial — over a US region. The game issues an
official forecast, and a 7-point slider (Big Bust → Bullseye → Big Blow) dials the actual
event anywhere inside the column's physically-bounded envelope, resolving to a full report
card: forecast vs actual, a severity index, the coined Bust–Blow Index (BBI), a narrative,
and a region map.

Open `index.html` in any browser — no build step, no dependencies.
Run `index.html?selftest=1` to execute the built-in engine test suite; it prints
`SELFTEST <pass>/<total> PASS|FAIL` to the console and to `#selftest .sum`.
