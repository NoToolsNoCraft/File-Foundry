# 🌳➡️💾 File Foundry

**File Foundry** is a lightweight, browser-based tool that lets you instantly generate downloadable ZIP archives with custom folder and file structures.  
No backend, no installs, no setup — everything runs **100% client-side** in your browser.

Live link: https://notoolsnocraft.github.io/File-Foundry/
---

## ✨ Features

- **Instant ZIP Generation**  
  Build and download file structures instantly, with no servers involved.

- **Two Input Formats**  
  Choose between:
  - **Tree Format**: ASCII-style hierarchy (`├─`, `│`, `└─`)  
  - **Simple Format**: One path per line

- **Ready-to-Use Files**  
  All files are empty placeholders, ready for your content.

- **Works Everywhere**  
  Runs in any modern browser, on any OS, with no installation required.

---

## 🚀 How It Works

1. Enter your desired folder and file structure into the input box:
   - **Tree Format Example**  
     ```
     project/
     ├─ package.json
     ├─ tsconfig.json
     ├─ public/
     │  └─ index.html
     └─ src/
        ├─ index.tsx
        └─ components/
           ├─ Counter.tsx
           └─ ItemList.tsx
     ```
   - **Simple Format Example**  
     ```
     project/
     project/package.json
     project/tsconfig.json
     project/public/
     project/public/index.html
     project/src/
     project/src/index.tsx
     project/src/components/Counter.tsx
     project/src/components/ItemList.tsx
     ```

2. Click **Generate & Download .zip**.

3. Instantly download a `.zip` file with your folder structure.  
   All files are created empty, and folders are preserved.

---

## 💡 Benefits

- **Save time** when prototyping project layouts or scaffolding starter kits.  
- **Share templates** quickly with teammates or students.  
- **No dependencies** — it works in any browser without installing anything.  
- **Portable** — just open the app and start generating.  

---

## 🛠 Tech Stack

- [Tailwind CSS](https://tailwindcss.com/) for styling  
- [JSZip](https://stuk.github.io/jszip/) for ZIP file generation  
- Vanilla JavaScript (no build tools required)


