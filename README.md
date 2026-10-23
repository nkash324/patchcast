# PatchCast

**Live: [nkash324.github.io/patchcast](https://nkash324.github.io/patchcast/)**

PatchCast forecasts how strong each League of Legends champion will be on a new patch, and keeps a public record of how right or wrong those forecasts were.

- **Forecast:** expected winrate for every champion, with a 95% range, from recent and long-run results, popularity, and that patch's balance and item changes.
- **Accuracy:** every forecast is made before the patch using only earlier data, then compared with what happened. The site shows forecast-vs-actual, calibration, and the average miss per patch next to the "luck floor".

This repo is the static site (HTML/JS). The data collection and models live in [GamePredictor](https://github.com/nkash324/GamePredictor).
