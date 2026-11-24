# KITCHEN STUDIO — Photorealistic 3D Kitchen Cabinet Designer & BOQ

> **Interactive 3D / ISO / X-Ray / 2D Blueprint Kitchen Cabinet Designer with Real-Time BOQ & Multi-Sheet Excel Export**  
> **เว็บแอปพลิเคชันออกแบบชุดครัวบิ้วอิน 3 มิติสมจริง พร้อมแบบแปลน 2D และถอดราคา BOQ ส่งออก Excel อัตโนมัติ**

![Platform](https://img.shields.io/badge/Platform-PC%20%7C%20Tablet%20%7C%20Mobile-18181B?style=flat-square)
![Languages](https://img.shields.io/badge/Languages-English%20%7C%20%E0%B9%84%E0%B8%97%E0%B8%A2-4F6252?style=flat-square)
![Three.js](https://img.shields.io/badge/Three.js-r128%20PBR-000000?style=flat-square)
![Zero Backend](https://img.shields.io/badge/Deploy-Single%20HTML%20%7C%20GitHub%20Pages-059669?style=flat-square)

---

## ✨ Key Features / ฟีเจอร์หลัก

### 1. Bilingual & Multi-Currency (2 ภาษา & 2 สกุลเงิน)
- **EN / TH Toggle:** Instant switching across all UI panels, dimensions, material names, 2D blueprint annotations, BOQ tables, and Excel exports.
- **THB (`฿`) / USD (`$`) Toggle:** Real-time currency conversion across the entire BOQ and exported workbook.

### 2. Responsive Multi-Platform UI (รองรับทุกอุปกรณ์)
- Works smoothly on **PC, Tablet, and Mobile** browsers with touch-friendly 3D orbit, pinch-to-zoom, and collapsible accordion panels.
- **Full Screen Presentation Mode** with one-click toggle (`Esc` to exit) and **360° Turntable Auto-Rotate** for client presentations.

### 3. Parametric Layouts & Cabinet Engineering (ปรับรูปทรงและโครงสร้างตู้ได้ละเอียด)
- **3 Kitchen Layouts:** Straight (ครัวตรง), L-Shape (ครัวตัว L), and U-Shape (ครัวตัว U).
- **Independent Wing Controls:** Adjust main wall length, left/right wing lengths, and **independent wing height levels** (`75–110 cm`).
- **Smart Corner Collision Prevention:** Automatic `5 cm` L-corner safety fillers and mitered corner countertops for L-Shape and U-Shape layouts.
- **Cabinet Customization:**
  - Toggle **Wall Cabinets (Upper)** ON/OFF individually per wall or all at once.
  - Toggle **Backsplash** ON/OFF (synced across 3D, 2D, and BOQ).
  - Select **Cabinet Styles** for Base (`Mixed / Close Door / Drawer / Open Shelf`) and Upper (`Mixed / Close Door / Open Shelf`).
  - Adjust **Toe-Kick Height**, **Countertop Thickness**, and **Carcass Board Thickness** (`16 / 18 / 20 mm`).
  - **Open Doors / Drawers Inspection Mode** to inspect 18 mm carcass interiors, hinges, and 3D drawer boxes.

### 4. Photorealistic PBR Materials & Studio Lighting
- Procedural HTML5 Canvas **Diffuse + Bump PBR textures** for Wood Grain (Light Oak, Warm Walnut), Matte Laminates (Sage Green, Warm Taupe, Off-White, Charcoal, Navy), Glossy Stone/Marble (Pure Quartz, Calacatta Gold, Black Marquina, Concrete), Backsplash Tiles (Vertical Fluted, Subway, Terrazzo), Flooring, and Hardware Pulls / J-Groove.
- **Daylight & Warm Evening Lighting Moods** powered by baked PMREM studio environment maps and soft shadows.
- **3 Quick Style Presets:** *Sage & Oak Minimal*, *Warm Taupe & Marble*, and *Walnut & Charcoal Luxury*.

### 5. 4 Synchronized View Modes (4 มุมมองซิงก์อัตโนมัติ)
- **3D Perspective** with quick camera presets (`Hero 3D`, `Front`, `Corner`, `Top`, `Fit`).
- **ISO Axonometric** (Orthographic projection).
- **X-Ray Structural View** showing internal shelves, drawer boxes, corner fillers, and sink P-trap plumbing.
- **2D Architectural Blueprint** with Top Plan View (including optional Work Triangle overlay) and unified-scale **Front + Side Elevations** (`A / B / C`) for L-Shape and U-Shape.

### 6. Live BOQ & 3-Sheet Excel Export (คำนวณ BOQ และส่งออก Excel)
- Automatically calculates linear meters, backsplash area, hardware sets, and appliances.
- Edit quantities and unit prices inline, toggle items ON/OFF, add custom line items, and apply **Discount (%)** and **VAT (%)**.
- Exports a ready-to-send `.xlsx` workbook with **3 sheets**:
  1. `BOQ` (with live Excel formulas for line totals, subtotal, discount, VAT, and grand total)
  2. `Dimensions` (full layout parameters & enabled modules)
  3. `Materials` (selected finishes & estimated coverage)

---

## 🚀 Quick Start / วิธีใช้งาน

No build step or server required — runs 100% client-side in any modern browser.

1. Download or clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `index.html` directly in Chrome, Edge, Safari, or Firefox.

---

## 🌐 Deploy on GitHub Pages

1. Push `index.html` and `README.md` to your GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, select `main` and `/ (root)`, then click **Save**.
4. Your live app will be available at `https://<your-username>.github.io/<your-repo-name>/`.

---

## 🛠️ Tech Stack

- **3D Engine:** [Three.js r128](https://threejs.org/) (`WebGLRenderer`, `PMREMGenerator`, `OrbitControls`, `MeshPhysicalMaterial`)
- **UI & Styling:** [Tailwind CSS CDN](https://tailwindcss.com/) + Inter & Noto Sans Thai fonts
- **2D Blueprint:** Native HTML5 Canvas 2D API
- **Excel Export:** [SheetJS (`xlsx`)](https://sheetjs.com/)

---

## 📄 License

MIT License — feel free to use, customize, and deploy for personal or commercial kitchen design workflows.