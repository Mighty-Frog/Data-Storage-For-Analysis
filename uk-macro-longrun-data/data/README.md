# UK long-run interest rate & house price (annual, cleaned)

This repo publishes a cleaned annual dataset (1917–2016) that aligns:
- UK policy interest rate (annual average, %)
- UK house price index (long-run series)

## Files
- `data/uk_interest_and_house_prices_boe_clean_1917_2016.csv`
- `data/uk_interest_and_house_prices_boe_clean_1917_2016_metadata.json`

## Source
Bank of England research dataset: “A millennium of macroeconomic data for the UK” (sheets A31 and A32).

## How to load
```python
import pandas as pd
url = "https://raw.githubusercontent.com/<USER>/<REPO>/main/data/uk_interest_and_house_prices_boe_clean_1917_2016.csv"
df = pd.read_csv(url)
