# EURUSD PHASE II - DATA RECEIPT & DIGEST

Run: phase2_digest.py (python 3.12.14) at 2026-11-22 12:45:45 UTC. Input dir: `/workspace/EURUSD`. Files found: 12.

## MANIFEST

| file | bytes | md5 | rows | first bar | last bar | tf | claimed | actual | symbol |
|---|---|---|---|---|---|---|---|---|---|
| CCMonthCapture EURUSD h4 20130726-20231231.csv | 839440 | a367a8f0fe13280fcaea7501d5cb14fc | 14668 | 2013-07-26 05:00:00 | 2023-12-29 18:00:00 | h4 | 2013-2023 | 2013-07-26 05:00:00 .. 2023-12-29 18:00:00 | EURUSD |
| CCMonthCapture EURUSD h4 20160726-20261121.csv | 829917 | c43bb479f659c0d3d68879ef4f90f5cd | 14500 | 2016-07-26 17:00:00 | 2026-11-20 18:00:00 | h4 | 2016-2026 | 2016-07-26 17:00:00 .. 2026-11-20 18:00:00 | EURUSD |
| CCMonthCapture EURUSD t100 20230101-20231231.csv | 7879257 | 6b28de8f5098ce69c9003fb186fcafbf | 142052 | 2023-01-01 22:14:05 | 2023-12-29 21:56:19 | t100 | 2023 | 2023-01-01 22:14:05 .. 2023-12-29 21:56:19 | EURUSD |
| CCMonthCapture EURUSD t100 20240101-20241231.csv | 7668358 | 17b1dbeb1ef030d81ce8d775742d5c90 | 138033 | 2024-01-01 22:51:33 | 2024-12-31 21:57:24 | t100 | 2024 | 2024-01-01 22:51:33 .. 2024-12-31 21:57:24 | EURUSD |
| CCMonthCapture EURUSD t100 20250101-20251231.csv | 8330808 | aec5de382e3d86b364f0349d94279622 | 149933 | 2025-01-01 22:08:56 | 2025-12-31 21:55:42 | t100 | 2025 | 2025-01-01 22:08:56 .. 2025-12-31 21:55:42 | EURUSD |
| CCMonthCapture EURUSD t100 20260101-20260630.csv | 4728873 | 3b448a83dcecc59ba51ecb0ee86cb16c | 85112 | 2026-01-01 22:18:04 | 2026-06-30 23:56:33 | t100 | 2026 | 2026-01-01 22:18:04 .. 2026-06-30 23:56:33 | EURUSD |
| CCMonthCapture EURUSD t100 20260701-20261121.csv | 2994749 | cf3b0f988b069839e18ff26b4cbbf62b | 53898 | 2026-07-01 00:00:13 | 2026-11-20 21:50:05 | t100 | 2026 | 2026-07-01 00:00:13 .. 2026-11-20 21:50:05 | EURUSD |
| CCMonthCapture EURUSD t750 20220101-20221231.csv | 1507209 | b068ff827f12e0ac50dfe83337239ef0 | 27148 | 2022-01-02 23:05:58 | 2022-12-30 21:54:48 | t750 | 2022 | 2022-01-02 23:05:58 .. 2022-12-30 21:54:48 | EURUSD |
| CCMonthCapture EURUSD t750 20230101-20231231.csv | 1050416 | 52eff4e7980fd5ea9ddded88cb45781d | 18940 | 2023-01-01 22:48:12 | 2023-12-29 21:44:53 | t750 | 2023 | 2023-01-01 22:48:12 .. 2023-12-29 21:44:53 | EURUSD |
| CCMonthCapture EURUSD t750 20240101-20241231.csv | 1022244 | 9f4051eb5b996fa84260b342b0d9d78d | 18404 | 2024-01-01 23:41:48 | 2024-12-31 21:30:01 | t750 | 2024 | 2024-01-01 23:41:48 .. 2024-12-31 21:30:01 | EURUSD |
| CCMonthCapture EURUSD t750 20250101-20251231.csv | 1110776 | 0919bbf78de1c425c5b5d6e6da5e602c | 19991 | 2025-01-01 22:23:31 | 2025-12-31 21:02:57 | t750 | 2025 | 2025-01-01 22:23:31 .. 2025-12-31 21:02:57 | EURUSD |
| CCMonthCapture EURUSD t750 20260101-20261122.csv | 1029646 | bebdcae7ca588e84a0d3eb70474891af | 18533 | 2026-01-01 22:43:10 | 2026-11-20 20:52:35 | t750 | 2026 | 2026-01-01 22:43:10 .. 2026-11-20 20:52:35 | EURUSD |

- **h4**: 19168 rows (2 files), 2013-07-26 05:00:00 .. 2026-11-20 18:00:00; overlap 10000/10000 identical, 0 conflicts.
- **t100**: 569028 rows (5 files), 2023-01-01 22:14:05 .. 2026-11-20 21:50:05; overlap 0/0 identical, 0 conflicts.
- **t750**: 103016 rows (5 files), 2022-01-02 23:05:58 .. 2026-11-20 20:52:35; overlap 0/0 identical, 0 conflicts.

