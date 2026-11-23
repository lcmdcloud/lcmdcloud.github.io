# LCMD Cloud · Product Pre-sale Materials & AI Model Store

Live GitHub Pages Portal: **https://lcmdcloud.github.io/**

- **中文入口 (Chinese)**: https://lcmdcloud.github.io/zh/
- **English Portal**: https://lcmdcloud.github.io/en/
- **AI 模型广场 / AI Model Store (Bilingual)**: https://lcmdcloud.github.io/model-store/

## Overview

This static portal hosts two bilingual (Chinese & English) sections maintained and published automatically from local infrastructure:

1. **Product Pre-sale Materials (售前资料)** — Auto-synced from `lcmd-product-pre-sale-information` (53 deliverables across 2 product lines: LCMD AI Pod X5-T5000, LCMD LC03 Micro Server).
2. **AI Pod Model Store (AI 模型广场)** — Auto-synced from LazyCat AI Pod v2.3.364 (58 public models across 19 capability categories, supporting AGX Thor, AGX Orin, and multi-node TP2/TP4 clusters).

## Deployment Policy

- Static files are built, translated, verified, and pushed directly from the local sync server daily (only when actual content changes).
- `.nojekyll` is enabled with **no custom GitHub Actions workflows**, keeping CI overhead at zero.
