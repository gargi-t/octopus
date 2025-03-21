# 🎨 **Colorama Python Script**

This script demonstrates how to add colors and styles to terminal text using the **`colorama`** library in Python.

---

## 📄 **Code Overview**

```python
from colorama import Fore, Back, Style, init
init()

print(Fore.BLUE + "hello world")
print(Style.RESET_ALL)
```

---

## 🚀 **How It Works**

1. **Imports Colorama Modules:**
   - `Fore` – Controls text color.
   - `Back` – Controls background color.
   - `Style` – Modifies text styles like bold or reset.
   - `init()` – Initializes Colorama for Windows compatibility.

2. **Prints 'hello world' in Blue:**
```python
print(Fore.BLUE + "hello world")
```

3. **Resets All Styles:**
```python
print(Style.RESET_ALL)
```

---

## 📦 **Installation**

To run this script, you need to install the `colorama` package. Use:
```bash
pip install colorama
```

---

## ▶️ **Usage**

1. Run the script:
```bash
python script.py
```
2. You’ll see `hello world` printed in blue, and the terminal will reset after that.

---

## 🎨 **More Examples**

- **Change Background Color:**
```python
print(Back.YELLOW + "This has a yellow background!")
```

- **Combine Foreground and Background:**
```python
print(Fore.RED + Back.WHITE + "Red text on white background!")
```

- **Apply Bright Styles:**
```python
print(Style.BRIGHT + "Bright text!")
```

---

## 📚 **Learn More**

- [Colorama Documentation](https://pypi.org/project/colorama/)
- Explore different colors, backgrounds, and styles to enhance terminal output.

---

## 📧 **Contributing**

Feel free to fork, raise issues, and submit pull requests! 😊

---

## 📝 **License**

This project is licensed under the MIT License.

---

## 🎉 **Happy Coding!** 🎯

