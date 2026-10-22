# NFL player data - As of 10/22/2026

Every NFL player game we have, with FanDuel fantasy points, plus season summaries.

**Download:** [`NFL_player_data_as_of_2026-10-22.xlsx`](NFL_player_data_as_of_2026-10-22.xlsx) (Excel, Google Sheets, LibreOffice, Numbers) - the
first tab explains everything. Or open a CSV below; GitHub shows CSVs as a searchable table.

## Tabs
| Tab | What it shows | Rows |
|---|---|---|
| Offense Summary | NFL Offense: one row per player per season (season totals) | 977 |
| Offense Game Log | NFL Offense: one row per player per game | 6,421 |
| Defense-ST Summary | NFL Defense-ST: one row per player per season (season totals) | 64 |
| Defense-ST Game Log | NFL Defense-ST: one row per player per game | 730 |
| Kickers Summary | NFL Kickers: one row per player per season (season totals) | 39 |
| Kickers Game Log | NFL Kickers: one row per player per game | 387 |

## Coverage
| Group | Season | First game | Last game | Player-games | Players |
|---|---|---|---|---|---|
| NFL Offense | 2026 | 2026-09-10 | 2026-10-20 | 1,673 | 452 |
| NFL Offense | 2025 | 2025-09-05 | 2026-01-05 | 4,748 | 525 |
| NFL Defense-ST | 2026 | 2026-09-10 | 2026-10-20 | 186 | 32 |
| NFL Defense-ST | 2025 | 2025-09-05 | 2026-01-05 | 544 | 32 |
| NFL Kickers | 2026 | 2026-09-10 | 2026-10-20 | 122 | 21 |
| NFL Kickers | 2025 | 2025-09-05 | 2026-01-05 | 265 | 18 |

## CSV files
- [`NFL_defense_st_game_log_2025_as_of_2026-10-22.csv`](csv/NFL_defense_st_game_log_2025_as_of_2026-10-22.csv)
- [`NFL_defense_st_game_log_2026_as_of_2026-10-22.csv`](csv/NFL_defense_st_game_log_2026_as_of_2026-10-22.csv)
- [`NFL_defense_st_summary_as_of_2026-10-22.csv`](csv/NFL_defense_st_summary_as_of_2026-10-22.csv)
- [`NFL_kickers_game_log_2025_as_of_2026-10-22.csv`](csv/NFL_kickers_game_log_2025_as_of_2026-10-22.csv)
- [`NFL_kickers_game_log_2026_as_of_2026-10-22.csv`](csv/NFL_kickers_game_log_2026_as_of_2026-10-22.csv)
- [`NFL_kickers_summary_as_of_2026-10-22.csv`](csv/NFL_kickers_summary_as_of_2026-10-22.csv)
- [`NFL_offense_game_log_2025_as_of_2026-10-22.csv`](csv/NFL_offense_game_log_2025_as_of_2026-10-22.csv)
- [`NFL_offense_game_log_2026_as_of_2026-10-22.csv`](csv/NFL_offense_game_log_2026_as_of_2026-10-22.csv)
- [`NFL_offense_summary_as_of_2026-10-22.csv`](csv/NFL_offense_summary_as_of_2026-10-22.csv)

## FanDuel scoring used
| Group | Stat | FD points | Note |
|---|---|---|---|
| Offense | Reception | +0.5 |  |
| Offense | Receiving yard | +0.1 | +3 bonus at 100+ |
| Offense | Receiving touchdown | +6 |  |
| Offense | Rushing yard | +0.1 | +3 bonus at 100+ |
| Offense | Rushing touchdown | +6 |  |
| Offense | Passing yard | +0.04 | +3 bonus at 300+ |
| Offense | Passing touchdown | +4 |  |
| Offense | Interception thrown | -1 |  |
| Offense | Fumble lost | -2 |  |
| Offense | Two-point conversion | +2 |  |
| Offense | Two-point return | +2 |  |
| Defense-ST | Sack | +1 |  |
| Defense-ST | Interception | +2 |  |
| Defense-ST | Fumble recovery | +2 |  |
| Defense-ST | Return touchdown | +6 |  |
| Defense-ST | Safety | +2 |  |
| Defense-ST | Blocked kick | +2 |  |
| Defense-ST | Points allowed tier | see note | 0 allowed +10, 1-6 +7, 7-13 +4, 14-20 +1, 21-27 0, 28-34 -1, 35+ -4 |
| Kickers | Field goal 0-39 yards | +3 |  |
| Kickers | Field goal 40-49 yards | +4 |  |
| Kickers | Field goal 50+ yards | +5 |  |
| Kickers | Extra point made | +1 |  |
| Kickers | Field goal missed | +0 |  |
| Kickers | Extra point missed | +0 |  |

**Source:** ESPN game box scores and play-by-play (player, defense and field-goal-distance lines). FanDuel points are calculated from those stats with FanDuel's published scoring - not supplied by FanDuel.
No FanDuel salaries, projections, ownership or contest results are included. Provided as-is; not affiliated with FanDuel or any league.
