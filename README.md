## Test Tareq Joumaa

# Solar ROI Calculator (Frappe App)

This app processes solar power data from an Excel file and automatically calculates:
- Average KW and KWH
- Monthly low and high tariff estimates based on time-of-use data

## Features
- Upload Excel files with `Timestamp`, `KW`, and `KWH` columns
- Auto-fill average metrics and monthly breakdown
- Supports low (off-peak) and high (peak) tariff calculations


### Installation

1. Clone this repo into your Frappe app directory:

```bash
git clone https://github.com/tareqjoumaa/test-tareq-joumaa.git

```

2. Install the app on the site::

```bash
cd ~/frappe-bench
bench --site site-name install-app test_tareq_joumaa

```