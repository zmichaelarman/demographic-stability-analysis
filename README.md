# demographic-mortality-geometry

Currently in process of reevaluating entire pipeline, my resume references a completely different project from what will appear in the repository.

A cross national study of population aging and mortality dynamics across X countries, combining demographic analysis, machine learning, and actuarial mathematics built from Human Mortality Database.

I have decided to Omit the SQL implementation in favor a a more simple and streamlined data pipeline.

Work in Progress, adding on to existing research with my own contributions.

Note: This project is under active development. Selected outputs and methodology documentation available. reach out at zmichaelarman@gmail.com or connect on LinkedIn.

<img width="1634" height="887" alt="stability_pyramid_DEU_2019_B" src="https://github.com/user-attachments/assets/06488b85-d90c-467d-ae49-faedc47be196" />

The observed age distribution (blue bars) against its fitted stable-population benchmark (black step line), with a residual panel showing where the population departs from stability (green = surplus, red = deficit). The stability index summarizing those residuals is annotated at the top. This is the visual companion to the project's core metric.

<img width="1184" height="881" alt="pyramid_comparison_regimes" src="https://github.com/user-attachments/assets/75009996-185a-49ed-a9c1-c77c42fc4372" />

Overlaid age structure profiles for three demographic regimes (aging, mid-transition, and youthful) each normalized to population share so the shapes are directly comparable regardless of country size.

<img width="1407" height="881" alt="lexis_log_mx_JPN_B" src="https://github.com/user-attachments/assets/4e7fa0ba-2184-4a3a-8962-bb24498ce06e" />

A Lexis surface of log-mortality over age (vertical) and calendar year (horizontal). It reads four ways at once: the age gradient (rising vertically), secular decline (lightening left→right), period shocks (vertical bands), and birth-cohort effects (45° diagonals; the dashed line marks one cohort).

<img width="1419" height="877" alt="lexis_improvement_JPN_B" src="https://github.com/user-attachments/assets/63ef6911-a7a8-4b31-822d-4b435b602988" />

A Lexis surface of year-over-year mortality improvement on a diverging scale centered at zero (blue = falling, red = rising). Period shocks show up as a red-then-blue vertical pair (the jump and the recovery); cohort effects trace diagonals.

<img width="1256" height="907" alt="heatmap_improvement_country" src="https://github.com/user-attachments/assets/6f8ba139-b5f6-45f2-82fc-e7b26ea34a8b" />

Annual mortality-improvement rate by cause of death (rows) and country (columns), with blue = mortality falling and red = rising. Each cell is labeled with the rate, giving a one-glance cross-national view of which causes are improving, and where.

<img width="1483" height="731" alt="composition_BRA_B" src="https://github.com/user-attachments/assets/b94e99f1-fad7-4699-9ed0-344cb7b9648f" />

A stacked-area chart of the share of deaths by cause over time: the epidemiological transition, with broad causes like cardiovascular and infectious receding as others expand.

## References

Arriaga, E. E. (1984). Measuring and explaining the change in life expectancies. *Demography*, *21*(1), 83–96. https://doi.org/10.2307/2061029

Fernandez, O. E., & Beltrán-Sánchez, H. (2015). The entropy of the life table: A reappraisal. *Theoretical Population Biology*, *104*, 26–45. https://doi.org/10.1016/j.tpb.2015.07.001

Keyfitz, N. (1968). *Introduction to the Mathematics of Population*. Addison-Wesley Publishing Company.

Human Mortality Database. Max Planck Institute for Demographic Research (Germany) and University of California, Berkeley (USA). Available at www.mortality.org.
