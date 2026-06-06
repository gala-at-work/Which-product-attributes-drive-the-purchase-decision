# Which-product-attributes-drive-the-purchase-decision

This project analyses consumer preferences for chocolate truffles using the choice-based conjoint analysis approach. The data comes from a conjoint survey in which 44 respondents each completed 24 choice tasks. In every task they were shown 4 product alternatives, plus a "none" (no-purchase) option and asked to pick one. The truffle profiles varied across five
attributes:
- **Flavor** — Fruity, Nutty, Mixed
- **Filling** — Creamy, Liquid
- **Superfoods** — Yes / No
- **Size** — 5g, 10g, 15g, 20g
- **Price** — €5.99, €6.99, €7.99

Because respondents reveal their priorities through trade-offs, the analysis lets us estimate how much each attribute drives choice and what customers are willing to pay for each feature.

## What This Analysis Does

The notebook implements a **conditional (multinomial) logit model** 
- Descriptive statistics and price–choice cross-tabulations
- Maximum-likelihood estimation of the choice model (with a likelihood-ratio test)
- **Part-worth utilities** for each attribute level
- **Relative Attribute Importance (RAI)** — how much each attribute drives choice
- **Willingness-to-Pay (WTP)** in euros, with delta-method standard errors
- **Market simulation** — predicting market shares for a hypothetical product line


