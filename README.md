# PSB Football Animation Test

Single-sport Playwright test suite for PlanetSportBet Football animation (Live tracker) validation.

## Commands

```bash
npm ci || npm install
npx playwright install --with-deps chromium
npx playwright test tests/specs/planetsports/PSG.Football.Animations.spec.ts --project=chromium
```

Artifacts (HTML) are written to `test-results-html/` by Playwright config.
