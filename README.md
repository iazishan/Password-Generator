# 🔐 Password Generator

A simple, user-friendly desktop application to generate secure passwords using a mix of letters, numbers, and symbols. Built with Python and Tkinter.

## 🖼️ Screenshot

*(Optional: Add a screenshot here by uploading it to the repo and linking it like this)*

```bash
![App Screenshot](screenshot.png)
```

---

## 🚀 Features

- Generate **easy** or **strong** passwords instantly
- Customize:
  - Number of letters
  - Number of numbers
  - Number of symbols
- Simple and clean GUI built with Tkinter
- Random password logic using Python's `random` module

---

## 🛠️ Technologies Used

- Python 3.x
- Tkinter (built-in GUI library)
- PyInstaller (for creating the `.exe`)

---

## 🧪 How to Run (Python Script)

If you have Python installed:

```bash
python PasswordGenerator.py
```

---

## 📦 Windows Executable

A standalone `.exe` is available in the [Releases](https://github.com/iazishan/Password-Generator/releases) section — no Python installation required!

---

## ⚙️ Building the `.exe` Yourself

If you'd like to generate your own `.exe` from the script:

1. Install PyInstaller:

   ```bash
   pip install pyinstaller
   ```

2. Build:

   ```bash
   pyinstaller --onefile --windowed PasswordGenerator.py
   ```

3. The `.exe` will be inside the `dist/` folder.

---

## 📂 Project Structure

```
Password Generator/
├── PasswordGenerator.py
├── README.md
├── .gitignore
├── dist/              # Output folder after building with PyInstaller
├── build/             # Temp build folder (can be ignored)
├── PasswordGenerator.spec
```

---

## 📄 License

MIT License. See [`LICENSE`](LICENSE) for details.

---

## 🙌 Acknowledgments

Inspired by common password security practices and built for fun and learning.
