# 🧱 7-1 Style Architecture Showcase

This repository demonstrates how to apply the **7-1 style architecture pattern** across different UI frameworks — including **SCSS**, **XAML**, and **QML**.

> The "7-1 architecture" refers to organizing UI styles into 7 modular folders + 1 entry file (`main`), promoting maintainability, scalability, and separation of concerns.

---

## 🔧 Included Frameworks

| Framework                      | Folder  | Notes                                                       |
| ------------------------------ | ------- | ----------------------------------------------------------- |
| **SCSS**                       | `/scss` | Classic 7-1 pattern with `main.scss`                        |
| **XAML (WPF / MAUI / WinUI3)** | `/wpf`  | ResourceDictionary-based styling system                     |
| **QML (PySide6)**              | `/qml`  | Singleton-based `QtObject` tokens + componentized structure |

---

## 📦 Why 7-1?

The 7-1 architecture pattern offers:

- **Separation of concerns** – Colors, typography, spacing, and styles are split by purpose
- **Component-level reusability** – Styles and tokens for components are centralized
- **Scalability** – Each framework can scale with consistent structure
- **Framework-agnostic modeling** – Easy to port concepts across technologies

---
