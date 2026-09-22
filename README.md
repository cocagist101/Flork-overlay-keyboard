# 🎹 Flork Bongo Overlay

A lightweight, cute, and responsive desktop overlay featuring the iconic **Flork of Cows** meme character! The character animates and slaps its keyboard dynamically in response to your physical keyboard presses and mouse clicks.

![Flork Preview](https://via.placeholder.com/600x300.png?text=Flork+Bongo+Overlay+Preview) *(Thay link ảnh demo của bạn vào đây)*

---

## ✨ Features

- **Real-time Event Hooking**: Reacts instantly to any key press or mouse click (`Left` and `Right` clicks).
- **Custom Visuals**: Smooth Lanczos-resampled graphics with automatic background thresholding for crisp black-and-white visuals.
- **Built-in Keyboard**: Features a clean, custom-drawn dark mechanical keyboard positioned directly beneath Flork's hands.
- **Always on Top**: Floats cleanly over your games, streaming setups (OBS/Streamlabs), or workspace.
- **Draggable & Portable**: Left-click and drag anywhere to move; right-click to close immediately.
- **Standalone Distribution**: Can be compiled into a single `.exe` file without requiring Python installations or external folders.

---

## 🛠️ Built With

* **Python 3.x**
* **Tkinter** - GUI Framework
* **Pillow (PIL)** - High-quality image processing and resizing
* **keyboard & mouse** - System-wide event hooks
* **PyInstaller** - Standalone `.exe` packaging

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed, then install the required dependencies:

```bash
pip install keyboard mouse pillow
