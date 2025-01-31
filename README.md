# Quasar CSS Cheat Sheet

This cheat sheet provides a quick reference to Quasar's CSS utility classes, including breakpoints, spacing, typography, display, positioning, and more.

## 🚀 Getting Started

Quasar provides built-in CSS classes that help with responsive design, layout management, and styling.

---

## 📌 Table of Contents
- [Typography](#typography)
- [Font Size & Font Weight](#font-size--font-weight)
- [Text Alignment](#text-alignment)
- [Colors](#colors)
- [Flex & Grid](#flex--grid)
- [Spacing (Margin & Padding)](#spacing-margin--padding)
- [Sizing (Width & Height)](#sizing-width--height)
- [Custom Sizing (Width & Height)](#custom-sizing-width--height)
- [Positioning (Top, Left, Right, Bottom)](#positioning-top-left-right-bottom)
- [Z-Index](#z-index)
- [Opacity](#opacity)
- [Cursor Styles](#cursor-styles)
- [Visibility](#visibility)
- [Overflow Control](#overflow-control)
- [Display](#display)
- [Borders & Shadows](#borders--shadows)
- [Breakpoints (Responsive Design)](#breakpoints-responsive-design)
- [Animations & Transitions](#animations--transitions)
- [Usage Examples](#usage-examples)

---

## 📝 Typography

| Class | Description |
|-------|------------|
| `.text-h1` to `.text-h6` | Header styles (H1-H6) |
| `.text-subtitle1`, `.text-subtitle2` | Subtitle text styles |
| `.text-body1`, `.text-body2` | Body text styles |
| `.text-caption`, `.text-overline` | Smaller text styles |
| `.text-italic`, `.text-bold`, `.text-uppercase` | Text formatting |

---

## 🔠 Font Size & Font Weight

### **Font Size**
| Class | Description |
|-------|------------|
| `.text-xs` | Extra small font size |
| `.text-sm` | Small font size |
| `.text-md` | Medium (default) font size |
| `.text-lg` | Large font size |
| `.text-xl` | Extra large font size |

### **Font Weight**
| Class | Description |
|-------|------------|
| `.text-weight-thin` | Thin font weight (100) |
| `.text-weight-light` | Light font weight (300) |
| `.text-weight-regular` | Regular font weight (400) |
| `.text-weight-medium` | Medium font weight (500) |
| `.text-weight-bold` | Bold font weight (700) |
| `.text-weight-bolder` | Extra bold font weight (900) |

---

## 📐 Custom Sizing (Width & Height)

### **Custom Width**
```html
<div style="width: 300px;">Custom width 300px</div>
<div style="width: 50%;">Custom width 50%</div>
```

### **Custom Height**
```html
<div style="height: 200px;">Custom height 200px</div>
<div style="height: 75vh;">Custom height 75% of viewport height</div>
```

---

## 📍 Positioning (Top, Left, Right, Bottom)

| Class | Description |
|-------|------------|
| `.absolute-{position}` | Absolute positioning (`top`, `right`, `bottom`, `left`) |
| `.fixed-{position}` | Fixed positioning (`top`, `right`, `bottom`, `left`) |
| `.relative` | Relative positioning |
| `.top-{size}` | Moves element down (`size`: `xs`, `sm`, `md`, `lg`, `xl`) |
| `.bottom-{size}` | Moves element up (`size`: `xs`, `sm`, `md`, `lg`, `xl`) |
| `.left-{size}` | Moves element to the right (`size`: `xs`, `sm`, `md`, `lg`, `xl`) |
| `.right-{size}` | Moves element to the left (`size`: `xs`, `sm`, `md`, `lg`, `xl`) |

---

## 📱 Breakpoints (Responsive Design)

Quasar follows Material Design breakpoints for responsive design.

### **Breakpoint Ranges**
| Breakpoint | Min Width | Max Width | Devices |
|-----------|----------|----------|---------|
| `xs` (Extra Small) | 0px | 599px | Mobile |
| `sm` (Small) | 600px | 1023px | Tablets, Small Laptops |
| `md` (Medium) | 1024px | 1439px | Laptops, Desktops |
| `lg` (Large) | 1440px | 1919px | Large Screens |
| `xl` (Extra Large) | 1920px | ∞ | Ultra-wide Screens |

---

## 📜 License

This cheat sheet is free to use under the **MIT License**.

---

## 🔗 Resources

- [Quasar Official Documentation](https://quasar.dev)
- [Material Design Guidelines](https://material.io/)

