<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:64748B,50:475569,100:334155&height=220&section=header&text=Material%20Weight%20Calculator&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Industrial%20Material%20Weight%20Estimation%20Tool%20%E2%9A%96%EF%B8%8F&descAlignY=58&descAlign=50" width="100%"/>

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-material--weight--calculator.vercel.app-6366F1?style=for-the-badge)](https://material-weight-calculator.vercel.app)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=94A3B8&center=true&vCenter=true&width=650&lines=Calculate+material+weight+instantly+%E2%9A%96%EF%B8%8F;Select+thickness%2C+height+%26+length+%F0%9F%93%90;Add+multiple+items+%26+get+grand+total+%F0%9F%93%A6;Zero+dependencies+%E2%80%94+pure+HTML%2FCSS%2FJS+%E2%9C%A8;Works+offline%2C+no+backend+needed+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<br/>

<blockquote>
A lightweight, zero-dependency web tool for engineers and manufacturers to calculate the total weight of materials based on thickness, height, length, and quantity. Add multiple entries and get a precise grand total instantly.
</blockquote>

<br/>

</div>

---

## 🌟 Features

<table>
  <tr>
    <td align="center" width="220">⚖️<br/><strong>Weight Calculation</strong><br/><sub>Compute material weight from thickness, height, length & quantity</sub></td>
    <td align="center" width="220">📦<br/><strong>Multi-Item Tracking</strong><br/><sub>Add multiple material entries and track them in a live table</sub></td>
    <td align="center" width="220">🔢<br/><strong>Grand Total</strong><br/><sub>Running grand total weight updated in real time as items are added</sub></td>
  </tr>
  <tr>
    <td align="center" width="220">📐<br/><strong>Preset Dimensions</strong><br/><sub>Dropdown selects for standard thickness (0.8–1.5 mm) and height values</sub></td>
    <td align="center" width="220">🗑️<br/><strong>Item Management</strong><br/><sub>Remove individual entries or reset all items at once</sub></td>
    <td align="center" width="220">⚡<br/><strong>Zero Dependencies</strong><br/><sub>Pure HTML, CSS & JS — no frameworks, no installs, works offline</sub></td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Role |
|-----------|------|
| **HTML5** | Structure & form elements |
| **CSS3** | Styling & responsive layout |
| **Vanilla JavaScript** | Calculation logic & DOM manipulation |
| **Vercel** | Deployment & hosting |

</div>

> **Single-file architecture** — the entire app lives in one `index.html` file. No build step, no dependencies, no backend.

---

## 📐 How It Works

1. **Select thickness** from preset dropdown (0.8 mm – 1.5 mm)
2. **Select height** from standard values (1.5", 2", 10")
3. **Enter length** in feet and **quantity** in pieces
4. Click **＋ Add Item** — the entry is added to the table with calculated weight
5. Repeat for multiple materials
6. View the **Grand Total Weight** at the bottom

### Weight Formula

```
Weight (kg) = Thickness (mm) × Height (inch × 25.4) × Length (feet × 304.8) × Quantity × Density
```

---

## 🚀 Getting Started

Since this is a single HTML file, there's nothing to install:

```bash
# Clone the repo
git clone https://github.com/Tanyaagarg/material-weight-calculator.git
cd material-weight-calculator

# Open directly in browser
open index.html
```

Or just visit the **[live demo](https://material-weight-calculator.vercel.app)** — no setup needed.

---

## 📦 Deployment

Deployed on **Vercel** as a static site. To deploy your own:

```bash
npm install -g vercel
vercel --prod
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-material-type`
3. Commit your changes: `git commit -m 'Add new material type'`
4. Push: `git push origin feature/new-material-type`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:64748B,50:475569,100:334155&height=120&section=footer" width="100%"/>

<sub>Built with ⚙️ pure HTML · CSS · JavaScript</sub>

</div>
