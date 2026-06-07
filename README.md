# Digital Journey Telemetry Engine

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SH76qZybrTGcWAqeL5NVtSpXqsFm8_S5?usp=sharing)

A high-fidelity behavioral analytics engine designed to ingest raw event logs, map multi-stage conversion funnels, and systematically isolate user friction points across digital product tracks.

## Core Architectural Impact

* Built clickstream telemetry engine
* Engineered database utilizing SQLite
* Mapped 25,000 user clickstream events
* Applied advanced analytical SQL
* Constructed multi-layered Common Table Expressions
* Implemented conditional aggregations
* Isolated multi-stage conversion friction points
* Quantified user drop-off metrics
* Modeled session-level behavior tracks
* Optimized relational query execution windows
* Structured clean analytical schemas
* Generated data-driven drop-off insights

## Analytical Methodology & Techniques

1. **Session-Level Reconstruction:** Aggregates unstructured event logs into sequential, time-bound user sessions.
2. **Advanced CTE Funneling:** Uses multi-layered Common Table Expressions (CTEs) to isolate precise milestones in the user conversion path.
3. **Friction Isolation:** Leverages conditional aggregations to calculate conversion rates and drop-off velocity between specific event triggers.

## Quick Start

Click the **Open in Colab** badge at the top of this page to launch the interactive notebook. The script automatically provisions an in-memory SQLite instance, seeds the 25,000 clickstream data matrix, and runs the entire analytical pipeline.
