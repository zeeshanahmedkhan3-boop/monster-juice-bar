# Monster Juice Bar

A colour-mixing game for all ages, packaged as an Android app.

- The game is one file: `app/src/main/assets/index.html`. It runs offline and collects no data.
- Every push to `main` builds the app on GitHub Actions. Build files land on the `builds` branch.
- The release bundle is built unsigned and signed afterwards with the upload key, which is kept out of this repository.
