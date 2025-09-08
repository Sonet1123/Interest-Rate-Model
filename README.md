# Interest-Rate-Model
Hull–White (1F) Extended Vasicek Model Bond Option Pricing


This project prices **European options on zero-coupon bonds** under **Hull–White (one factor)** and compares to **Black-76**. Includes three curve builds (flat, pillar, bootstrapped), sanity checks, and small sensitivity analyses.

## 
- Show that HW1f bond options ≡ Black-76 when using the **HW-implied bond-price volatility** (σ_P).
- Demonstrate put–call parity and the relative impact of **volatility vs curve vs mean reversion**.

## What’s inside
- **Curve builders:** flat rate; pillar zeros with linear interpolation; toy bootstrap from a deposit and short par-swap quotes.
- **HW1f pricer:** computes σ_P and prices ZCB options in closed form.
- **Black-76 comparator:** same payoff under the S-forward measure.
- **Checks:** HW ≡ Black-76(@σ_P); parity; ATM behavior; parameter and curve bumps.

## Files 
-for code see 'main.ipynb'
-for report see 'report.pdf' file

