# Graph Report - workspace  (2026-05-04)

## Corpus Check
- 57 files · ~904,927 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 417 nodes · 651 edges · 33 communities detected
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 47 edges (avg confidence: 0.79)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 36|Community 36]]

## God Nodes (most connected - your core abstractions)
1. `JSONStorage` - 26 edges
2. `FlaskManager` - 12 edges
3. `DashboardKPI` - 11 edges
4. `generateSystemCommand()` - 10 edges
5. `MetricsStorage` - 10 edges
6. `_process_object()` - 10 edges
7. `TelegramOrderProcessor` - 8 edges
8. `Daemon` - 8 edges
9. `detect_patterns()` - 8 edges
10. `generate_test_pnl()` - 8 edges

## Surprising Connections (you probably didn't know these)
- `generate()` --calls--> `sparkline()`  [INFERRED]
  demo_charts_ascii/generators/summary_gen.py → demo_charts_ascii/generators/base.py
- `_get_storage()` --calls--> `get_storage()`  [INFERRED]
  fundament_rf/routes/graphics.py → fundament_rf/storage.py
- `JSONStorage` --uses--> `FundObj`  [INFERRED]
  fundament_rf/storage.py → fundament_rf/models.py
- `MetricsStorage` --uses--> `FundObj`  [INFERRED]
  fundament_rf/storage.py → fundament_rf/models.py
- `create_object()` --calls--> `FundObj`  [INFERRED]
  fundament_rf/routes/api.py → fundament_rf/models.py

## Communities (38 total, 11 thin omitted)

### Community 0 - charts
Cohesion: 0.06
Nodes (38): create_candlestick_chart(), Candlestick chart visualization using Plotly., Create an interactive candlestick chart with pattern markers.          Args:, create_combined_chart(), Combined chart visualization using Plotly., Create a combined chart with candlesticks, patterns, and P&L.          Args:, Charts module for visualization., create_pnl_chart() (+30 more)

### Community 1 - storage.py
Cohesion: 0.11
Nodes (4): get_metrics_storage(), get_storage(), JSONStorage, MetricsStorage

### Community 2 - bitget_checker
Cohesion: 0.11
Nodes (5): BitgetAPIClient, main(), OrderData, Данные ордера с формулами PnL как в fundament_rf, TelegramOrderProcessor

### Community 3 - routes
Cohesion: 0.09
Nodes (16): _arc_path(), donut_chart(), _empty_donut(), get_mini_color(), get_roe_color(), heatmap_mini_cells(), kpi_card(), kpi_row() (+8 more)

### Community 4 - ui-ux-design-pro
Cohesion: 0.14
Nodes (19): auditCommand(), auditFile(), extractFont(), extractPrimaryColor(), extractStyleName(), generateArchitecturalPalette(), generateEnhancedMarkdown(), generateSystemCommand() (+11 more)

### Community 5 - routes
Cohesion: 0.11
Nodes (13): batch_process(), _build_chart_data(), _calculate_day(), _calculate_ranges(), _calculate_summary(), _fetch_candles(), _fetch_with_retry(), _force_object() (+5 more)

### Community 6 - infographics
Cohesion: 0.12
Nodes (3): CalendarHeatmap, DashboardCharts, EquityAnalyzer

### Community 7 - generators
Cohesion: 0.21
Nodes (15): generate(), plot(), plot_multi(), enrich_summary(), legend(), load_data(), sparkline(), generate() (+7 more)

### Community 8 - routes
Cohesion: 0.18
Nodes (16): all_charts(), calc_deviation(), chart(), _get_1m_price(), _get_current_price(), _get_daily_price(), _get_storage(), _parse_date() (+8 more)

### Community 9 - data
Cohesion: 0.12
Nodes (10): MarketDataFetcher, Market data fetcher using CCXT (Bitget)., Fetches market data from Bitget using CCXT., Get available trading symbols., Fetch OHLCV candlestick data.                  Args:             symbol: Trading, Get trading summary for a symbol., generate_test_candles(), Generate test data when API is unavailable. (+2 more)

