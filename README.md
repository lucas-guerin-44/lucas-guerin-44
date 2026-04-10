# Lucas G.

5 years in fullstack and product engineering: now focused on trading infrastructure and quantitative systems.

## Trading stack

A research-to-execution pipeline built from scratch:

| Repo | What it does |
|---|---|
| [backtesting-engine](https://github.com/lucas-guerin-44/backtesting-engine) | Event-driven backtester with tick-level fills, FIFO order book, latency modeling, Cython hot paths. The core. |
| [datalake-api](https://github.com/lucas-guerin-44/datalake-api) | Containerized REST + WebSocket API for OHLC and tick data. DuckDB for analytical queries, MT5/Dukascopy ingest. |
| [live-trading-dashboard](https://github.com/lucas-guerin-44/live-trading-dashboard) | React 19 + FastAPI dashboard. Streams live ticks, aggregates into candles in real-time, runs strategies with live P&L. |
| [fix-parser](https://github.com/lucas-guerin-44/fix-parser) | Zero-copy FIX 4.4 parser in Rust. SIMD field scanning, <100ns per message. Wire ingestion layer for the above. |

The fix-parser sits at the bottom of the stack — it's what would sit between a real broker FIX connection and the execution layer, translating wire bytes into the `Order`/`Fill` types the backtester already understands.

## Other

Python, TypeScript, Rust. Previously: product engineering, ML tooling, console modding.
