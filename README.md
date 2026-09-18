# Behind the AfD's 2025 Result: A Brief Empirical Note

*A multi-method empirical analysis of the Alternative für Deutschland's historic result in the 2025 German Federal Election, examining its geographic structure, structural determinants, individual-level predictors, and ideological profile.*

---

## Research Question

What drove the AfD's 20.8 percent second-vote share in the 2025 German Federal Election — the strongest far-right result in postwar German federal electoral history — and to what extent does it reflect geographic concentration, structural grievances, attitudinal factors, or ideological supply?

---

## Motivation

The AfD's 2025 result marks a qualitative shift in German party politics: a far-right party finished second in a federal election for the first time since 1945. Understanding the sources of this surge matters for democratic theory, comparative politics, and the study of far-right mobilization in Western Europe.

Existing work has debated whether AfD support reflects economic dislocation ("modernization losers"), cultural backlash, or political disaffection. This note contributes updated evidence from the 2025 cycle, combining geographic, structural, individual-level, and programmatic analyses.

---

## Contribution

- **Empirical**: Documents municipality-level geographic patterns of AfD support and change (2021–2025) across 10,676 *Gemeinden*
- **Empirical**: Provides a covariate balance check between Eastern and Western municipalities using 2022 INKAR indicators
- **Empirical**: Estimates individual-level predictors of AfD voting using the 2025 GLES post-election survey
- **Empirical**: Situates the AfD's ideological profile in the German party system using Manifesto Project coding

---

## Identification Strategy

Descriptive and associational. The note does not claim causal identification. Individual-level analyses use linear probability models (OLS) with four nested specifications and standard errors clustered by federal state (16 clusters). Model 4 includes state fixed effects to absorb unobserved state-level heterogeneity.

---

## Data

| Dataset | Source | Coverage |
|---------|--------|----------|
| Municipality-level electoral results | GERDA (German Electoral Database) | Federal elections 1990–2025, harmonized to 2025 boundaries |
| Socioeconomic indicators | INKAR (BBSR) | Municipality level, 2022 |
| Individual-level survey | GLES Cross-Section Post-Election Survey (ZA10100, v4.0.0) | ~2,500 respondents, 2025 |
| Party manifestos | Manifesto Project (MARPOR), Version 2024a | German parties, 2025 federal election |

> **Note:** GLES microdata requires registration via GESIS and is not redistributed in this repository.

---

## Replication

The manuscript is fully self-contained in paper2.qmd. Render it with:

quarto::quarto_render("paper2.qmd")

---

## Citation

Guelfi, Kevin. (2026). Behind the AfD's 2025 Result: A Brief Empirical Note. University of Chicago, Available at: [https://github.com/kevinguelfi/germany_research_note]