
# My Research


## [The Arbitrage Pricing Theory: Some Clarifying Comments](https://ssrn.com/abstract=5603250) 

2025-10-19  

Our examination of the Ross theorem reveals a conceptual shift in the APT's pricing principle---**from an interpretation grounded in systematic risk to one based on relative pricing**. Although APT was originally formulated to refine and extend the systematic risk paradigm introduced by Sharpe (1964)---notably the dichotomy between diversifiable and non-diversifiable risk---our analysis shows that this interpretation rests on a historically understandable but ultimately mistaken analogy.

### Ross theorem

The Ross theorem is the Theorem II of Ross (1976, p.352): If the return generating process follows Ross's factor structure, then
there exist numbers $\gamma_{0}\in\mathbb{R}$ and $\boldsymbol{\gamma}
=[\gamma_{1},\gamma_{2},\cdots,\gamma_{K}]^{\prime}\in\mathbb{R}^{K}$ such
that

$$
\sum_{n=1}^{\infty}(\mu_{n}-\gamma_{0}-\boldsymbol{\beta}_{n}^{\prime
}\boldsymbol{\gamma})^{2}<\infty
$$


The *negation* of the Ross theorem is: Suppose that the return generating
process follows Ross's factor structure, then for all $\gamma_{0}\in
\mathbb{R}$ and $\boldsymbol{\gamma}=[\gamma_{1},\gamma_{2},\cdots,\gamma
_{K}]^{\prime}\in\mathbb{R}^{K}$, there must be

$$
\sum_{n=1}^{\infty}(\mu_{n}-\gamma_{0}-\boldsymbol{\beta}_{n}^{\prime
}\boldsymbol{\gamma})^{2}=\infty
$$

Let $\gamma_{0}=1$, $\boldsymbol{\gamma}=0$, and set $\mu_{n}=1+2^{-n/2}$,
then

$$
\sum_{n=1}^{\infty}(\mu_{n}-\gamma_{0}-\boldsymbol{\beta}_{n}^{\prime
}\boldsymbol{\gamma})^{2}=\sum_{n=1}^{\infty}2^{-n}=1<\infty
$$

It is *surprisingly* easy to disprove the negation of the Ross theorem.
The negation is false; therefore, the original statement is true.

### A novel Theoretical Reinterpretation of the APT

