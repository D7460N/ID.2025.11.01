# International Dance Inc.

**International Dance Inc.** is built with the **D7460N Architecture** - a browser-native, fully declarative architecture for building scalable, maintainable, and future-proof front-end systems. This implementation operates as a Single Page Application (SPA) and is designed as a Progressive Web App (PWA).

OUT OF THE BOX:

> - lightweight
> - browser-native
> - dependency-free
> - standards-first
> - fully declarative
> - fully 508 accessible
> - fully responsive

This website eliminates runtime dependencies and avoids complex JavaScript-driven UI logic by embracing **modern standards**: semantic HTML, CSS state management, and data-only JavaScript modules.

> - Native HTML, CSS, JS (ES Modules)
> - No build tools, no transpilers, no frameworks
> - Responsive, accessible, and declarative _**by design**_

<br>

## ✨ HIGHLIGHTS

🔹 **CSS-First Architecture**: Advanced state management using hidden checkboxes + CSS `:checked`, `:has()` selectors<br>
🔹 **Performance Optimized**: CSS rendering 100-1000x faster than JavaScript DOM manipulation equivalents<br>
🔹 **Security Hardened**: Minimal JavaScript surface reduces XSS attack vectors<br>
🔹 **Progressive Enhancement**: Fully functional with JavaScript disabled<br>
🔹 **Accessibility Native**: Uses semantic HTML + ARIA for 508/WCAG compliance<br>
🔹 No dependencies: 100% browser-native<br>
🔹 Dynamic JSON data via `fetch()`<br>
🔹 Declarative single-page-application (SPA) navigation via `<input type="radio">` + CSS `:has()` + container queries<br>
🔹 **Easily Overridden**: Minimal nesting, no IDs, classes, or custom attributes in markup, CSS Layers<br>
🔹 Component visibility logic (`:empty`, `:has`, `[hidden]`) based on data delivery **JavaScript CRUD**.<br>
🔹 Clean separation of concerns: UI boolean logic, and JavaScript/API services.

**⚠️ Architecture Note**:<br>
This project uses an intentionally sophisticated<br>
> - CSS-first pattern with `<label role="button"><input type="checkbox"></label>` for state management. _This is NOT a mistake_ - **it's an advanced optimization technique**. See [D7460N Architecture Documentation](https://github.com/D7460N/DHCP/blob/main/docs/README.md) for complete architectural analysis.

<br>

## 🚀 TO RUN

1. Download and extract the project.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari).

DONE!

- No build step<br>
- No compilation<br>
- No problem

<br>

## 📂 STRUCTURE

| Directory       | Purpose                                       |
| --------------- | --------------------------------------------- |
| `/assets/css/`  | CSS layers for layout, typography, heuristics |
| `index.html`    | Main application entry point                  |

<br>

## 🛠️ DEVELOPER TIPS

> - Clear cache with `Ctrl+Shift+R` to avoid stale module loads
> - Ensure the website is served over HTTP/HTTPS for optimal PWA functionality

<br>

## 📚 DOCUMENTATION

For detailed information about the D7460N Architecture:
- [D7460N Architecture Documentation](https://github.com/D7460N/DHCP/blob/main/docs/README.md)
- [Architecture Decision Document (ADD)](https://github.com/D7460N/DHCP/blob/main/ADD.md)
- [Agent Guidelines](https://github.com/D7460N/DHCP/blob/main/AGENT.md)

<br>

## 🙋 NEED HELP?

Open an issue in this repository or refer to the D7460N Architecture documentation for guidance.
