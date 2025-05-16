````markdown
# 🗓️ Availability Table

A responsive, color-coded availability table built with HTML and CSS. This project visualizes time-slot availability using custom CSS variables, gradients, and table layouts.

---

## ✅ Features

- 📅 Table with **days of the week** as columns and **time slots** as rows.
- 🎨 Custom color-coded cells using `--color#` CSS variables.
- 🧮 Availability levels shown with class names like `.available-0` to `.available-5`.
- 🔁 Alternating row styles (`.sharp` and `.half`) using solid and dashed borders.
- 🌈 A gradient legend representing availability from 0 to 5 people.

---

## 📐 User Stories Covered

- Table with **at least 3 columns** and **5 rows** (including headers).
- First **row** contains table headers (days).
- First **column** contains time headers with the `time` class.
- Each data cell uses `.available-#` class, where `#` = 0–5.
- CSS `:root` defines:
  - `--color0` through `--color5` for availability levels.
  - `--solid-border` and `--dashed-border` for row styling.
- Rows alternate between `.sharp` and `.half` classes.
- A `#legend` section with:
  - `span`: "Availability"
  - `#legend-gradient`: a linear gradient with **two hard color stops** for each color variable.

---

## 🧪 CSS Structure

```css
:root {
  --color0: #ffffff;
  --color1: #aaffaa;
  --color2: #55ddff;
  --color3: #ffff55;
  --color4: #ff9999;
  --color5: #7777ff;

  --solid-border: 2px solid black;
  --dashed-border: 2px dashed gray;
}
````

---
```
## 📂 Project Structure

``
availability-table/
├── index.html
├── styles.css
└── README.md
```

---
```

## 🧠 What I Learned

* Using CSS custom properties (`--var`) for dynamic styling.
* Creating hard-line gradients with precise color stops.
* Structuring semantic HTML tables for accessibility.
* Alternating row styles with class-based logic.

---

## 🛠️ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/availability-table.git
   ``
2. Open `index.html` in any browser.

---

## 📸 Preview

![availability table preview](screenshot.png)

---

## 🧾 License

This project is open-source and free to use under the [MIT License](LICENSE).

