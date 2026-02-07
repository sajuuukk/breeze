## 2024-05-22 - Metric-Driven UX Improvements
**Learning:** Hardcoded pixel metrics in C++ styles often age poorly as screen resolutions increase.
**Action:** When auditing legacy themes, check `metrics.h` or similar files first. Small increases in base units (e.g., 6px -> 8px) can dramatically modernize the look and feel without complex code changes.

## 2024-05-22 - Context is King: Pro vs. Consumer UX
**Learning:** "Modern" UX (spacing, large targets) can be actively harmful in professional contexts (CAD, IDEs) where information density and screen real estate are paramount.
**Action:** Before increasing margins or padding, explicitly identify the user persona. For "Creator" tools, prioritize density and precise interaction (e.g., visible splitters) over "breathing room".
