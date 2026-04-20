# 🧬 Melanin Project: The Bio-DevOps Compiler

**Authors:** Joao & Ana  
**Environment:** Web / React / GSAP  
**Status:** Build Successful (Functional Protein)

## 📋 Project Overview
This interactive educational tool visualizes the **Central Dogma of Molecular Biology**. It treats the human body as a hardware system and the genetic code as the software. By simulating the flow from DNA to Protein, we demonstrate how the **MC1R gene** renders physical traits like skin and hair color.

---

## 🛠 Tech Stack
- **Frontend Framework:** React 18 (Production Build)
- **Styling:** Tailwind CSS (Antialiased Dark Mode)
- **Animation Engine:** GSAP (GreenSock) for high-performance sequence mapping
- **Smooth Scrolling:** Lenis Scroll for refined UI experience

---

## 🔬 System Architecture (The Central Dogma)

The application models the biological process as a deployment pipeline:

### 1. Transcription (Source Copy)
The `RNA Polymerase` tool scans the DNA "Master Branch." It generates an `mRNA` "Deploy Build" by matching complementary bases (A→U, T→A, C→G, G→C). This ensures the original source code remains safe in the Nucleus "Server."

### 2. Splicing (Build Optimization)
Before execution, the code undergoes splicing. **Introns** (non-coding segments) are removed, and **Exons** (coding segments) are linked to create a finalized instruction set.

### 3. Translation (Compilation)
The `Ribosome` (System Compiler) reads the mRNA in 3-bit **Codons**. `tRNA` (Delivery Drones) fetch the specific **Amino Acids** (Raw Materials) required to build the `MC1R Protein` (Compiled Hardware).

---

## 🐛 Bug Report (Mutation Simulation)
The "Lab" allows for real-time testing of genetic mutations to observe "Runtime Errors" in the physical UI:

| Mutation | Effect | Resulting UI Render |
| :--- | :--- | :--- |
| **R151C (Missense)** | Source Code Typo | Incomplete melanin density; "Red Hair/Fair Skin" UI. |
| **Early STOP (Nonsense)** | Unexpected EOF | Truncated build; 10% yield; non-functional protein. |
| **Index Shift (Frameshift)** | Index Out of Bounds | Scrambled logic; protein translates to gibberish. |
| **RM -RF (Deletion)** | No Source Found | Fatal crash; Albinism/Safe Mode UI. |

---

## 🚀 How to Run the Project
Since this project uses a "No-Build" CDN approach for school portability, you can run it directly in any modern browser:

1. Save the code as `index.html`.
2. Open `index.html` in Chrome, Edge, or Safari.
3. Use the **Build Protein** button to initialize the animation sequence.
4. Toggle **Mutations** in the diagnostic panel to debug different genetic outcomes.

---

## 📂 Glossary
- **Base:** The 4 raw bit inputs (A, T, C, G) composing your source code.
- **Gene:** A specific directory of instructions for a trait.
- **Codon:** A 3-base sequence that acts as a key for an Amino Acid.
- **Protein:** The final physical output that performs biological functions.