### Community 12 - transcript_pipeline.py
Cohesion: 0.44
Nodes (11): build_markdown(), download_subtitles(), fetch_playlist_entries(), get_title(), main(), markdown_front_matter(), process_playlist(), process_single_video() (+3 more)

### Community 13 - routes
Cohesion: 0.24
Nodes (4): FundObj, create_from_emoji(), create_object(), parse_emoji_data()

### Community 14 - flask
Cohesion: 0.56
Nodes (9): cmd_restart(), cmd_start(), cmd_status(), cmd_stop(), handler(), is_running(), kill_flask(), log() (+1 more)

### Community 15 - flask-runner
Cohesion: 0.56
Nodes (9): cmd_restart(), cmd_start(), cmd_status(), cmd_stop(), handler(), is_running(), kill_flask(), log() (+1 more)

### Community 17 - transcript_pipeline.py
Cohesion: 0.47
Nodes (8): build_markdown(), download_subtitles(), get_title(), main(), markdown_front_matter(), summarize_text(), video_id_from_url(), vtt_to_text()

### Community 18 - playlist_transcript.py
Cohesion: 0.54
Nodes (7): download_subtitles(), fetch_playlist_entries(), get_title(), main(), process_video(), video_id_from_url(), vtt_to_text()

### Community 19 - migrate_to_card.py
Cohesion: 0.43
Nodes (6): cleanup_old_files(), get_symbol_from_json(), main(), migrate_trade(), Load trade JSON and extract symbol, Delete old 1D_ and RAW_ files after successful migration

### Community 20 - update_widgets.py
Cohesion: 0.38
Nodes (6): generate_html(), get_title(), main(), Get title from filename., Generate new HTML with dynamic iframe., Update all widget files.

### Community 22 - yt_transcript_ytdlp.py
Cohesion: 0.6
Nodes (5): ensure_dir(), extract_video_id(), fetch_subtitles(), main(), vtt_to_text()

### Community 23 - yt_transcript_ytdlp.py
Cohesion: 0.6
Nodes (5): ensure_dir(), extract_video_id(), fetch_subtitles(), main(), vtt_to_text()

### Community 25 - restart_flask.py
Cohesion: 0.83
Nodes (3): kill_flask(), restart(), start_flask()

### Community 26 - remove_system_reminder_from_zips.py
Cohesion: 0.83
Nodes (3): main(), process_archive(), remove_block_from_text()

## Knowledge Gaps
- **49 isolated node(s):** `Данные ордера с формулами PnL как в fundament_rf`, `PnL% = (Текущая - Вход) / Вход × 100`, `Текущая цена = Вход + (PnL$ / Объём)`, `Разница в днях (для emoji_upd)`, `emoji_entry: 🏗️ [number] 🚏[symbol] 🧾[entry] 📆[date] 🕒[days] 🧱[vol] 📈[%] 🫧[$] 📦[r` (+44 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **11 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `JSONStorage` connect `Community 1` to `Community 13`?**
  _High betweenness centrality (0.014) - this node is a cross-community bridge._
- **Why does `get_storage()` connect `Community 1` to `Community 8`?**
  _High betweenness centrality (0.009) - this node is a cross-community bridge._
- **Why does `_get_storage()` connect `Community 8` to `Community 1`?**
  _High betweenness centrality (0.008) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `generateSystemCommand()` (e.g. with `searchDesign()` and `generateTypographyScale()`) actually correct?**
  _`generateSystemCommand()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Данные ордера с формулами PnL как в fundament_rf`, `PnL% = (Текущая - Вход) / Вход × 100`, `Текущая цена = Вход + (PnL$ / Объём)` to the rest of the system?**
  _49 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.11 - nodes in this community are weakly interconnected._