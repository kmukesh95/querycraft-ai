<div align="center">

# QueryCraft AI ⚡

**Production-Grade AI Engine for PostgreSQL Optimization, Refactoring, and Index Engineering**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14%20|%2015%20|%2016-336791.svg)](https://www.postgresql.org/)
[![Node.js](https://img.shields.io/badge/Node.js-%3E=18.0.0-green.svg)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6.svg)](https://www.typescriptlang.org/)

</div>

---

## 📌 Overview

**QueryCraft AI** transforms slow, unindexed, and anti-pattern-heavy raw SQL queries into enterprise-ready, high-performance PostgreSQL code. Backed by strict deterministic performance rules and LLM reasoning, QueryCraft analyzes execution bottlenecks, eliminates expensive sequential scans, suggests covering indexes, and outputs machine-readable JSON schemas ready for CI/CD integration.

---

## ✨ Core Capabilities

- **Automatic Query Refactoring:** Replaces correlated subqueries, non-SARGable predicates, large `OFFSET` clauses, and redundant joins with optimized CTEs, window functions, and cursor patterns.
- **Index Engineering:** Generates exact DDL with `CREATE INDEX CONCURRENTLY`, partial indexes, and covering indexes (`INCLUDE` clause).
- **Strict Data Correctness:** Preserves query semantics and edge-case NULL behavior without sacrificing accuracy.
- **Deterministic Structured Output:** Returns validated JSON with bottleneck summaries, impact scores, and rollback/validation statements.
- **CI/CD & Pre-commit Ready:** Integrate query audits directly into your pull request pipeline before code hits production.

---

## 🏗️ Architecture Flow
