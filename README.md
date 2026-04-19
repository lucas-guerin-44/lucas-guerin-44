# Lucas G.

5 years in fullstack and product engineering: now focused on trading infrastructure and quantitative systems.

## Trading stack

A research-to-execution pipeline built from scratch:

| Repo | What it does |
|---|---|
| [strategies-research](https://github.com/lucas-guerin-44/quant-strategies-research) |  A pipeline for killing bad trading-strategy ideas fast (and running the few that survive). |
| [backtesting-engine](https://github.com/lucas-guerin-44/backtesting-engine) | Event-driven backtester with tick-level fills, FIFO order book, latency modeling, Cython hot paths. The core. |
| [datalake-api](https://github.com/lucas-guerin-44/datalake-api) | Containerized REST + WebSocket API for OHLC and tick data. DuckDB for analytical queries. |
| [live-trading-dashboard](https://github.com/lucas-guerin-44/live-trading-dashboard) | React 19 + FastAPI dashboard. Streams live ticks, aggregates into candles in real-time, runs strategies with live P&L. |
| [fix-parser](https://github.com/lucas-guerin-44/fix-parser) | Zero-copy FIX 4.4 parser in Rust. SIMD field scanning, <100ns per message. Wire ingestion layer for the above. |

