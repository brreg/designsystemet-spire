# designsystemet-spire
This project is a Copy/Fork of prosject [@digdir/designsystemet](https://github.com/digdir/designsystemet-spire) to be used ONLY for 
training purposes and testing of spire designsystem (UNDER DEVELOPMENT)


The generated Theme is a NON OFFICIAL theme that replicates the theme  for the Brønnøysund Register Centre for use with [@digdir/designsystemet](https://github.com/digdir/designsystemet-spire)

[![Latest release](https://img.shields.io/npm/v/%40brreg%2Fdesignsystemet-spire-theme)](https://www.npmjs.com/package/@brreg/designsystemet-spire-theme)

Dette prosjektet er kopiert fra https://github.com/brreg/designsystemet/tags v0.2.11

## Gettings started:

### 1 Set up designsystemet
See https://github.com/digdir/designsystemet?tab=readme-ov-file#-get-started

### 2. Install theme
````
npm install @brreg/designsystemet-spire-theme
````

### 3. Import theme-css
````ts
import '@brreg/designsystemet-spire-theme/css/brreg.css'
````

## Contributing

### Updating CSS
CSS-files are automatically generated whenever changes to token-files are pushed to `main`-branch.

To update manually, run ```npm run build``` in your local repository.


### Publishing a new version
To release a new version of the package automatically , just bump the version in [package.json](package.json).

## ToDo
- Konfigurer changesets
  - Tags, release notes, PRs
- Konfigurer kode kvalitet for CSS
