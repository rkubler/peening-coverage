# peening-coverage
Interactive educational tool showing how surface coverage builds up during shot peening, as a function of the number of passes, media flow rate, particle size distribution, jet size and nozzle speed.
## Model
Coverage after n passes: τ(n) = 100·(1 − e^(−K·n)),
with K = 6·ṁ·c² / (ρ·D₃₂·V·ΔX) (Poisson / Avrami random impact model).

## Documentation
- [Coverage model note (PDF)](coverage_model_note.pdf)
- [Simulator technical note (PDF)](simulator_note.pdf)

## Limitations
Educational model with simplifying assumptions (uniform jet, random
impacts, dent radius proportional to shot diameter as initial guess). Not a substitute
for coverage verification per applicable standards (e.g. SAE J2277).

## Author and acknowledgement
Model and parameters: Regis KUBLER, Arts et Metiers Institute of Technology.
Simulator, documentation and Monte Carlo validation developed with the
assistance of Claude Opus 5.5 (Anthropic), October 2026 based on a simple Excel spreadsheet :-)

## Licence
Code: MIT. Documentation: CC BY 4.0.

## Cite as
https://doi.org/10.5281/zenodo.23195434
