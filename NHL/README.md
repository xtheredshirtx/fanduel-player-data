# NHL player data - As of 10/27/2026

Every NHL player game we have, with FanDuel fantasy points, plus season summaries.

**Download:** [`NHL_player_data_as_of_2026-10-27.xlsx`](NHL_player_data_as_of_2026-10-27.xlsx) (Excel, Google Sheets, LibreOffice, Numbers) - the
first tab explains everything. Or open a CSV below; GitHub shows CSVs as a searchable table.

## Tabs
| Tab | What it shows | Rows |
|---|---|---|
| Skaters Summary | NHL Skaters: one row per player per season (season totals) | 1,449 |
| Skaters Game Log | NHL Skaters: one row per player per game | 52,191 |
| Goalies Summary | NHL Goalies: one row per player per season (season totals) | 147 |
| Goalies Game Log | NHL Goalies: one row per player per game | 3,062 |

## Coverage
| Group | Season | First game | Last game | Player-games | Players |
|---|---|---|---|---|---|
| NHL Skaters | 2026-27 | 2026-09-29 | 2026-10-26 | 6,622 | 702 |
| NHL Skaters | 2025-26 | 2025-10-07 | 2026-06-15 | 45,401 | 735 |
| NHL Skaters | 2024-25 | 2024-10-15 | 2025-06-18 | 168 | 12 |
| NHL Goalies | 2026-27 | 2026-09-29 | 2026-10-26 | 393 | 70 |
| NHL Goalies | 2025-26 | 2025-10-07 | 2026-06-15 | 2,659 | 75 |
| NHL Goalies | 2024-25 | 2024-10-05 | 2025-01-20 | 10 | 2 |

## CSV files
- [`NHL_goalies_game_log_2024-25_as_of_2026-10-27.csv`](csv/NHL_goalies_game_log_2024-25_as_of_2026-10-27.csv)
- [`NHL_goalies_game_log_2025-26_as_of_2026-10-27.csv`](csv/NHL_goalies_game_log_2025-26_as_of_2026-10-27.csv)
- [`NHL_goalies_game_log_2026-27_as_of_2026-10-27.csv`](csv/NHL_goalies_game_log_2026-27_as_of_2026-10-27.csv)
- [`NHL_goalies_summary_as_of_2026-10-27.csv`](csv/NHL_goalies_summary_as_of_2026-10-27.csv)
- [`NHL_skaters_game_log_2024-25_as_of_2026-10-27.csv`](csv/NHL_skaters_game_log_2024-25_as_of_2026-10-27.csv)
- [`NHL_skaters_game_log_2025-26_as_of_2026-10-27.csv`](csv/NHL_skaters_game_log_2025-26_as_of_2026-10-27.csv)
- [`NHL_skaters_game_log_2026-27_as_of_2026-10-27.csv`](csv/NHL_skaters_game_log_2026-27_as_of_2026-10-27.csv)
- [`NHL_skaters_summary_as_of_2026-10-27.csv`](csv/NHL_skaters_summary_as_of_2026-10-27.csv)

## FanDuel scoring used
| Group | Stat | FD points | Note |
|---|---|---|---|
| Skaters | Assist | +8 |  |
| Skaters | Blocked Shot | +1.6 |  |
| Skaters | Goal | +12 |  |
| Skaters | Power Play Assist | +0.5 |  |
| Skaters | Power Play Goal | +0.5 |  |
| Skaters | Shot on Goal | +1.6 |  |
| Skaters | Short Handed Assist | +2 |  |
| Skaters | Short Handed Goal | +2 |  |
| Goalies | Goals Against | -4 |  |
| Goalies | Shutout | +8 |  |
| Goalies | Save | +0.8 |  |
| Goalies | Win | +12 |  |

**Source:** NHL game-center box scores (api-web.nhle.com); earlier 2024-26 rows from a public NHL box-score file. FanDuel points are calculated from those stats with FanDuel's published scoring - not supplied by FanDuel.
No FanDuel salaries, projections, ownership or contest results are included. Provided as-is; not affiliated with FanDuel or any league.
