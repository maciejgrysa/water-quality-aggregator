> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# Water Quality Aggregator

Python data pipeline that collects public water-quality reports from multiple municipal providers and normalizes them into one Excel workbook.

## Problem
Providers publish data as HTML tables, XLSX files, PDFs or multiple pages for individual treatment plants. Manual comparison is slow and inconsistent.

## Features
- pluggable extractors for multiple source formats
- one output sheet per city
- separate columns for every measurement point
- source caching and repeatable processing
- Excel export with pandas/openpyxl
- no LLM dependency in the extraction pipeline

## Stack
Python, httpx, pandas, lxml, openpyxl.

## Source access

The complete implementation is kept in a private source archive. For serious commercial discussions, a live walkthrough, architecture review, or controlled private code review can be arranged.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [PROPRIETARY-NOTICE.md](PROPRIETARY-NOTICE.md).
