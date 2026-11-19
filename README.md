# MacBook Laptop Showcase Website

A comprehensive, responsive, high-performance website dedicated to Apple MacBook laptops (MacBook Air, MacBook Pro, and Apple Silicon architecture), built with pixel-perfect adherence to the **cla-master** theme, color scheme, and typography.

---

## 🎨 Theme & Design System

The website maintains 100% fidelity to the original CLA design system:

| Element | Specification | Description |
| :--- | :--- | :--- |
| **Primary Accent Color** | `#48ca95` | Mint green used on buttons, badges, hover effects, indicators, and active borders |
| **Secondary Accent / Indigo** | `#4f4aa6` / `#3b3687` | Deep purple-blue used for section headers, comparison tables, and highlight banners |
| **Dark Accents** | `#121010` / `#252525` | Deep charcoal used on product card headings and dark backgrounds |
| **Neutral Backgrounds** | `#ffffff` / `#f7f7f7` | Alternating clean white and soft light-gray sections |
| **Body Font** | `'Poppins', sans-serif` | Clean, modern sans-serif for body copy, lists, and form controls |
| **Heading Font** | `'Rajdhani', sans-serif` | Bold, technical geometric typography for titles and branding |
| **Promotional Font** | `'Dosis', sans-serif` | Distinctive rounded typography for the promotional spotlight banner |

---

## 💻 Project Structure (VS Code Ready)

```text
cla-master/
├── index.html            # Main flagship portal (Carousel, Air, Pro, Silicon, Comparison, Reviews, Contact)
├── laptop.html           # Dedicated MacBook Air showcase (13-inch & 15-inch M3, silent fanless design)
├── computer.html         # Dedicated MacBook Pro showcase (14-inch & 16-inch M4 Pro/Max, Liquid Retina XDR)
├── about.html            # Apple Silicon Architecture deep dive & 20-year milestone timeline
├── product.html          # Complete MacBook catalog with interactive category filters
├── contact.html          # Apple certified specialist consultation & custom CTO inquiry form
│
├── css/
│   ├── bootstrap.min.css # Bootstrap 4.x grid and components
│   ├── style.css         # Core CLA theme stylesheet
│   ├── macbook.css       # MacBook UI enhancements (spec tags, comparison tables, filters, modals)
│   ├── responsive.css    # Responsive mobile/tablet media queries
│   └── ...               # Additional helper and scrollbar styles
│
├── js/
│   ├── jquery.min.js     # jQuery library
│   ├── popper.min.js     # Popper.js tooltip & popover positioning
│   ├── bootstrap.bundle.min.js # Bootstrap carousel and modal logic
│   ├── custom.js         # CLA core scripts & preloader
│   └── macbook.js        # Interactive filter, smooth scroll, specs modal, and form submission
│
└── images/
    ├── macbook_pro_16.jpg      # High-definition MacBook Pro 16" Liquid Retina XDR
    ├── macbook_pro_14.jpg      # High-definition MacBook Pro 14" Space Black
    ├── macbook_air_13.jpg      # High-definition MacBook Air 13" Midnight
    ├── macbook_air_15.jpg      # High-definition MacBook Air 15" Starlight
    ├── apple_silicon_chip.jpg  # High-definition Apple Silicon 3nm SOC die
    ├── liquid_retina.jpg       # High-definition Mini-LED ProMotion display closeup
    ├── magic_keyboard.jpg      # High-definition Magic Keyboard with Touch ID
    ├── macbook_accessories.jpg # High-definition MagSafe 3 & Thunderbolt 5 ports
    ├── macbook_colors.jpg      # High-definition MacBook finishes lineup
    ├── macbook_desk.jpg        # High-definition developer desk setup
    ├── reviewer_marques.jpg    # Tech critic portrait (MKBHD)
    ├── reviewer_sarah.jpg      # Tech architect portrait (Sarah Zhang)
    ├── reviewer_alex.jpg       # Product designer portrait (Alex Miller)
    └── ...                     # Original CLA icons, backgrounds, and loader
```

---

## 🚀 How to Run in Visual Studio Code

1. **Open Folder in VS Code**:
   - Open Visual Studio Code.
   - Click `File` > `Open Folder...` (or press `Ctrl + K, Ctrl + O`).
   - Select `C:\Users\user\OneDrive\Pictures\Screenshots\FINAL CODING\cla-master`.

2. **Launch with Live Server (Recommended)**:
   - Install the **Live Server** extension by *Ritwick Dey* (Extension ID: `ritwickdey.LiveServer`).
   - Right-click `index.html` in the file explorer.
   - Click **"Open with Live Server"** (or press `Alt + L, Alt + O`).
   - The website will automatically launch in your default web browser at `http://127.0.0.1:5500/index.html` with hot-reloading enabled.

3. **Launch Directly in Browser**:
   - Double-click `index.html` in Windows Explorer, or drag-and-drop `index.html` into Google Chrome, Microsoft Edge, or Firefox.

---

## ✨ Features Included

- **HD Image Asset Suite**: All high-definition MacBook photographs are stored locally inside `images/` so the site runs completely offline without broken links.
- **5-Slide Hero Carousel**: Interactive Bootstrap carousel showcasing MacBook Pro, MacBook Air, Apple Silicon, Liquid Retina XDR, and Magic Keyboard.
- **Product Category Filter**: Dynamic jQuery filtering by All Models, MacBook Air, MacBook Pro, and Silicon & Hardware.
- **Quick Specs Modal**: Clicking "View Full Specs" on any product card opens a populated modal dialog with exact chip, RAM, display, and port data.
- **Comprehensive Comparison Matrix**: Side-by-side technical breakdown across Air 13", Air 15", Pro 14", and Pro 16".
- **Customer & Tech Critic Reviews**: Smooth carousel featuring reviews from top industry authorities.
- **Interactive Contact & Consultation Form**: Includes model selector dropdown, validation, and real-time submission confirmation.
