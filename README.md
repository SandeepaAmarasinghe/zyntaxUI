# ZyntaxUI

> A Brutalist, Black & White Bootstrap 5 Override by **[Zyntax Studio](https://zyntax-studio.vercel.app/)**

![Version](https://img.shields.io/badge/version-2.0.0-black?style=flat-square)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-black?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-black?style=flat-square)

**Clean. Sharp. Brutal. | Drop in one CSS file. Ship a neo-brutalist UI.**

---

## 🖤 Overview

**ZyntaxUI** is a zero-config, stark, high-contrast CSS theme that overrides Bootstrap 5 defaults. Designed for developers who want a bold, black-and-white, neo-brutalist aesthetic — without touching a line of JavaScript or installing npm packages.

Created by Pasan Sandeepa at **[Zyntax Studio](https://zyntax-studio.vercel.app/)**.

| Resource | Link |
|---|---|
| 🌐 Live Demo | [zyntaxui.pages.dev](https://zyntaxui.pages.dev) |
| 📦 Raw CSS | [zyntaxui.pages.dev/zyntaxUI.css](https://zyntaxui.pages.dev/zyntaxUI.css) |
| 💻 GitHub | [SandeepaAmarasinghe/zyntaxUI](https://github.com/SandeepaAmarasinghe/zyntaxUI) |

---

## ✨ Features

- **High Contrast** — Pure blacks, pure whites, sharp 2px borders
- **Brutalist Shadows** — Stark flat offset box-shadows on cards and buttons
- **Bootstrap 5 Ready** — Drop-in override; works with any existing Bootstrap 5 project
- **CSS Custom Properties** — All design tokens exposed as CSS variables for easy customization
- **Zero Config** — No build step, no npm, no JavaScript required
- **Hover Micro-animations** — Subtle brutalist movement on interactive elements
- **Custom Scrollbar** — Styled to match the theme

---

## 🧱 Components

| Component | Class(es) |
|---|---|
| Buttons | `.btn`, `.btn-primary`, `.btn-sm`, `.btn-lg` |
| Cards | `.card`, `.card-header`, `.card-footer` |
| Alerts | `.alert`, `.alert-success`, `.alert-danger`, `.alert-warning`, `.alert-info` |
| Tables | `.table`, `.table-striped`, `.table-hover`, `.table-dark` |
| Badges | `.badge`, `.bg-*` |
| Forms | `.form-control`, `.form-select`, `.form-label`, `.form-check-input` |
| List Groups | `.list-group`, `.list-group-item` |
| Progress | `.progress`, `.progress-bar` |
| Accordion | `.accordion`, `.accordion-item`, `.accordion-button` |
| Modal | `.modal`, `.modal-header`, `.modal-footer` |
| Nav Tabs | `.nav-tabs`, `.nav-pills`, `.nav-link`, `.tab-pane` |
| Spinners | `.spinner-border`, `.spinner-grow` |
| Pagination | `.pagination`, `.page-link` |
| Dropdowns | `.dropdown`, `.dropdown-menu`, `.dropdown-item` |
| Breadcrumbs | `.breadcrumb`, `.breadcrumb-item` |

---

## 🚀 Installation

**1.** Add Bootstrap 5 and then zyntaxUI after it in your `<head>`:

```html
<!-- Bootstrap 5 CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- ZyntaxUI Override -->
<link href="https://zyntaxui.pages.dev/zyntaxUI.css" rel="stylesheet">
```

**2.** Add the Bootstrap JS bundle (required for modals, accordions, dropdowns) before `</body>`:

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

That's it. No build step. No npm. Just two tags.

---

## 🎨 Customization

Override any CSS variable in your own stylesheet after importing zyntaxUI:

```css
:root {
    --bg-color: #ffffff;
    --text-color: #000000;
    --border-color: #000000;
    --hover-bg: #f0f0f0;
    --muted-color: #555555;
    --shadow-md: 4px 4px 0px 0px var(--border-color);
}
```

---

## 📄 License

MIT © 2026 [Zyntax Studio](https://zyntax-studio.vercel.app/)