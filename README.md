# Cory McCartan

I am the Hoben and Patricia Thomas and Thomas and Ann Hettmansperger Early Career Professor of Statistics and a faculty affiliate in political science at Penn State University. My research focuses on methodological and applied problems in the social sciences, including elections, legislative redistricting, racial disparities, and missing data.
Read more **[on my website](https://corymccartan.com/)**.

The sections below organize my public projects into a few areas.

## Statistical modeling

**[bases](https://github.com/CoryMcCartan/bases)** is a lightweight R package to create basis expansions of covariates for use in modeling functions. These allow kernel methods, approximate GPs (via random Fourier features), and other nonparametric methods to be used inside other R modeling functions.

**[adjustr](https://github.com/CoryMcCartan/adjustr)** is an R package for efficient Stan model sensitivity analysis using leave-one-out importance sampling.

**[conformalbayes](https://github.com/CoryMcCartan/conformalbayes)** is an R package for finite-sample calibration of predictive intervals for Stan models. 

## Elections and redistricting

**[redist](https://github.com/alarm-redist/redist)** is software written in R and C++ to analyze districting plans with sampling algorithms. The accompanying **[redistmetrics](https://github.com/alarm-redist/redistmetrics)** is specialized for quantifying aspects of plans like compactness, partisan performance, and so on.

**[fifty-states](https://github.com/alarm-redist/fifty-states)** is a comprehensive project to generate public redistricting simulations for congressional districts in all 50 states, for 2010 and 2020.

**[census-2020](https://github.com/alarm-redist/census-2020)** contains Census demographics joined to [VEST](https://election.lab.ufl.edu/) precinct-level vote data for easy use.

**[PL94171](https://github.com/CoryMcCartan/PL94171)** is an R package for downloading and processing the first redistricting data released decennially by the U.S. Census Bureau under P.L. 94-171.

**[harm-redistricting](https://github.com/CoryMcCartan/harm-redistricting)** is replication code for [Individual and Differential Harm in Redistricting](https://osf.io/preprints/socarxiv/nc2x7/), a new set of tools for analyzing effects of districting plans on individuals and groups.

**[midterms-22](https://github.com/CoryMcCartan/midterms-22)** is a dynamic Bayesian model to forecast the 2022 U.S. midterm elections, in collaboration with [Data for Progress](https://www.dataforprogress.org/).

**[president](https://github.com/CoryMcCartan/president)**, **[senate](https://github.com/CoryMcCartan/senate)**, and **[us-house-20](https://github.com/CoryMcCartan/us-house-20)** are dynamic Bayesian models for the 2020 federal elections.

**[dem-primary-20](https://github.com/CoryMcCartan/dem-primary-20)** replicates the analysis I published in the *Washington Post* [on the 2020 presidential primary](https://www.washingtonpost.com/politics/2019/10/23/whos-most-electable-democrat-it-might-be-warren-or-buttigieg-not-biden/).

## Racial disparities and imputation

**[birdie](https://github.com/CoryMcCartan/birdie/)** is an R package that performs BISG, which probabilistically imputes individual race from surnames and addresses. More importantly, **birdie** allows for statistically valid estimates of racial disparities (generally, of a conditional mean of some outcome variable by race) using the BISG probabilities.
Paper replication code is available in [birdie-replication](https://github.com/CoryMcCartan/birdie-replication).

**[seine](https://github.com/CoryMcCartan/seine)** is an R package for ecological inference, where individual relationships (commonly, vote by race) are estimated from aggregate data.

## Census data

**[easycensus](https://github.com/CoryMcCartan/easycensus)** is an R package for finding Census variables to download, downloading Census data in a clean format, and labeling and tidying the results.

**[PL94171](https://github.com/CoryMcCartan/PL94171)** is an R package for downloading and processing the first redistricting data released decennially by the U.S. Census Bureau under P.L. 94-171.

**[blockpop](https://github.com/CoryMcCartan/blockpop)** is an R package for working with FCC block-level population estimates, which are based on new roads and map data, along with decennial Census and ACS data.

**[tinytiger](https://github.com/alarm-redist/tinytiger)** is a lightweight alternative to the **tigris** package for downloading TIGER/Line shapefiles from the Census.

## Tools for research and writing

**[wacolors](https://github.com/CoryMcCartan/wacolors)** is a set of colorblind-friendly palettes, both discrete and continuous.

**[legal](https://github.com/CoryMcCartan/legal)** is a Quarto template (via LaTeX) for legal filings and expert reports.

**[science](https://github.com/CoryMcCartan/science)** is a Quarto template for *Science* journals.

**[cmc-article](https://github.com/CoryMcCartan/cmc-article)** is a lightweight Quarto template for scientific papers.
