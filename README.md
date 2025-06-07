# chem-idea

## 🧠 Summary

This is a project idea for building a Mac-native alternative to ChemSketch (currently Windows-only). It aims to solve the real issue of limited access for Mac users in chemistry education and research, while improving usability and modernizing the interface.

---

## 🎯 Goals

- Build a fast, modern molecular structure editor for macOS
- Enable intuitive 2D editing of atoms, bonds, and angles
- Export structures in common formats like SMILES and PNG
- Package the tool as a native macOS desktop app using Tauri (Rust + JS) or SwiftUI

---

## 🔧 MVP Feature List

- [ ] Click-to-place atoms (C, H, O, N, etc.)
- [ ] Draw single, double, and triple bonds
- [ ] Bond angle snapping (e.g., 120°, 109.5°)
- [ ] Represent molecule as an internal data model (atoms, bonds, coordinates)
- [ ] Export structure to SMILES using RDKit or Open Babel
- [ ] Save/load molecules (local JSON or IndexedDB)
- [ ] Validate bonding and valency rules (e.g., carbon can't exceed 4 bonds)

---

## 🔮 Planned Enhancements

- [ ] Generate IUPAC names from SMILES using RDKit or other cheminformatics tools
- [ ] Provide feedback on incorrect names with rule-based comparison (e.g., incorrect locant, wrong root chain)
- [ ] Predict basic properties like molecular weight, logP, H-bond donors/acceptors using RDKit
- [ ] Visualize 3D structures from SMILES using 3Dmol.js
- [ ] Optional AI extensions if useful or educational (e.g., structure → name generation via ML)

---

## 💡 Opportunity Gap

While tools like ChemDoodle, MarvinSketch, Avogadro, and Ketcher exist, they have limitations worth noting:

- **ChemDoodle** is a polished, feature-rich option, but it is paid software (~$60 for Mac), which may limit accessibility for students and individual users without institutional licenses.
- **MarvinSketch**, although free for academic use, is based on a Java UI. Users have reported that it lacks modern UI responsiveness and loses editability when structures are pasted into external programs like Word.
- **Avogadro** is excellent for 3D modeling and molecular simulations, but it does not prioritize clear, clean 2D structure drawing for publication or teaching.
- **Ketcher** is a capable web-based open-source tool, but it lacks an offline native desktop experience. Its UI, while functional, is not optimized for native feel or high-quality visual output.

These limitations create space for a new tool:
- A **free, Mac-native, open-source** molecule editor focused on **clean 2D drawing**, **usability**, and **light educational feedback**.
- Built specifically for **students**, **educators**, and **researchers** who need a lightweight, installable, responsive tool — without the constraints of web-only interfaces or costly licenses.

---

## 🛑 Status

Development paused. Idea is saved for future reference. May revisit after completing current AI and full-stack studies.
