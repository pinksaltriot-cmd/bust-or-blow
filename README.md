# Bust or Blow

A standalone meteorology sandbox. Engineer a single atmospheric column — six levels
(eye level, 5k, 10k, 18k, 30k, 40k ft) of temperature, pressure, and wind, plus five
soil-temperature depths and a moisture dial — over a US region. The game issues an
official forecast, and a 7-point slider (Big Bust → Bullseye → Big Blow) dials the actual
event anywhere inside the column's physically-bounded envelope, resolving to a full report
card: forecast vs actual, a severity index, the coined Bust–Blow Index (BBI), a narrative,
and a region map.

**Challenge Mode** (the 🏆 button) turns the sandbox into a five-level game. Each level asks
for three specific events over specific regions — a Crippling blizzard over the Northern
Plains, an EF5 outbreak over the Southern Plains on a Bullseye — and later levels limit how
far the outcome dial may go, so the storm has to be built rather than dialed up. Every level
beaten makes your storms 10% stronger; from Level 4 on, some goals are out of reach without
that boost. Beating Level 5 unlocks a 15th region, **Continental**: the whole continent at
once, where storm dynamics build megastorms that dwarf even a lake-effect superstorm.
Progress is kept in the browser; the boost applies only while Challenge Mode is on.

Open `index.html` in any browser — no build step, no dependencies.
Run `index.html?selftest=1` to execute the built-in engine test suite; it prints
`SELFTEST <pass>/<total> PASS|FAIL` to the console and to `#selftest .sum`.
