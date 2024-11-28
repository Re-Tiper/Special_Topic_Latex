# Special Topic Latex

This directory contains the latex code and the pdf file of my special topic work with the title: "Foundations of Financial Mathematics and Implementation of Models in Option Valuation". The whole 100 pages long text is in greek. <br>

## Abstract

This repository contains a comprehensive exploration of financial mathematics, focusing on stochastic processes and their applications in modeling and analyzing financial instruments.

### Chapter 1: Brownian Motion  
We introduce the foundational concepts and properties of Brownian motion, along with related stochastic processes, including symmetric and scalar random walks. Advanced topics, such as the first passage time, the reflection principle, and the maximum properties of Brownian motion, are also discussed.

### Chapter 2: Stochastic Calculus  
This chapter begins with an introduction to geometric Brownian motion and progresses to the Ito integral and Ito's lemma, forming the foundation for asset modeling. Practical applications of these concepts are demonstrated, particularly for financial instruments.

### Chapter 3: Option Pricing and Monte Carlo Simulations  
Using the martingale method, we derive a general formula for pricing vanilla options and prove the Black-Scholes formula using calculus. Additionally, we implement a simple algorithm with Monte Carlo simulations to price European and Barrier options. The chapter concludes with an implementation of the Least-Squares Monte Carlo (LSM) method by Longstaff and Schwartz for pricing American options.

### Chapter 4: Heston Model Calibration and Comparison  
We explore the Heston stochastic volatility model, demonstrating its performance and full calibration. By extending the Black-Scholes model, the Heston model provides greater flexibility, including Black-Scholes as a special case. A weighted least-squares error fit is employed for calibration, combining the deterministic trust-region reflective optimization method with the stochastic simulated annealing algorithm. We then compare the efficiency of the Heston and Black-Scholes models on the S&P 500 stock index.

---

The final section includes the full code used throughout the book, offering practical insights and tools for further exploration.
