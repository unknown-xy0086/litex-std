# ROADMAP
This is a roadmap for contructing litex standard libraries for different branches in Math. 

This document outlines the roadmap for building **litex-std**, a standard library for the Litex proof assistant.  
Our strategy is **skeleton-first**: we prioritize adding **definitions and theorem statements** early (even with placeholders), and gradually fill in proofs.

---

## Global Phases

Perhaps we may refer to mathlib4 in LEAN to see what we can do here in Litex. 

- **Phase 1**: Provide essential structures to support basic number theory, algebra, and linear algebra.  
- **Phase 2**: Add fundamental theorems from number theory, algebra, and analysis.  
- **Phase 3**: Enrich the library with combinatorics, probability, and deeper results in algebra/analysis.  

---

## Domain Roadmaps

### 1. Foundations (Logic & Set Theory)
**Phase 1**
- Sets, functions, relations  
- Basic logical inference  
- Reflexive/symmetric/transitive relations  

**Phase 2**
- Equivalence relations & quotient sets  
- Partial and total orders  

**Phase 3**
- ...  

---

### 2. Number Theory
**Phase 1**
- Divisibility, gcd, lcm  
- Euclidean algorithm  
- Modular arithmetic basics  

**Phase 2**
- Fundamental Theorem of Arithmetic  
- Chinese Remainder Theorem  
- Fermat’s Little Theorem, Euler’s Theorem  

**Phase 3**
- ...  

---

### 3. Algebra
**Phase 1**
- Group axioms (Group, Subgroup, Homomorphism)  
- Basic lemmas (identity/ inverse uniqueness)  

**Phase 2**
- Ring and Field definitions  
- Isomorphism theorems  
- Ideals and quotient structures  

**Phase 3**
- Sylow theorems  
- Polynomial rings and field extensions  

---

### 4. Linear Algebra
**Phase 1**
- Vector space axioms  
- Basis and dimension  

**Phase 2**
- Matrix definitions and operations  
- Rank, null space  

**Phase 3**
- Eigenvalues and eigenvectors  
- Jordan normal form
- ...

---

### 5. Analysis
**Phase 1**
- Real numbers (axiomatized, or imported as `axiom R`)  
- Convergent sequences  

**Phase 2**
- ε–δ limit definition  
- Function continuity  
- Intermediate Value Theorem  

**Phase 3**
- Differentiation and integration  
- Uniform convergence, power series
- ... 

---

### 6. Combinatorics
**Phase 1**
- Factorials, binomial coefficients  
- Simple counting principles  

**Phase 2**
- Binomial theorem  
- Pigeonhole principle  

**Phase 3**
- Graph theory basics (degree, connectivity)  
- ...

---

## ✅ Milestone Checklist

- [ ] ... 


---

## 🤝 Collaboration Guidelines

- **Skeletons first**: Add theorem statements early, proofs later.  
- **CI check**: Ensure all files successfully run.  
- ... 

---
