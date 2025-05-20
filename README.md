# 🍽️ restaurant_jolah — A Modular, Reusable Rust Library

This is a simple and educational reusable Rust library.

It demonstrates how to:
- Organize code with modules and files
- Control visibility using `pub`
- Build reusable components for a real-world-like domain

---


## Why This Is Reusable
- Clear modular structure: `front_of_house` vs `back_of_house`
- Controlled visibility using pub and private fields
- Public interface via `eat_at_restaurant()` or individual module APIs
- Separate file organization, for scalability.
  
## 📁 Project Structure

restaurant/ ├── Cargo.toml ├── src/ │ ├── lib.rs # Library root │ ├── front_of_house.rs # Handles customer interactions │ ├── back_of_house.rs # Kitchen logic │ └── bin/ │ └── main.rs # Binary example that uses the library


---

## 🚀 Getting Started

### Clone and Run

```bash
git clone https://github.com/jolah1/restaurant.git
cd restaurant
cargo run --bin main
```
### Example Usage

```bash
use restaurant::eat_at_restaurant;

fn main() {
    eat_at_restaurant();
}

```
### Output
```bash
Added to waitlist.
Added to waitlist.
I'd like Wheat toast please
```

### This repo is a practical reference for:

- Building Rust libraries with clear public APIs

- Managing code with modular file structure

- Using privacy rules to protect internal logic

- Preparing codebases for scalability and reusability




