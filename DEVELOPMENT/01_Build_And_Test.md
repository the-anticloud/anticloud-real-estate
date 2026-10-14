# Build and Test

**Project:** `REAL_ESTATE`
**Upstream:** https://github.com/liberu-real-estate/real-estate
**License:** MIT

## Quick Start

```bash
git clone https://github.com/liberu-real-estate/real-estate
cd real-estate
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local property description generation (offline, no API calls)
2. AES-256 encryption at rest for all tenant and lease records
3. Single-binary deployment via PyInstaller — no Docker, no cloud dependency
4. AIOSS append-only audit chain on every lease mutation and payment record
5. Offline floor plan analysis using quantized vision model
6. Zero-telemetry: all analytics replaced with local aggregation
7. CLI management interface replacing web-only admin panel
8. SQLite-first persistence replacing cloud database defaults

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Property description generation: <3s per listing on CPU |
| Throughput | 500 listings/hour offline batch |
| Memory | <4GB RAM baseline |
| Accuracy | Tenant satisfaction score parity with upstream UI |

## Build Status

Not yet measured. Run verified build and record actual figures above.
