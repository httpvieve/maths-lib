

## 📂 Papers

### 📄 001 — The Structure and Behavior of Prime Numbers
| | |
|---|---|
| **File** | [`main.tex`](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/main.tex) |
| **Bibliography** | [`reference.bib`](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/reference.bib) |
| **PDF** | [`main.pdf`](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/main.pdf) |

**Abstract:**
This paper presents a comprehensive exploration of prime numbers — their definition, fundamental properties, and the profound mathematical theorems and open conjectures that surround them. Beginning with Euclid's classical proof of the infinitude of primes, the discussion progresses through the Fundamental Theorem of Arithmetic, primality testing methods, the distribution of primes via the Prime Number Theorem, and landmark results on bounded prime gaps. The paper further examines the pseudorandom nature of primes and concludes with a survey of their far-reaching contributions to modern mathematics, cryptography, and science.

**Topics covered:**
- Fundamental Theorem of Arithmetic · Euclid's theorem · Mersenne primes & perfect numbers
- Sieve of Eratosthenes · Fermat's Little Theorem · Prime Number Theorem
- Goldbach conjecture · Twin prime conjecture · Bertrand's postulate
- Euler product formula · Riemann zeta function & Riemann hypothesis
- Zhang's bounded gap theorem ($N \leq 70{,}000{,}000$) · Polymath8 ($N \leq 246$)
- Pseudorandomness · Cramér model · Applications in cryptography (RSA, Diffie–Hellman, AKS)

---

> 🔜 *More papers will appear here as research continues.*

---

## 🗂️ Repository Structure

```
maths-lib/
│
├── README.md                       ← You are here
│
├── [001] Structure and Behavior of Primes/
│   ├── main.tex                    ← LaTeX source
│   ├── reference.bib               ← Bibliography (30+ sources)
│   └── output
│       └── Structure_and_Behavior_of_Primes_by_Vieve.pdf           ← Compiled output
│
├── 002-[next-paper]/               ← Future paper (placeholder)
│   ├── main.tex
│   ├── reference.bib
│   └── output
│       └── filename.pdf
│
└── ...
```
---

## 🔨 How to Build a Paper (LaTeX → PDF)

All papers are written in LaTeX. To compile a paper locally:

### 1. Install a LaTeX distribution

| Platform | Recommended |
|----------|-------------|
| Linux | `sudo apt install texlive-full` · or · `sudo pacman -S texlive-most` |
| macOS | [MacTeX](https://www.tug.org/mactex/) via `brew install --cask mactex` |
| Windows | [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/) |
| Online | [Overleaf](https://www.overleaf.com) — upload `.tex` + `.bib`, compile instantly |

### 2. Compile

```bash
# Navigate into the paper's folder
cd "[001] Structure and Behavior of Primes"

# Full build with bibliography (4-step process)
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or use `latexmk` to handle all passes automatically:

```bash
latexmk -pdf main.tex

# To clean up auxiliary files afterwards
latexmk -c
```

The output `main.pdf` will appear in the same folder.

---

## 📖 How to Read

If you just want to read without compiling:

1. Navigate to the paper's folder above
2. Click the `.pdf` file — GitHub renders PDFs in-browser
3. Or download and open locally

All mathematical notation renders correctly in the compiled PDF. The `.tex` source is also readable as plain text for those who want to inspect proofs, theorems, or LaTeX structure.

---

## 🧭 Fields & Topics Index

As the library grows, this index will map topics to papers:

| Field | Topic | Paper |
|-------|-------|-------|
| Analytic Number Theory | Prime distribution, PNT, Riemann hypothesis | [001](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/) |
| Analytic Number Theory | Bounded prime gaps, Zhang, Polymath8 | [001](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/) |
| Number Theory | Primality testing, RSA, AKS | [001](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/) |
| Number Theory | Goldbach conjecture, twin primes | [001](./%5B001%5D%20Structure%20and%20Behavior%20of%20Primes/) |
| *More fields TBA* | | |

---

## 🔗 Useful Resources

General resources for pure and theoretical mathematics:

| Resource | Description |
|----------|-------------|
| [The Prime Pages](https://primes.utm.edu/) | Prime number database and glossary |
| [MathWorld](https://mathworld.wolfram.com/) | Wolfram's encyclopaedia of mathematics |
| [arXiv math](https://arxiv.org/archive/math) | Preprint server for mathematics research |
| [GIMPS](https://www.mersenne.org/) | Great Internet Mersenne Prime Search |
| [Clay Mathematics Institute](https://www.claymath.org/) | Millennium Prize Problems |
| [Polymath Project](https://polymathprojects.org/) | Collaborative open mathematics |
| [Terence Tao's Blog](https://terrytao.wordpress.com/) | Research commentary by a Fields Medallist |
| [3Blue1Brown](https://www.youtube.com/c/3blue1brown) | Visual intuition for advanced mathematics |

---

- 📧 Reach me via [GitHub Issues](../../issues) for questions or discussions on any paper
- ⭐ Star the repo if you find it useful/interesting ouo


