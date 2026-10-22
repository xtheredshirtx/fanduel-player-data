# NBA player data - As of 10/22/2026

Every NBA player game we have, with FanDuel fantasy points, plus season summaries.

**Download:** [`NBA_player_data_as_of_2026-10-22.xlsx`](NBA_player_data_as_of_2026-10-22.xlsx) (Excel, Google Sheets, LibreOffice, Numbers) - the
first tab explains everything. Or open a CSV below; GitHub shows CSVs as a searchable table.

## Tabs
| Tab | What it shows | Rows |
|---|---|---|
| Summary | NBA: one row per player per season (per-game averages) | 1,473 |
| Game Log | NBA: one row per player per game | 56,786 |

## Coverage
| Group | Season | First game | Last game | Player-games | Players |
|---|---|---|---|---|---|
| NBA | 2026-27 | 2026-10-20 | 2026-10-21 | 322 | 322 |
| NBA | 2025-26 | 2025-10-21 | 2026-06-13 | 28,465 | 582 |
| NBA | 2024-25 | 2024-10-22 | 2025-06-22 | 27,999 | 569 |

## CSV files
- [`NBA_players_game_log_2024-25_as_of_2026-10-22.csv`](csv/NBA_players_game_log_2024-25_as_of_2026-10-22.csv)
- [`NBA_players_game_log_2025-26_as_of_2026-10-22.csv`](csv/NBA_players_game_log_2025-26_as_of_2026-10-22.csv)
- [`NBA_players_game_log_2026-27_as_of_2026-10-22.csv`](csv/NBA_players_game_log_2026-27_as_of_2026-10-22.csv)
- [`NBA_players_summary_as_of_2026-10-22.csv`](csv/NBA_players_summary_as_of_2026-10-22.csv)

## FanDuel scoring used
| Group | Stat | FD points | Note |
|---|---|---|---|
| All players | Point scored | +1 |  |
| All players | Rebound | +1.2 |  |
| All players | Assist | +1.5 |  |
| All players | Block | +3 |  |
| All players | Steal | +3 |  |
| All players | Turnover | -1 |  |

**Source:** NBA box scores (stats.nba.com via the nba_api package), regular season and playoffs. FanDuel points are calculated from those stats with FanDuel's published scoring - not supplied by FanDuel.
No FanDuel salaries, projections, ownership or contest results are included. Provided as-is; not affiliated with FanDuel or any league.
