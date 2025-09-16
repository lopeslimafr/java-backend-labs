# Java Backend Labs

**Hands-on Java backend essentials — tested, automated, production-ready style.**

[![CI](https://github.com/lopeslimafr/java-backend-labs/actions/workflows/ci.yml/badge.svg)](https://github.com/lopeslimafr/java-backend-labs/actions/workflows/ci.yml) ![Java](https://img.shields.io/badge/Java-orange) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Tech Stack & Practices
- ✅ Java · **Maven Wrapper** · **JUnit 5** · **GitHub Actions CI**
- ✅ **Money-safe**: `BigDecimal` (`HALF_EVEN`)
- ✅ **Time-aware**: `java.time` (zone **Europe/Paris**)
- ✅ **Collections/Streams** (legible, tested)
- ✅ **CSV I/O** + clear error messages
- ✅ Focused labs tackling real backend scenarios

---

## Run (with Maven Wrapper)
```bash
./mvnw -v        # check Maven Wrapper version
./mvnw -q verify # build + run tests
# Windows:
# .\mvnw.cmd -v
# .\mvnw.cmd -q verify
