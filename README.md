# Salah Timings in CLI

## About
Get Salah (Namaz/Prayer) timings from https://salah.com right in the terminal!

## Installation

### Linux
```bash
curl https://raw.githubusercontent.com/AfzGit/salah-cli/main/salah --output salah
chmod a+x salah
sudo mv salah /usr/bin/ # or anywhere in PATH
```

## Usage

### Usage: salah [OPTIONS] [PRAYER]

- `salah fajr/f`
  - Get Fajr time
- `salah sunrise/s`
  - Get Sunrise time
- `salah dhuhr/d`
  - Get Dhuhr time
- `salah asr/a`
  - Get Asr time
- `salah magribh/m`
  - Get Maghrib time
- `salah isha/i`
  - Get Isha time
- `salah qiyam/q`
  - Get Qiyam time
- `salah all`
  - Get all times

### Options: [-f] [--format]
- `salah -f fajr`
  - To format and get only hour and minute numbers (like `4 55` instead of `4:55PM`)

## TODO
- Make option for showing only next prayer time
