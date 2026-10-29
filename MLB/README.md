# MLB player data - As of 10/29/2026

Every MLB player game we have, with FanDuel fantasy points, plus season summaries.

**Download:** [`MLB_player_data_as_of_2026-10-29.xlsx`](MLB_player_data_as_of_2026-10-29.xlsx) (Excel, Google Sheets, LibreOffice, Numbers) - the
first tab explains everything. Or open a CSV below; GitHub shows CSVs as a searchable table.

## Tabs
| Tab | What it shows | Rows |
|---|---|---|
| Hitters Summary | MLB Hitters: one row per player per season (season totals) | 1,118 |
| Hitters Game Log | MLB Hitters: one row per player per game | 86,103 |
| Pitchers Summary | MLB Pitchers: one row per player per season (season totals) | 1,407 |
| Pitchers Game Log | MLB Pitchers: one row per player per game | 35,414 |

## Coverage
| Group | Season | First game | Last game | Player-games | Players |
|---|---|---|---|---|---|
| MLB Hitters | 2026 | 2026-03-25 | 2026-10-28 | 50,019 | 650 |
| MLB Hitters | 2025 | 2025-03-18 | 2025-09-28 | 36,084 | 468 |
| MLB Pitchers | 2026 | 2026-03-25 | 2026-10-28 | 20,905 | 847 |
| MLB Pitchers | 2025 | 2025-03-18 | 2025-09-28 | 14,509 | 560 |

## CSV files
- [`MLB_hitters_game_log_2025_as_of_2026-10-29.csv`](csv/MLB_hitters_game_log_2025_as_of_2026-10-29.csv)
- [`MLB_hitters_game_log_2026_as_of_2026-10-29.csv`](csv/MLB_hitters_game_log_2026_as_of_2026-10-29.csv)
- [`MLB_hitters_summary_as_of_2026-10-29.csv`](csv/MLB_hitters_summary_as_of_2026-10-29.csv)
- [`MLB_pitchers_game_log_2025_as_of_2026-10-29.csv`](csv/MLB_pitchers_game_log_2025_as_of_2026-10-29.csv)
- [`MLB_pitchers_game_log_2026_as_of_2026-10-29.csv`](csv/MLB_pitchers_game_log_2026_as_of_2026-10-29.csv)
- [`MLB_pitchers_summary_as_of_2026-10-29.csv`](csv/MLB_pitchers_summary_as_of_2026-10-29.csv)

## FanDuel scoring used
| Group | Stat | FD points | Note |
|---|---|---|---|
| Hitters | Single | +3 |  |
| Hitters | Double | +6 |  |
| Hitters | Triple | +9 |  |
| Hitters | Home run | +12 |  |
| Hitters | Run batted in | +3.5 |  |
| Hitters | Run scored | +3.2 |  |
| Hitters | Walk | +3 |  |
| Hitters | Stolen base | +6 |  |
| Hitters | Hit by pitch | +3 |  |
| Pitchers | Win | +6 |  |
| Pitchers | Quality start | +4 |  |
| Pitchers | Earned run | -3 |  |
| Pitchers | Strikeout | +3 |  |
| Pitchers | Inning pitched | +3 |  |

**Source:** MLB Stats API box scores (statsapi.mlb.com). FanDuel points are calculated from those stats with FanDuel's published scoring - not supplied by FanDuel.
No FanDuel salaries, projections, ownership or contest results are included. Provided as-is; not affiliated with FanDuel or any league.
