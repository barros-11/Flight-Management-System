# Flight Management System ✈️

**University of Minho - Laboratórios de Informática III (2025/2026)**

## 📋 Project Overview

This project is a comprehensive C-based system developed to manage and analyze large datasets of flight information (Flights, Airports, Passengers, and Reservations). The application parses CSV data, validates integrity, and provides a high-performance query engine to extract statistics.

[cite_start]The development focuses on strict **Modularity** and **Encapsulation**, utilizing opaque pointers and separating interface from implementation[cite: 13, 14].

### Key Features
* [cite_start]**Data Parsing:** robust handling of CSV files with syntactic and logical validation[cite: 355].
* [cite_start]**Error Logging:** Invalid records are automatically filtered and logged to specific error files (e.g., `flights_errors.csv`)[cite: 361].
* [cite_start]**3 Execution Modes:** Batch processing, Interactive Terminal UI, and Automated Testing.
* [cite_start]**Performance:** Optimized data structures (Hash Tables/Trees) to handle large volumes of data[cite: 57].

---

## 🛠️ Installation & Dependencies

### Prerequisites
To compile and run this project, you need a Linux environment with the following dependencies installed:

* **Compiler:** `gcc`
* **Build System:** `make`
* **Libraries:**
    * [cite_start]`glib2.0` (for generic data structures) [cite: 166]
    * [cite_start]`ncurses`, `readline`, `history` (for the Interactive Mode UI) [cite: 166]

**Install dependencies (Ubuntu/Debian):**
```bash
sudo apt install gcc make libglib2.0-dev libncurses-dev libreadline-dev