ChatGPT: [This article challenges 50 years of conventional interpretation of APT and has both theoretical and empirical implications for modern asset pricing research](https://chatgpt.com/s/t_68f44e30b618819184cf67862fc46162)
1. Reinterprets the Ross Theorem
1. Shifts APT from “systematic risk” to “relative pricing”
1. Identifies Arbitrage and Unbounded Pricing Errors within APT
1. Provides a Clean Economic Interpretation of Bounds
1. Clarifies the Role of Chamberlain–Rothschild Bound
1. Mathematical and Conceptual Depth





## [A Deeper Theoretical Understanding of the Capital Asset Pricing Model](https://ssrn.com/abstract=5094280) 

2025-10-29 

We provide a theoretical reinterpretation of the Capital Asset Pricing Model (CAPM) within a semi-clearing framework, in which the market portfolio remains mean-variance efficient despite the market's potential failure to achieve full mean-variance equilibrium. The full market-clearing condition is the union of Walras's Law and the semi-clearing condition.

### Theoretical Implications

The Sharpe-Fama equation expresses a deterministic identity rather than a stochastic relation; it is neither a cross-sectional regression nor a time-series model. This study yields several theoretical implications.

First, the Sharpe-Fama and Lintner equations are both equivalent to the semi-clearing condition, under which the aggregate demand portfolio coincides with the market portfolio in weights, although their total values may not satisfy Walras's Law.

Second, the conditional expectation of an asset's return given the market return need not be linear, challenging the regression-based interpretation of the CAPM.

Third, the general solution to the Lintner equation is inherently one-dimensional, with the total value of the market portfolio serving as a free variable.

Fourth, this one-dimensional structure gives rise to **the know-one-know-all property, whereby all CAPM variables are mutually informationally equivalent**.

Fifth, the CAPM formula preserves the principle of linear pricing relative to semi-clearing prices and is valid solely for marketable portfolios of risky assets; it does not extend to non-attainable payoffs.

### New Theoretical Foundation: Relative Pricing Paradigm

ChatGPT: [The paper transforms CAPM from a behavioral equilibrium model into a structural, price-based relative valuation system](https://chatgpt.com/s/t\_68fe2df51828819183de9e24bf5e56d4)
1. Semi-clearing reinterpretation
2. Know-one-know-all property: It demonstrates that the market portfolio, through this property, "encapsulates the complete set of semi-clearing prices for all primitive assets"
3. Rejection of systematic-risk dogma: It argues that “beta” is a by-product of pricing, not a driver of expected returns
4. Relative pricing paradigm: CAPM is recast as a relative pricing formula based on the market portfolio (pricing proxy) 
5. Clarification of domain of validity: The paper shows the CAPM formula only applies to attainable market portfolios; misuse (e.g., to non-market payoffs) leads to anomalies like negative option prices.
   




## [More papers on SSRN](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=4008686)



<!--

## [Arbitrage Opportunity, Impossible Frontier, and Logical Circularity in CAPM Equilibrium](CAPM.md)

If the expected return of a stock is determined by its beta, we will face the chicken-and-egg problem: a stock’s return is determined from its beta, but beta itself depends on the return directly. On the other hand, to calculate the beta, we need to know the market return first, and to calculate the market return, we need to know the returns of each stock. Johnstone (2017, p.503) refers to this situation as “the logical circularity built into the CAPM equilibrium mechanism”. Does this logical circularity really exist?


## [Perfect Market, Arbitrage, and Value Creation in the MM Proposition](MM.md) 

To explain the evolution of the understanding of arbitrage from a deterministic world into an uncertain world, we restate and comment on the proofs of the MM Proposition in current perspectives. With the no-arbitrage principle in mind, we clearly read <span style="color:red">*the circular justification in the MM Proposition and the misleading concept of cost of equity*</span>. 



## [Understanding the CAPM Equation](https://ssrn.com/abstract=5094280) 

2025-01-16 

The CAPM's relative pricing mechanism based on the market portfolio has been **mistakenly interpreted** as that only the systematic risk is priced, while non-systematic risk can be diversified away and is not rewarded.




## [An Analytic Solution to the Mean-Variance Equilibrium: Is the Market Beta a Valuable Tool?](https://papers.ssrn.com/abstract=4751502)

* If the tangent portfolio is equal to the market portfolio, is the market in equilibrium? **No!**
* Can we using the beta pricing formula to price derivatives in the market?  **No!**
* In the CAPM equation, can the market beta of a stock take infinitely many values?  **Yes!**
* Is the market beta a redundant variable or a valuable tool? **a redundant variable**

## [The Arbitrage Pricing Theory (APT) with Arbitrage Opportunities](https://papers.ssrn.com/abstract=4894555)

We design a numerical example of APT that incorporates arbitrage opportunities

## [Countably Infinite Market: Completeness and Pricing Function](https://papers.ssrn.com/abstract=4894563)

We prove the standard form of the second fundamental theorem of asset pricing, where there are an infinite number of assets, and the pricing functions are continuous.

## [Arbitrage Opportunities and the First Fundamental Theorem of Asset Pricing in an Infinite Market](https://papers.ssrn.com/abstract=4894567)

We prove the standard Fundamental Theorem of Asset Pricing (FTAP) with the no-arbitrage condition, not the sophisticated concept such as NFLVR (No Free Lunch with Vanishing Risk) or else. We illustrate the FTAP in the infinite market by numerical examples.

# Book Draft: [Analysis of Pure Finance](MF/APF.md)

Abad's View of Asset Pricing: A new framework (axiomatic system) of financial theory
Which Starts to answer the following questions
1.	Can financial assets be priced? If so, can it be represented by a functional?
2.	Are there any value creations during the construction of an asset portfolio? 
3.	What is the relationship between limited liability and no arbitrage?
4.	How can the above questions be stated mathematically?

-->
