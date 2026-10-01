# MTH 240: Transition to Abstract Mathematics

Selected LaTeX and mathematical writing coursework completed for MTH 240 (Transition to Abstract Mathematics) at Muhlenberg College (Spring 2025).

This repository contains my personal work from the course, focusing on formal mathematical logic, structured proof techniques, mathematical exposition, and LaTeX typesetting.

## Highlights

### [Proof Portfolio](proof-portfolio/)
The semester capstone project compiling 15 revised proofs across direct and indirect proof, quantifiers, mathematical induction, complete induction, set theory, equivalence relations, modular arithmetic, and the Alden handshake problem. Includes personal reflection essays on learning mathematical proof and LaTeX.

- **Typesetting features**: Multi-section structure, Roman-numeral frontmatter, automated table of contents (`tocloft`), running headers/footers (`fancyhdr`), and embedded figures.
- **Preview**:

<p align="center">
  <img src="assets/previews/proof-induction.png" width="45%" alt="Proof Portfolio Induction Page">
  <img src="assets/previews/proof-portfolio-title.png" width="45%" alt="Proof Portfolio Title Page">
</p>

### [The Alden Handshake Problem](alden-handshake-problem/)
A mathematical essay explaining the solution to the classic party handshake puzzle using base cases ($n=1, 2$) and mathematical induction. Written in an accessible narrative style for general audiences.

- **Typesetting features**: Double-spaced article format, custom geometry, and an integrated handshake distribution diagram.
- **Preview**:

<p align="center">
  <img src="assets/previews/alden-handshake-essay.png" width="45%" alt="Alden Handshake Essay Preview">
  <img src="assets/previews/alden-handshake-model.png" width="45%" alt="Alden Handshake Model Preview">
</p>

### [Selected Problem Sets](problem-sets/)
Curated weekly homework problem sets in LaTeX demonstrating proof techniques on advanced topics:
- **[Assignment 08](problem-sets/assignment-08-induction-and-relations/)**: Complete induction ($3s+4t$ and $4s+5t$), second-order linear recurrence relations ($a_{n+2} = 5a_{n+1} - 6a_n$), Fibonacci sequence powers ($g_n = 2^{f_n}$), and relation composition domains.
- **[Assignment 11](problem-sets/assignment-11-functions-and-modular-arithmetic/)**: Function restrictions, Cartesian product mappings, and surjectivity/injectivity in modular arithmetic ($\mathbb{Z}_4 \to \mathbb{Z}_2$).
- **[Assignment 12](problem-sets/assignment-12-bijections-and-permutations/)**: Bijectivity proof for a rational function and cycle notation in the symmetric group $S_7$.

## Skills Demonstrated

- **LaTeX & Document Layout**: Article class customization, page margins (`geometry`), running headers and footers (`fancyhdr`), table of contents customization (`tocloft`), and figure captioning (`caption`).
- **Mathematical Typesetting**: Aligned equations, quantifiers ($\forall, \exists$), set-builder notation, modular arithmetic equivalence classes, and piecewise definitions.
- **Mathematical Proof Techniques**: Direct proof, proof by contradiction, mathematical induction (PMI), complete induction (PCI), second-order linear recurrences, and bijection proofs.
- **Technical & Expository Writing**: Translating graph-theoretic and combinatorial parity arguments into clear prose for general readers.

## Repository Structure

```text
.
├── README.md
├── .gitignore
├── proof-portfolio/
│   ├── README.md
│   ├── main.tex
│   ├── proof_portfolio.pdf
│   └── figures/
├── alden-handshake-problem/
│   ├── README.md
│   ├── main.tex
│   ├── alden_handshake_essay.pdf
│   └── figures/
├── problem-sets/
│   ├── README.md
│   ├── assignment-08-induction-and-relations/
│   ├── assignment-11-functions-and-modular-arithmetic/
│   └── assignment-12-bijections-and-permutations/
└── assets/
    └── previews/
```

## Compiling the Documents

All documents are self-contained and compile with `pdflatex`.

```bash
# Example: Compiling the Proof Portfolio (run twice for TOC)
cd proof-portfolio
pdflatex main.tex
pdflatex main.tex

# Example: Compiling the Alden Handshake Essay
cd alden-handshake-problem
pdflatex main.tex
```

Prerequisites: A standard TeX distribution (TeX Live, MacTeX, or MiKTeX) with standard AMS packages.

## About Me

Robert Kohn  
Muhlenberg College  
Mathematics · Statistics · Physics  

GitHub: [https://github.com/rkohnmn](https://github.com/rkohnmn)
