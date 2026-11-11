# rates

Daily public reference data, updated once a day (~05:00 UTC) by an automated job.

- `latest.json` — latest FX rates (open.er-api, NBU, Monobank), stablecoin prices (CoinGecko),
  flexible Simple Earn rates (Bybit, Binance, OKX) and year-over-year inflation (BLS, Eurostat, IMF, NBU).
  Each record carries `fetched_at`; `stale: true` means the source did not answer and the previous value is kept.
- `history/fx.csv`, `history/earn.csv`, `history/inflation.csv` — daily history.

Raw URL: `https://raw.githubusercontent.com/Kostia8262/rates/main/latest.json`

Contains public market data only. No personal or account data.
