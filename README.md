# 🧠 RPA Architecture for Legacy ERP Systems

This repository showcases the **architecture and methodology** behind a production RPA solution that successfully automates a legacy, browser-based ERP system with no API access.

## 🛠️ Production Challenge Solved

Built for a real-world scenario where modern integration wasn’t possible:

- Legacy web interface with nested framesets
- Dynamic element IDs that change unpredictably
- Multi-step authentication flows
- Critical business data extraction from invoice management system

## 🏗️ Architecture Approach

**Smart Navigation Strategy:**

- XPath selectors with fallback patterns
- Custom wait logic that adapts to system response times
- Frame-aware element detection
- Human-like interaction patterns to avoid detection

**Key Innovation:** Dynamic selector resolution that works even when the legacy system updates its internal structure.

-----

## 📊 Technical Stack

- **Python 3.x** - Core automation logic
- **Playwright (sync API)** - Browser control and interaction
- **Firefox headless** - Reliable rendering for legacy sites
- **Custom XPath patterns** - Robust element targeting
- **Adaptive error handling** - Graceful failure management
- **Simulated user behavior** - Natural interaction timing

-----

## 🎯 What You’ll Learn Here

✅ **Production-tested navigation patterns** for unpredictable legacy systems  
✅ **Error recovery strategies** that handle system timeouts and failures  
✅ **Modular architecture design** for maintainable RPA solutions  
✅ **Security considerations** for sensitive business data extraction

-----

## 💡 Key Insights Demonstrated

**Frame Management:**
Legacy systems often trap automation in nested frames. Our approach uses frame-aware selectors that automatically detect and switch context.

**Timing Resilience:**
Instead of fixed waits, we implement smart polling that adapts to system load variations - critical for production reliability.

-----

## 🚀 Business Impact

This approach has processed **thousands of invoices** with 99%+ accuracy, saving significant manual effort while maintaining data integrity standards required for financial operations.

-----

## 🧠 Author & Contact

Part of the **POA** (Personalized Operational AI) initiative - bringing modern automation capabilities to legacy business systems.

**Peter Ujvári**  
🔗 LinkedIn: [Peter Ujvári](https://www.linkedin.com/in/peter-ujvari-55442122a)  
🌐 Website: https://peterujvari.ai  
📩 Contact: peter@peterujvari.ai

-----

## 📌 Implementation Support

This repository demonstrates methodology and architectural decisions.

For custom RPA implementation or consultation on your legacy systems, reach out directly. Each solution requires domain-specific customization and ongoing optimization.

**© 2025 Ujvári Péter** - All rights reserved
