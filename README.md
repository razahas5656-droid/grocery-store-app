# Grocery Store App

A grocery store management system built in Python, with three implementations of increasing complexity.

## 📁 Files
- `grocery_store_basic.py` — console app with JSON file persistence (inventory + sales)
- `grocery_store_advanced.py` — SQLite-backed version with:
  - User authentication (admin/customer, hashed passwords)
  - Product categories and search
  - Discount coupon codes
  - Low-stock alerts
  - Sales analytics (revenue by day, top products)
  - CSV export of inventory and sales
- `grocery_gui.py` — native desktop GUI built with Tkinter
- `grocery-market.html` — browser-based version with a custom "paper receipt" visual theme ([live demo](https://claude.ai/artifact/EVC57DRZwgMvH6xvTRrNP5))

## 🛠 Requirements
Standard library only — `sqlite3`, `json`, `csv`, `hashlib`, `tkinter`. No installs needed.

## ▶️ Running

```bash
python grocery_store_basic.py
# or
python grocery_store_advanced.py
# or
python grocery_gui.py
```

For the browser version, just open `grocery-market.html` in any browser.

## 👤 Author
Hasnain Raza