## FORMAT

- CCMonthCapture EURUSD h4 20130726-20231231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD h4 20160726-20261121.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t100 20230101-20231231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t100 20240101-20241231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t100 20250101-20251231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t100 20260101-20260630.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t100 20260701-20261121.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t750 20220101-20221231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t750 20230101-20231231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t750 20240101-20241231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t750 20250101-20251231.csv: 7 fields date,time,O,H,L,C,V confirmed
- CCMonthCapture EURUSD t750 20260101-20261122.csv: 7 fields date,time,O,H,L,C,V confirmed

## INTEGRITY

- **h4**: wrong-field-count 0; OHLC violations 0; duplicate ts 0; non-monotonic 0; zero-range 1; zero-volume 0.
- **t100**: wrong-field-count 0; OHLC violations 0; duplicate ts 0; non-monotonic 0; zero-range 0; zero-volume 0.
- **t750**: wrong-field-count 0; OHLC violations 0; duplicate ts 0; non-monotonic 0; zero-range 0; zero-volume 0.

## GAPS & SEAMS

Timezone evidence (finest timeframe t100): UTC: session-open days (first bar after a >6h gap) start at 21:00-23:59 in 100% of cases; the 21/22 split flips with US DST (EDT/EST), matching the 21:00/22:00 UTC session boundary (histogram in receipt.json).
- h4 (thr 10.0h): weekend 642, holiday 13, UNEXPLAINED 1.
- t100 (thr 6.0h): weekend 202, holiday 4, UNEXPLAINED 0.
- t750 (thr 6.0h): weekend 254, holiday 4, UNEXPLAINED 0.
  - UNEXPLAINED 2020-12-31 18:00:00 -> 2022-01-02 22:00:00 (8812.0h)
- holiday gaps by name: Christmas x11; New Year's Day x10
- hole map **h4**: 308 zero-bar days (incl. 48 Fridays - this timeframe has no Friday bars in part of its range): 2017-01-01, 2017-12-24 ... (full map in receipt.json)
- hole map **t100**: 2 zero-bar days: 2023-12-24, 2023-12-31
- hole map **t750**: 3 zero-bar days: 2022-12-25, 2023-12-24 ... (full map in receipt.json)
- weekend seams: 1096 total across timeframes, mean |drift| 0.06%, worst 5:
  - [h4] 2017-04-21 17:00:00 -> 2017-04-23 21:00:00 close 1.07238 reopen 1.09089 drift +0.01850 (1.73%)
  - [h4] 2015-06-26 17:00:00 -> 2015-06-28 21:00:00 close 1.11634 reopen 1.10055 drift -0.01580 (-1.41%)
  - [h4] 2022-02-25 18:00:00 -> 2022-02-27 22:00:00 close 1.12718 reopen 1.11280 drift -0.01440 (-1.28%)
  - [h4] 2015-07-03 17:00:00 -> 2015-07-05 21:00:00 close 1.11146 reopen 1.09879 drift -0.01270 (-1.14%)
  - [h4] 2015-01-02 18:00:00 -> 2015-01-04 22:00:00 close 1.20013 reopen 1.18778 drift -0.01230 (-1.03%)

## BAD TICKS

- **h4**: 15 flagged bars (delta_close x11; C x4; wick x4). Full rows in anomalies.csv.
- **t100**: 0 flagged bars (). Full rows in anomalies.csv.
- **t750**: 1 flagged bars (H x1). Full rows in anomalies.csv.

## CROSS-VALIDATION

- same-timeframe overlaps: h4 10000/10000 identical
- daily H/L t100 vs h4, printed-day: 1215 days, H match 138, L match 155
- daily H/L t100 vs h4, session-day: 1012 days, H match 122, L match 60

## CALIBRATION DIGEST

(per-year tables shown for 2021+; full history incl. pre-2021 in receipt.json. Cost tiers for EURUSD: base 0.0000, stress 0.0000 per unit = 0.10000/0.30000 pips, as % of avg bar range.)

### h4 (reference bars/day ~n/a; ref ticks/day ~n/a (no tick file this run))

- h4: cross-validation/synthetic frame; per-year table and 2021+ stats in receipt.json.

### t100 (reference bars/day ~n/a; ref ticks/day ~n/a (no tick file this run))

| year | bars | days | bars/day | ticks/day | min/bar | avg rng | med rng | avg rng % | base % | stress % |
|---|---|---|---|---|---|---|---|---|---|---|
| 2023 | 142052 | 311 | 456.8 | 45676.0 | 2.07 | 0.00029 | 0.00026 | 0.03 | 3.44 | 10.33 |
| 2024 | 138033 | 314 | 439.6 | 43960.0 | 2.15 | 0.00023 | 0.0002 | 0.02 | 4.31 | 12.93 |
| 2025 | 149933 | 312 | 480.6 | 48055.0 | 2.0 | 0.00032 | 0.00028 | 0.03 | 3.16 | 9.48 |
| 2026 | 139010 | 278 | 500.0 | 50004.0 | 1.87 | 0.00023 | 0.00021 | 0.02 | 4.28 | 12.84 |

