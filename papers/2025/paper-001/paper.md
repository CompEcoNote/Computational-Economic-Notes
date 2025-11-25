
### 2. `_papers/2025/paper-001/paper.md`
```markdown
---
title: "An Example Paper in Computational Economics"
authors:
- name: "Jane Doe"
  affiliation: "University of Economics"
- name: "John Smith" 
  affiliation: "Institute for Economic Research"
abstract: |
  This paper demonstrates the proper format for submissions to Computational Economic Notes. 
  We show how to structure research papers, include mathematical notation, and format references. 
  The template follows best practices for reproducible computational economics research.
layout: default
---

# Introduction

Computational economics has become an essential tool for economic analysis, allowing researchers to tackle complex problems that are intractable with analytical methods alone. This paper provides a template for submissions to Computational Economic Notes.

## Research Question

How can we establish best practices for reproducible computational economic research?

# Methods

## Data Sources

We utilize synthetic data generated for demonstration purposes.

## Computational Approach

The analysis employs standard econometric techniques implemented in Python and R.

### Model Specification

The basic model can be expressed as:

$$ Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \epsilon $$

Where:
- $Y$ is the dependent variable
- $X_1$ and $X_2$ are independent variables
- $\epsilon$ represents the error term

# Results

## Main Findings

Our analysis reveals important patterns in the synthetic data that demonstrate proper paper formatting.

**Table 1:** Regression Results
| Variable | Coefficient | Standard Error |
|----------|-------------|----------------|
| Intercept | 2.34* | (0.15) |
| X1 | 0.56** | (0.12) |
| X2 | -0.23 | (0.18) |

*Note: *p < 0.05, **p < 0.01*

# Discussion

## Interpretation

The results indicate that proper formatting enhances research reproducibility and accessibility.

## Limitations

This being a template paper, the results are for demonstration purposes only.

## Future Research

Future work could extend these formatting guidelines to include more complex computational methods.

# References

Include a `references.bib` file in the same folder and cite using Pandoc style: [@smith2020]