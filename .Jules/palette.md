## 2024-05-22 - Metric-Driven UX Improvements
**Learning:** Hardcoded pixel metrics in C++ styles often age poorly as screen resolutions increase.
**Action:** When auditing legacy themes, check `metrics.h` or similar files first. Small increases in base units (e.g., 6px -> 8px) can dramatically modernize the look and feel without complex code changes.
