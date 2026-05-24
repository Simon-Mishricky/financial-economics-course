# Financial Economics (ECON8037)

**Graduate course materials**
**Australian National University, Research School of Economics**
**Semester 2, 2023**

**Instructor:** Simon Mishricky

## Overview

This repository archives the lecture notes, tutorials, assignments, and examinations for ECON8037 Financial Economics, a graduate course taught at the Australian National University. The course develops the theoretical foundations of asset pricing and extends them to monetary theory and the economics of cryptocurrencies.

## Course Description

Financial economics studies equilibrium in markets where agents trade claims to uncertain future payoffs. The course is organised around three complementary strands:

- **Asset pricing.** Arbitrage, state prices, stochastic discount factors, and equilibrium valuation of bonds, equities, and derivatives.
- **Monetary theory.** Search-theoretic foundations of money following Lagos and Wright (2005) and Rocheteau and Lagos, with attention to liquidity, bargaining, and the welfare cost of inflation.
- **Cryptocurrency economics.** A treatment of decentralised digital currencies based on Chiu and Koeppl (2017), covering mining, double-spending, and the design of proof-of-work systems.

The unifying theme is the pricing of time, risk, and liquidity in environments with frictions.

## Course Structure

The course consists of eleven weekly lectures and accompanying tutorials, grouped into four modules.

### 1. Foundations
Mathematical and computational preliminaries, the structure of financial markets, and an introduction to Python for quantitative work.

### 2. Monetary Theory and Cryptocurrencies
Search-theoretic models of money (Lagos-Wright, Rocheteau-Lagos) followed by an analysis of cryptocurrency systems building on Chiu and Koeppl (2017).

### 3. Asset Valuation
Present-value relations, the term structure of interest rates, equity valuation, and the pricing of contingent claims.

### 4. Complete Markets and Synthesis
Arrow-Debreu securities, state-price densities, market completeness and spanning, the fundamental theorems of asset pricing, and a concluding synthesis.

## Repository Contents

```
financial-economics-anu/
├── lectures/           Weekly lecture slides (PDF)
├── tutorials/          Tutorial problem sets (PDF)
├── assignments/        Take-home assignments (PDF)
├── exams/              Final examination papers (PDF)
├── Slides.tex          LaTeX source for selected slide material
└── README.md
```

### Materials Included

| Component   | Items |
|-------------|-------|
| Lectures    | Eleven weekly lecture sets covering the four modules above |
| Tutorials   | Nine tutorial problem sets aligned with the lecture sequence |
| Assignments | Assignment 1 and Assignment 2 |
| Exams       | Final examination and deferred final examination |

## Learning Outcomes

On completion of the course, students are expected to be able to:

1. Apply no-arbitrage and equilibrium principles to value financial securities.
2. Derive and interpret stochastic discount factors and state-price densities.
3. Analyse portfolio choice under uncertainty using expected utility theory.
4. Use search-theoretic models to characterise the role of money as a medium of exchange.
5. Evaluate the economic mechanisms underlying cryptocurrency systems, including incentives for honest mining and the limits of decentralised consensus.
6. Implement and solve standard models numerically in Python.

## Prerequisites

- **Mathematics.** Multivariable calculus, linear algebra, probability theory, and constrained optimisation.
- **Economics.** Graduate microeconomic theory, including consumer choice and general equilibrium.
- **Programming.** Basic familiarity with Python; further tools are introduced as needed.

## Assessment

| Component              | Weight | Timing       |
|------------------------|--------|--------------|
| Take-home Assignment 1 | 20%    | Week 4       |
| Take-home Assignment 2 | 20%    | Week 10      |
| Final examination      | 60%    | Exam period  |

## Key Topics

### Mathematical foundations
Probability spaces, expected utility, stochastic processes, dynamic programming.

### Asset pricing
No-arbitrage pricing, risk-neutral valuation, stochastic discount factors, Arrow-Debreu securities, term structure, and derivatives.

### Portfolio theory
Mean-variance analysis, the Capital Asset Pricing Model, multi-factor models, and dynamic portfolio choice.

### Monetary economics
Search and bargaining in decentralised exchange, the Lagos-Wright framework, money as a medium of exchange, and the welfare cost of inflation.

### Cryptocurrency economics
Proof-of-work mining, double-spending incentives, settlement finality, and the design and welfare properties of decentralised payment systems.

### Markets and information
Complete versus incomplete markets, spanning, informational efficiency, and the role of prices in aggregating information.

## Computational Methods

Python is used throughout for numerical optimisation, Monte Carlo simulation, data analysis, and the implementation of pricing and equilibrium models. The emphasis is on translating theoretical objects into reproducible code.

## References

### Primary texts
- Duffie, D. (2010). *Dynamic Asset Pricing Theory*, 3rd ed. Princeton University Press.
- Cochrane, J. H. (2005). *Asset Pricing*, revised ed. Princeton University Press.

### Monetary theory
- Lagos, R., and Wright, R. (2005). "A Unified Framework for Monetary Theory and Policy Analysis." *Journal of Political Economy*, 113(3), 463-484.
- Rocheteau, G., and Lagos, R. "Liquidity in Asset Markets with Search Frictions" and related work on search-theoretic monetary models.

### Cryptocurrency economics
- Chiu, J., and Koeppl, T. V. (2017). "The Economics of Cryptocurrencies - Bitcoin and Beyond." Bank of Canada Staff Working Paper.

### Supplementary
- LeRoy, S. F., and Werner, J. (2014). *Principles of Financial Economics*, 2nd ed. Cambridge University Press.
- Lengwiler, Y. (2004). *Microfoundations of Financial Economics*. Princeton University Press.
- Varian, H. R. (1987). "The Arbitrage Principle in Financial Economics." *Journal of Economic Perspectives*, 1(2), 55-72.

## Usage

These materials are intended for:

- **Students** revisiting the course or preparing for examinations.
- **Instructors** designing related graduate courses in financial or monetary economics.
- **Researchers** seeking a self-contained introduction to the asset-pricing, monetary, and cryptocurrency literatures covered.

## License

Copyright (c) 2023 Simon Mishricky.

These materials are made available for personal study and non-commercial educational use with attribution. For other uses, please contact the author.

## Contact

Simon Mishricky
Research School of Economics, Australian National University
Email: simon.mishricky@gmail.com

## Acknowledgments

The course was developed during the author's appointment at the Research School of Economics, ANU. Thanks are due to colleagues and students whose feedback shaped the material.
