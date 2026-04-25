# Loan Default Prediction via Decision Trees

**Tools:** R · rpart · tidyverse · Decision Trees · Loss Matrix · Pruning

---

## Problem

Loan default data was heavily imbalanced, causing naive models to fail at detecting defaults and limiting the usefulness of predictions for risk management decisions.

## Approach

Built a decision tree in R using rpart, addressing class imbalance through balanced sampling and a custom loss matrix to penalize missed defaults 10x more than false positives. Tuned the complexity parameter and pruned the tree using cross-validation to reduce overfitting and improve generalizability.

## Impact

Produced an interpretable pruned tree that improved detection of high-risk borrowers, enabling more targeted risk classification and supporting more informed lending decisions.

---

## Files

| File | Description |
|------|-------------|
| `loan_default_decision_tree.Rmd` | R Markdown source file with full analysis |
| `loan_default_decision_tree.html` | Rendered HTML output |

---

*Part of my data & analytics portfolio — [cameronbatts.github.io](https://cameronbatts.github.io)*
