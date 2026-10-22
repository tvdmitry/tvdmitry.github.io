# Auto parts search — GitHub Pages

Published application: https://tvdmitry.github.io/search-service/

The application is deployed only under `/search-service/`, not at the domain root.

All application source code and the reusable deployment workflow are maintained in [tvdmitry/Auto-parts-cross-reference-search-service](https://github.com/tvdmitry/Auto-parts-cross-reference-search-service).

To publish the latest `main` from the source repository, open **Actions → Deploy application to GitHub Pages → Run workflow** in this repository.

The application automatically uses the public key from the examples on page 3 of the Favorit Parts `wsprice.pdf` documentation. Visitors can search immediately by entering an article number; there is no API key form. Both search steps make real requests to Favorit Parts.
