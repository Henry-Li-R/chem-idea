# chem-idea

## 🧠 Summary

This is a project idea for building a Mac-native, AI-enhanced alternative to ChemSketch (Windows-only). It's meant to solve the real issue of limited access for Mac users in chemistry education and research.

---

## 🎯 Goals

- Make a fast, modern, native drawing tool for molecular structures
- Enable basic 2D editing (atoms, bonds, angles, etc.)
- Export structures in common formats like SMILES and PNG
- Package the tool as a desktop app using Tauri (Rust+JS) or SwiftUI (Mac-native)

---

## 🔧 MVP Feature List

- [ ] Click-to-place atoms (C, H, O, N, etc.)
- [ ] Draw single, double, triple bonds
- [ ] Bond angle snapping (e.g. 120°, 109.5°)
- [ ] Export structure to SMILES using RDKit or Open Babel
- [ ] Save/load molecules (local JSON or IndexedDB)
- [ ] Highlight structural errors (e.g. invalid valency)

---

## 🧠 Future AI Add-ons (Stretch Goals)

- [ ] Generate IUPAC names from drawn structure (Transformer model fine-tuned on PubChem)
- [ ] Explain incorrect naming attempts with rule-based + NLP system
- [ ] Predict basic properties (e.g. molecular weight, logP)

---
