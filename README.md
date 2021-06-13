# Fetch CRA registered charities
This script fetches CRA registered charities by province.

This is a zx script (https://github.com/google/zx)

Use one of AB, BC, MB, NB, NL, NT, NS, NU, ON, PE, QC, SK, YT provincial and territorial code in line 4 of fetch-cra-charities.mjs file:
```
const SEARCH_PROVINCE = 'AB';
```

## Install
```bash
npm i -g zx
```

## Requirements
Node.js >= 14.8.0

## Run
```bash
chmod +x ./fetch-cra-charities.mjs
./fetch-cra-charities.mjs
```
Or via the `zx` executable:

```bash
zx ./fetch-cra-charities.mjs
```