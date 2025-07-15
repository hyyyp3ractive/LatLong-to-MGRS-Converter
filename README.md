# LatLong to MGRS Converter

**LatLong to MGRS Converter** is an open-source toolkit designed for educators, GIS users, military trainers, and anyone needing to convert latitude/longitude coordinates to Military Grid Reference System (MGRS) format. This project makes it easy to generate MGRS map overlays, automate coordinate conversion, and support land navigation training or fieldwork.

---

## 🚀 Features

- Convert individual or bulk lat/long coordinates to MGRS
- Annotate existing maps with MGRS grid references
- Python scripts for custom workflows
- Printable tools (e.g., protractors, map grids) for hands-on training
- Sample lesson plans for land navigation courses

---

## 📦 Quick Start

1. **Clone or download this repository**
2. **Install Python dependencies:**  
   ```bash
   pip install mgrs
````

3. **Run the sample script:**

   ```bash
   python scripts/latlon_to_mgrs.py
   ```

---

## 🧭 Example Usage

```python
import mgrs
m = mgrs.MGRS()
print(m.toMGRS(38.8977, -77.0365))  # Output: 18SUJ2348068506
```

---

## 📚 Documentation

* [Getting Started Guide](docs/getting_started.md)
* [Land Navigation Lesson Plan](docs/lesson_land_nav.md)
* [Custom Map Grids](docs/map_grid_overlay.md)

---

## 🤝 Contributing

Pull requests are welcome! See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.
Feel free to open Issues for bugs, requests, or questions.

---

## 📝 License

* **Code:** MIT License (see [`LICENSE`](LICENSE))
* **Documentation & Lesson Plans:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 🔎 Keywords

MGRS, latitude, longitude, coordinate conversion, land navigation, GIS, military maps, Python, map overlays, teaching tools

---

*For questions, feedback, or to join the project, open an Issue or start a Discussion!*
