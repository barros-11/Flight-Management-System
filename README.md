# Flight Management System ✈️

**University of Minho - Laboratórios de Informática III (2025/2026)**

## 📋 Project Overview

This project is a comprehensive C-based system developed to manage and analyze large datasets of flight information (Flights, Airports, Passengers, and Reservations). The application parses CSV data, validates integrity, and provides a high-performance query engine to extract statistics.

The development focuses on strict **Modularity** and **Encapsulation**, utilizing opaque pointers and separating interface from implementation.

### Key Features
**Data Parsing:** robust handling of CSV files with syntactic and logical validation.
**Error Logging:** Invalid records are automatically filtered and logged to specific error files (e.g., `flights_errors.csv`).
**3 Execution Modes:** Batch processing, Interactive Terminal UI, and Automated Testing.
**Performance:** Optimized data structures (Hash Tables/Trees) to handle large volumes of data.

---

## 🛠️ Installation & Dependencies

### Prerequisites
To compile and run this project, you need a Linux environment with the following dependencies installed:

* **Compiler:** `gcc`
* **Build System:** `make`
* **Libraries:**
    * `glib2.0` (for generic data structures) 
    * `ncurses`, `readline`, `history` (for the Interactive Mode UI)

**Install dependencies (Ubuntu/Debian):**
```bash
sudo apt install gcc make libglib2.0-dev libncurses-dev libreadline-dev
```

* **`programa-principal`**: Batch processing engine.
* **`programa-interativo`**: Terminal-based user interface.
* **`programa-testes`**: Automated testing and benchmarking tool.

---

# 💻 Usage & Execution Modes

The application supports three distinct modes of execution.

### 1. Batch Mode (Principal)
This is the main processing engine used by the automatic evaluation platform. [cite_start]It accepts a dataset directory and a file containing a list of commands [cite: 209-211].

**Syntax:**
```bash
./programa-principal <dataset_path> <input_file>
```

## Interactive Mode

A user-friendly terminal interface that allows users to explore the data dynamically.
Syntax:
```bash
./programa-interativo
```

### Features:

    Prompts for the dataset path upon launch.

    Menu-driven query selection.

    Paginated output for large results.

### Interface Previews:

    Main Menu Select queries and load datasets easily via the text-based UI.

    Query Results View formatted results directly in your terminal.
<img width="536" height="297" alt="image" src="https://github.com/user-attachments/assets/2535ba35-64ba-4446-85ca-41abe9b1390e" />



## Test Mode

This mode is used to validate the correctness of the implementation and measure performance (time and memory). It compares the program's output against a set of expected results .

Syntax:
```bash
./programa-testes <dataset_path> <input_file> <expected_output_dir>
```

# 📂 Project Structure

The project follows the mandatory directory structure :
<img width="825" height="264" alt="image" src="https://github.com/user-attachments/assets/c2e5b65e-59b2-4da8-bd1a-3a3570b5f79d" />



# 👥 Authors
Afonso Barros (A112178)
Tomás Ferreira (A11018)
Lucas Pinto (A111442)
