# Special Topic Latex

This directory contains the latex code and the pdf file of my special topic work with the title: "Foundations of Financial Mathematics and Implementation of Models in Option Valuation". The whole 100 pages long text is in greek. Conducted as part of the subject “Special Topics” at my university, this thesis expands on the article: Implementation and calibration of the Heston stochastic volatility model (see repository Heston_SV_Model) by including additional theory, rigorous proofs, and various implementations of models in topics such as market forecasting and numerical methods in derivatives pricing.<br>

## Abstract

This repository contains a comprehensive exploration of financial mathematics, focusing on stochastic processes and their applications in modeling and derivatives pricing.

### Chapter 1: Brownian Motion  
We introduce the foundational concepts and properties of Brownian motion, along with related stochastic processes, including symmetric and scalar random walks. Topics, such as the first passage time, the reflection principle, and the maximum properties of Brownian motion, are also discussed.

### Chapter 2: Stochastic Calculus  
This chapter begins with an introduction to geometric Brownian motion and progresses to the Ito integral and Ito's lemma, forming the foundation for asset modeling. Practical applications of these concepts are demonstrated, particularly for market forecasting.

### Chapter 3: Option Pricing and Monte Carlo Simulations  
Using the martingale method, we derive a general formula for pricing vanilla options and prove the Black-Scholes formula using calculus. Additionally, we implement a simple algorithm with Monte Carlo simulations to price European and Barrier options. The chapter concludes with an implementation of the Least-Squares Monte Carlo (LSM) method by Longstaff and Schwartz for pricing American options.

### Chapter 4: Heston Model Calibration and Comparison  
We explore the Heston stochastic volatility model, demonstrating its performance and full calibration. By extending the Black-Scholes model, the Heston model provides greater flexibility, including Black-Scholes as a special case. A weighted least-squares error fit is employed for calibration, combining the deterministic trust region reflective optimization method with the stochastic simulated annealing algorithm. We then compare the efficiency of the Heston and Black-Scholes models on the S&P 500 stock index.

### Chapter 5: Python code
The final section includes the full code used throughout the thesis, offering practical insights and tools for further exploration.

---
### Bibliography:

1. Steven E. Shreve (2004). *Stochastic Calculus for Finance II Continuous Time Models*. Springer. [Link](https://link.springer.com/book/9780387401010)

2. Bernt Øksendal (2003). *Stochastic Differential Equations*. Springer, New York. [Link](https://link.springer.com/book/10.1007/978-3-642-14394-6)

3. Ubbo F. Wiersema (2008). *Brownian Motion Calculus*. Wiley. [Link](https://www.wiley.com/en-us/Brownian+Motion+Calculus-p-9780470021705)

4. Z. Brzeźniak and T. Zastawniak (1999). *Basic Stochastic Processes*. Springer-Verlag, Berlin. [Link](https://link.springer.com/book/10.1007/978-1-4471-0533-6)

5. Π.-Χ. Γ. Βασιλείου (2001). *Στοχαστικά Χρηματοοικονομικά*. Εκδόσεις Ζήτη. [Link](https://ziti.gr/vivlio/vasileioy-panagiotis-xristos-stoxastika-xrimatooikonomika/)

6. Karatzas, I., and Shreve, S. (1991). *Brownian Motion and Stochastic Calculus*. Springer-Verlag, New York. [Link](https://link.springer.com/book/10.1007/978-1-4612-0949-2)

7. Rick Durrett (2019). *Probability: Theory and Examples (5th edition)*. Cambridge University Press. [Link](https://www.cambridge.org/core/books/probability/DD9A1907F810BB14CCFF022CDFC5677A)

8. Heston, S. L. (1993). *A closed-form solution for options with stochastic volatility, with applications to bond and currency options*. Review of Financial Studies, 6, 327–343. [Link](https://doi.org/10.1093/rfs/6.2.327)

9. Black, F., & Scholes, M. (1973). *The Pricing of Options and Corporate Liabilities*. Journal of Political Economy, 81(3), 637–654. [Link](http://www.jstor.org/stable/1831029)

10. Rouah F. D. (2011). *Euler and Milstein discretization*. Documento de Trabajo, Sapient Global Markets, Estados Unidos. [Link](https://frouah.com/finance%20notes/Euler%20and%20Milstein%20Discretization.pdf)

11. Goutham Balaraman (2016). *Modeling Volatility Smile and Heston Model Calibration Using QuantLib Python*. [Link](https://gouthamanbalaraman.com/blog/volatility-smile-heston-model-calibration-quantlib-python.html)

12. Yiran Cui, Sebastian del Baño Rollin, Guido Germano (2017). *Full and fast calibration of the Heston stochastic volatility model*. European Journal of Operational Research, Volume 263, Issue 2, Pages 625-638, ISSN 0377-2217. [Link](https://doi.org/10.1016/j.ejor.2017.05.018)

13. M. A. Branch, T. F. Coleman, and Y. Li (1999). *A Subspace, Interior, and Conjugate Gradient Method for Large-Scale Bound-Constrained Minimization Problems*. SIAM Journal on Scientific Computing, Vol. 21, Number 1, pp 1-23. [Link](https://doi.org/10.1137/S1064827595289108)

14. Olivier Pironneau (2019). *Calibration of Heston Model with Keras*. [Link](https://hal.sorbonne-universite.fr/hal-02273889v1/document)

15. Longstaff, Francis A., and Eduardo S. Schwartz (2001). *Valuing American Options by Simulation: A Simple Least-Squares Approach*. The Review of Financial Studies, vol. 14, no. 1, pp. 113–47. [Link](https://people.math.ethz.ch/%7Ehjfurrer/teaching/LongstaffSchwartzAmericanOptionsLeastSquareMonteCarlo.pdf)

16. Gustafsson, William (2015). *Evaluating the Longstaff-Schwartz method for pricing of American options*. [Link](https://uu.diva-portal.org/smash/get/diva2:818128/FULLTEXT01.pdf)

17. Tsallis C, Stariolo DA (1996). *Generalized Simulated Annealing*. Physica A, 233, 395-406. [Link](https://www.sciencedirect.com/science/article/abs/pii/S0378437196002713)

18. Xiang Y, Gong XG (2000). *Efficiency of Generalized Simulated Annealing*. Physical Review E, 62, 4473. [Link](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.62.4473)

19. Cont, R. (2001). *Empirical properties of asset returns: stylized facts and statistical issues*. Quantitative Finance, 1, 223 - 236. [Link](https://www.semanticscholar.org/paper/Empirical-properties-of-asset-returns%3A-stylized-and-Cont/b674f1384a95948d52018d1748e7284ef566233c)

