# ⚽ FM Planner — Football Manager Squad & Tactic Builder

<div align="center">
  <img src="resources/app.asar.unpacked/public/logo.png" alt="FM Planner Logo" width="128" style="border-radius: 24px; box-shadow: 0 10px 30px rgba(0, 230, 118, 0.3); margin-bottom: 20px;"/>
  
  <h3>Premium Desktop Assistant for Football Manager Tactical Planning & Squad Management</h3>

  <p>
    <a href="https://electronjs.org/"><img src="https://img.shields.io/badge/Electron-4730EB?style=for-the-badge&logo=electron&logoColor=white" alt="Electron"/></a>
    <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/></a>
    <a href="https://sqlite.org/"><img src="https://img.shields.io/badge/SQLite3-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite3"/></a>
    <a href="https://github.com/naptha/tesseract.js"><img src="https://img.shields.io/badge/Tesseract_OCR-563D7C?style=for-the-badge&logo=tesseract&logoColor=white" alt="Tesseract OCR"/></a>
    <br/>
    <a href="https://www.fmrte.com/"><img src="https://img.shields.io/badge/FMRTE-Companion-2e7d32?style=for-the-badge&logo=sports&logoColor=white" alt="FMRTE"/></a>
    <a href="https://www.fmscout.com/"><img src="https://img.shields.io/badge/FM_Genie_Scout-Companion-0277bd?style=for-the-badge&logo=scout&logoColor=white" alt="FM Genie Scout"/></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="License"/></a>
  </p>
</div>

---

## 📖 About the Application

**FM Planner** is a premium, custom-designed desktop utility built specifically for tracking positional scoring weights and tactical planning in **Football Manager (FM)**. 

Designed as a companion app, it integrates seamlessly with external tools such as **FMRTE (Football Manager Real Time Editor)** and **FM Genie Scout**. These tools generate player positional suitability values (*Scoring*), which FM Planner consolidates into an intuitive, visually stunning dashboard to serve as your ultimate tactical planning hub.

---

## 🖼️ Application Screenshots

<div align="center">
  <table style="width: 100%; max-width: 1000px; border-collapse: collapse; border: none;">
    <tr style="border: none;">
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/183072fc-9c04-4de1-8c66-d470c94d6506" alt="Dashboard Tactic Pitch" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Tactical Pitch & Squad Depth</b></p>
      </td>
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/ea61c25e-a925-46aa-8b40-f03575a190b3" alt="Academy Management" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Academy & Youth Development</b></p>
      </td>
    </tr>
    <tr style="border: none;">
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/73b43187-6e6d-4c9c-9d45-818085e8b131" alt="Shortlist & Targets" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Transfer Shortlist & Target Board</b></p>
      </td>
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/1038c5a6-56a8-4b0d-9f49-20e9208e2f21" alt="Sales Planner" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Financial & Sales Planner</b></p>
      </td>
    </tr>
    <tr style="border: none;">
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/f9c0e6d5-d293-45dd-bbf4-323a4d451e36" alt="Trophy Shelf" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Trophy Shelf</b></p>
      </td>
      <td style="width: 50%; padding: 8px; border: none;">
        <img src="https://github.com/user-attachments/assets/7317a87f-111e-418b-a8af-51871cd53f7f" alt="Light Mode Interface" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.3);"/>
        <p align="center"><b>Elegant Light Mode Option</b></p>
      </td>
    </tr>
  </table>
</div>

---

## ⚡ Key Features & Pages

Each view is styled using a modern **Vibrant Slate Premium** design system, packed with interactive mechanics, micro-animations, and instant responses:

### 1. 📋 Tactical Pitch & Squad Depth
* **3D-Style Interactive Pitch**: Drag-and-drop players into tactical slots directly on a beautifully styled pitch with neon glow borders.
* **Undo & Redo System**: Easily undo or redo tactical experiments using standard controls.
* **Average Rating & Performance Monitor**: Calculates starting squad ratings automatically, complete with subtle danger warnings if quality dips.
* **Responsive Light/Dark Mode**: Switch between dark slate aesthetics and high-contrast light mode with a single toggle.

### 2. 🎓 Academy & Youth Development
* **Wonderkid Monitor**: Keep track of current capabilities vs. ceiling potential.
* **Dynamic Squad Segregation**: Automatic splits for Under-21 and Under-18 cohorts.
* **Smart Country Search**: Typo-tolerant nationality selector featuring dynamic flag rendering.

### 3. 🎯 Shortlist & Targets
* **Transfer Board**: Monitor target players, showing visual progress bars of their ratings.
* **Quick-Sign Action**: Promote or sign players from the shortlist directly into your main team database.

### 4. 💰 Sales & Budget Planner
* **Revenue Projector**: Estimate and tally incoming funds from proposed sales/loans to maintain healthy transfer kitties.

### 5. 🏆 Trophy Cabinet
* **Club History**: Commemorate your tournament victories, cup finals, and runner-up statuses.

---

## 🧠 Under-the-Hood Optimizations

* **Duplicate Protection**: Name parsing logic handles diacritics (e.g., standardizing *Ertuğrul* to *Ertugrul*), avoiding duplicates and throwing beautiful toast notifications.
* **Accessible Shortcuts**: Modal standard saving on `Enter`, dropdown navigation with arrow keys, and keyboard-friendly selections.
* **Optimized Light Mode**: Specialized high-contrast slate tables, borders, and input sheets for perfect legibility in any environment.

---

## 📷 AI OCR Screenshot Import (FMRTE)

Quickly populate player stats from FMRTE without manual typing.

```mermaid
graph TD
    A[Open FMRTE Profile] --> B[Go to Scout Info > Positional Rating]
    B --> C[Set Zoom to 100%]
    C --> D[Capture via Win+Shift+S]
    D --> E[Click 'PASTE FMRTE SCREENSHOT' in Modal]
    E --> F[Press Ctrl+V to Import]
    F --> G[Confirm parsed stats]
    G --> H[Done!]
```

> [!TIP]
> Keep the FMRTE page zoom at 100% and crop only the positional rating table for the cleanest text recognition.

---

## ⚙️ How to Run & Package

### Quick Start (Running the App)
To launch the application, simply double click **`FM Planner.exe`** in the root directory. 
The application loads and runs directly from **`resources/app.asar`**.

### For Developers

#### Repository Structure
- **`app_source/`**: Contains the complete editable source code of the application.
- **`resources/app.asar`**: The packaged application archive used at runtime.

#### Prerequisites
* **Node.js** (v16+)

#### Modifying & Packaging
1. Make your code modifications inside the `app_source/` directory.
2. In the root directory, install dependencies:
   ```bash
   npm install
   ```
3. Build the packaged `app.asar` archive:
   ```bash
   npm run build-asar
   ```
4. Run the updated application:
   ```bash
   npm start
   ```

---

*Built with passion for managers who love the numbers behind the beautiful game.* ⚽
