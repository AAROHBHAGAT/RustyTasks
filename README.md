# 🦀 RustyTasks - A Command-Line To-Do App

RustyTasks is a simple and efficient command-line to-do application built in Rust.  
It helps you stay organized by allowing you to **add**, **list**, and **complete** tasks — all from your terminal.

## 📦 Features

- ✅ Add new tasks
- 📋 View all tasks
- 🗹 Mark tasks as done
- 💾 Persist tasks in a local file (`tasks.txt`) so your progress is saved even after you close the app

## 🧠 Why RustyTasks?

RustyTasks is designed to help you:
- Learn file I/O with `std::fs`
- Work with command-line input/output using `std::io` or crates like [`clap`](https://crates.io/crates/clap)
- Design structs and enums to manage tasks
- Practice error handling using `Result` and `?`

## 🛠️ Getting Started

### Prerequisites
- Rust installed. If not, install via [rustup](https://rustup.rs/)

### Clone and Build
```bash
git clone https://github.com/yourusername/rustytasks.git
cd rustytasks
cargo build --release
