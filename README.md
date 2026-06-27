# 🚀 CppTrader

> **A High-Performance C++ Trading Engine Framework**

CppTrader is a modern C++ framework for building ultra-low latency trading systems. It provides a high-performance matching engine, order book management, and NASDAQ ITCH market data processing with a modular architecture suitable for quantitative trading platforms, exchanges, and market simulators.

---

## ✨ Features

* ⚡ Ultra-low latency matching engine
* 📈 High-performance order book implementation
* 🏦 NASDAQ ITCH market data parser
* 📊 Performance benchmarking suite
* 🧪 Comprehensive test suite
* 💻 Cross-platform support

  * Linux
  * Windows
  * macOS
* 🔧 CMake build system
* 📚 API documentation (Doxygen)
* 🧩 Modular architecture
* 🚀 Optimized implementations for maximum throughput

---

# Project Structure

```text
CppTrader
├── include/              # Public headers
├── source/               # Core implementations
├── examples/             # Example applications
├── performance/          # Benchmark applications
├── tests/                # Unit tests
├── modules/              # Third-party dependencies
├── tools/                # Sample datasets & scenarios
├── documents/            # Documentation
└── .github/              # GitHub Actions
```

---

# Core Components

### Matching Engine

Implements an efficient limit order matching engine supporting:

* Market Orders
* Limit Orders
* IOC Orders
* FOK Orders
* Order Replacement
* Order Cancellation
* Partial Execution
* Full Execution

---

### Order Book

Provides a high-performance order book with:

* Bid / Ask management
* Price level aggregation
* Best Bid / Best Ask retrieval
* Efficient order insertion
* Order deletion
* Order modification

---

### NASDAQ ITCH Handler

Includes a complete parser for NASDAQ ITCH market data capable of processing millions of market messages with extremely low latency.

Supported message processing includes:

* Stock Directory
* Add Order
* Execute Order
* Cancel Order
* Replace Order
* Delete Order
* Trade Messages
* Cross Trades
* NOII Messages
* Market Status Updates

---

# Performance

CppTrader focuses on ultra-low latency trading workloads.

## NASDAQ ITCH Processing

| Metric             |            Value |
| ------------------ | ---------------: |
| Messages Processed |      283,238,832 |
| Processing Time    |          6.831 s |
| Latency            |            24 ns |
| Throughput         | 41,460,256 msg/s |

---

## Market Manager

| Metric          |           Value |
| --------------- | --------------: |
| Processing Time |        87.616 s |
| Latency         |          309 ns |
| Throughput      | 3,232,727 msg/s |

---

## Optimized Market Manager

| Metric          |           Value |
| --------------- | --------------: |
| Processing Time |        34.150 s |
| Latency         |          120 ns |
| Throughput      | 8,293,747 msg/s |

---

## Aggressively Optimized Market Manager

| Metric          |           Value |
| --------------- | --------------: |
| Processing Time |        29.047 s |
| Latency         |          102 ns |
| Throughput      | 9,751,044 msg/s |

---

# Requirements

* C++17 or newer
* CMake ≥ 3.20
* Git
* Python 3
* GCC / Clang / MSVC

Optional

* CLion
* Doxygen
* Cygwin
* MSYS2
* MinGW

---

# Build Instructions

## Clone Repository

```bash
git clone https://github.com/27manavgandhi/cpptrader.git
cd cpptrader
```

---

## Configure

```bash
mkdir build
cd build

cmake ..
```

---

## Build

### Linux / macOS

```bash
cmake --build . --config Release
```

### Windows

```bash
cmake --build . --config Release
```

---

# Running Examples

Example applications are located in:

```text
examples/
```

Benchmarks:

```text
performance/
```

Tests:

```text
tests/
```

---

# Technologies

* C++
* STL
* CMake
* GitHub Actions
* Doxygen
* Catch2

---

# Highlights

* Ultra-low latency architecture
* Memory-efficient order book
* High-throughput message processing
* Modular trading engine
* Cross-platform support
* Extensive benchmarking
* Production-oriented design

---

# License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

---

# Acknowledgements

Original project architecture and implementation inspired by the CppTrader open-source trading engine.

---

⭐ If you found this project useful, consider giving it a star.
