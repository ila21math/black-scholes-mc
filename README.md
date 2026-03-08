# Black-Scholes Options Pricing & Monte Carlo Simulation

Prices European call and put options using the Black-Scholes closed-form 
solution, computes all five Greeks (Δ, Γ, ν, Θ, ρ), and benchmarks Monte 
Carlo simulation convergence across 100–50,000 GBM paths. Extracts implied 
volatility from live SPY options data and visualises the volatility skew.

**Libraries:** NumPy, pandas, matplotlib, scipy, yfinance  
**Data:** Live SPY options chain via Yahoo Finance (expiry 2026-03-31)  
**Results:** ATM IV = 22.64%, IV range 12.8%–32.7%, MC error $0.0004 at N=10,000
