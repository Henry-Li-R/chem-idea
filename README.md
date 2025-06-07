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

- [ ] **Generate IUPAC names** from SMILES using RDKit or other cheminformatics tools
- [ ] **Provide feedback on incorrect names** with rule-based comparison (e.g., incorrect locant, wrong root chain)
- [ ] **Predict basic properties** like molecular weight, logP, H-bond donors/acceptors using RDKit
- [ ] **Visualize 3D structures** from SMILES using 3Dmol.js
- [ ] Optional AI extensions if useful or educational (e.g., structure → name generation via ML)

---

## 🛑 Status

Development paused. Idea is saved for future reference. May revisit after completing current AI and full-stack studies.
