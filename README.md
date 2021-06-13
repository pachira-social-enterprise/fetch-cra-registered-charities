# Fetch CRA registered charities
This is a zx script (https://github.com/google/zx) that fetches CRA registered charities by province.



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
Or execute it remotely:
```bash
zx https://raw.githubusercontent.com/pachira-social-enterprise/fetch-cra-registered-charities/main/fetch-cra-charities.mjs
```
When prompted 
`Choose provincial and territorial code (AB, BC, MB, NB, NL, NT, NS, NU, ON, PE, QC, SK, YT):`
Type two-letter abbreviations for Canadian provinces and territories.