- hourly bar density (00-24, printed hours): 00:19750 01:22642 02:17488 03:14417 04:12556 05:15886 06:23883 07:31196 08:31772 09:27753 10:24568 11:25185 12:35177 13:43179 14:46105 15:40113 16:29875 17:24426 18:23180 19:20736 20:13687 21:6461 22:8556 23:10437
- dead hours: none; top hours: 14,13,15,12,08,07
- Feb-Mar 2026: peak H 1.19286 @ 2026-02-10 14:34:11; max close 1.19282 @ 2026-02-10 14:33:26; max bar range 0.00725 @ 2026-03-06 21:56:41; max |dC| 0.62% @ 2026-03-06 21:56:41; March trough close 1.14126; drawdown from max close 4.32%.
### t750 (reference bars/day ~n/a; ref ticks/day ~n/a (no tick file this run))

- t750: cross-validation/synthetic frame; per-year table and 2021+ stats in receipt.json.


## PHASE II READINESS

- t500 ABSENT: MA layer not runnable; t500 exports required.
- t100 2023-01-01..2026-11-20: entry layer READY (569028 bars), but faithful-transpose cells NOT runnable - t500 MA layer absent, t500 exports required.
- not present in this run: t300, t500. t300 would be derivable from t100 (groups of 3, phase calibrated by sweep) if t100 present; t750 from t1 ticks (groups of 750) where tick coverage exists; neither is derivable from a coarser bar file alone.
- present extra timeframes enabling cross-validation: t750, h4. NOT present in this run: t300.
- No strategy backtest in this run - receipt and digest only; the strategy grid is a separate, later prompt.

## METHOD

- Tool: `phase2_digest.py` (python 3.12.14, stdlib only): `python3 phase2_digest.py <input_dir> [--instrument I --spread-base B --spread-stress S --pip P --synth-t500] [--out DIR]`; artifacts written next to the data; raw files read-only (in-memory copies).
- Parse: CSV, delimiter/header auto-detected; dates YYYY.MM.DD/YYYY-MM-DD/YYYY/MM/DD/YYYYMMDD; times HH:MM[:SS[.fff]]; bar files = 7 fields date,time,O,H,L,C,V (time,date auto-swapped); tick files = 4 fields date,time,bid,ask (ms timestamps) summarized as tick reference only. Bar timestamps are OPEN times, printed as-is; close-time = next bar open; last bar of each file open-ended.
- Symbol gate per file: median price outside the EURUSD range (0.5-2.0) => SUSPECT wrong symbol, excluded from merge, both readings reported. Refs: XAUUSD ~1798->~4500s; GBPJPY ~124-220; EURUSD ~0.8-1.6.
- Merge per timeframe: dedupe by timestamp across files; overlaps compared bit-for-bit on printed OHLCV; conflicts reported with both readings (first file kept for stats, count disclosed). Integrity: field count != 7; H < max(O,C) or L > min(O,C); duplicate/non-monotonic timestamps; zero-range; zero-volume.
- Gap threshold per timeframe = max(6h, 2.5x median inter-bar gap). Class: weekend = Thu/Fri/Sat -> Sun/Mon 40-80h (intraday DST-adjusted 48-50h: 49h + Sun-Fri UTC offset, 4h EDT / 5h EST); holiday = span covers a computed US federal holiday 1998-2026 (Good Friday via computus, observance shifts, + 2025-01-09); else UNEXPLAINED (each listed). Hole map: zero-bar dates in [first,last] excl. Saturdays + listed holidays.
- Bad ticks (instrument-scaled, % of price): |dClose| > 1.5% of prev close (across_gap if gap > threshold), wick (H-L) > 2.5% of close, H or C == next session's reopen open (3dp) after such a gap (feed-contamination class). All flagged -> anomalies.csv; nothing deleted or fixed.
- Cross-validation: same-timeframe overlap equality; t500 = groups of 5 consecutive t100 (all 5 phases swept from file start, exact OHLCV + span); t300 = groups of 3; t100/t750 vs groups of 100/750 t1 ticks (mid and bid); daily H/L of finest frame vs h4/d1 under BOTH day definitions: printed date and DST-aware session day (open 22:00 UTC EDT / 23:00 UTC EST); --synth-t500 builds t500 from t100 groups of 5 phase 0, marked SYNTHETIC (on XAUUSD native t500 matched phase 3, 375380/375380 exact, so synthetic phase-0 grid is not bit-identical to the native chart).
- Digest: per-year bars/day, implied ticks/day = bars/day x tick size, median min/bar, avg/median range and % of close; cost ratio = spread / avg range (base 1e-05, stress 3e-05 per unit = 0.1/0.3 pips); hourly density on printed hours; Feb-Mar 2026 blowoff/crash metrics; weekend seam drift = reopen - prior close. Timezone: session-open first-bar hour histogram of finest timeframe vs the 21:00/22:00 UTC boundary (DST-shifting).
- Budget: REPORT.md hard-capped at 15 KB (long lists truncated here; full detail in receipt.json / anomalies.csv). Prices 5dp, percentages 2dp, timestamps full date+time as printed.
