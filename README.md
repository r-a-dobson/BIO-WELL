
<!-- README.md is generated from README.Rmd. Please edit that file -->

# **BIO-WELL**

<!-- badges: start -->

[![License](https://img.shields.io/badge/license-GPL%20%28%3E=%203%29-lightgrey.svg?style=flat)](http://www.gnu.org/licenses/gpl-3.0.html)
[![Codecov test
coverage](https://codecov.io/gh/r-a-dobson/BIOWELL/branch/main/graph/badge.svg)](https://app.codecov.io/gh/r-a-dobson/BIOWELL?branch=main)
[![R-CMD-check](https://github.com/r-a-dobson/BIOWELL/workflows/R-CMD-check/badge.svg)](https://github.com/r-a-dobson/BIOWELL/actions)
[![DOI](https://img.shields.io/badge/DOI-10.1016/j.jenvp.2022.101921-green.svg)](https://doi.org/10.1016/j.jenvp.2022.101921)

<!-- badges: end -->

**Introducing `BIOWELL`: An R package for effortlessly creating and
sharing customized surveys that include the BIO-WELL scale**.

The BIO-WELL scale is an important tool for assessing the **contribution
of biodiversity to human wellbeing**. The scale was developed to address
the limited understanding of how interactions with nature and
biodiversity impact our health and wellbeing.

With the `BIOWELL` package, you have the flexibility to **design surveys
tailored to your specific research needs**.

This **user-friendly** package provides a range of functions that
**streamline the survey development process**.

# **What is the BIO-WELL scale?**

BIO-WELL is a reliable and validated scale that links biodiversity to
human wellbeing. It incorporates multi-sensory attributes of
biodiversity and ecological metrics. Five studies, involving 2962
participants, detail its development, validation, and psychometric
properties (Irvine et al., 2023).

BIO-WELL provides a **valuable tool for researchers and
decision-makers** to understand the biodiversity-health/wellbeing
relationship and evaluate interventions.

<a href='https://github.com/r-a-dobson/BIO-WELL'><img src="https://raw.githubusercontent.com/r-a-dobson/BIO-WELL/main/man/V2/V2_0.png" align="centre" height="650" width = "100%"/></a>

**Read more about the development and application of BIO-WELL in:**

<span style="color:#004A86">*Irvine, K.N., Fisher, J.C., Bentley, P.R.,
Nawrath, M., Dallimer, M., Austen, G.E., Fish, R. and Davies, Z.G.,
2023. BIO-WELL: The development and validation of a human wellbeing
scale that measures responses to biodiversity. Journal of Environmental
Psychology, 85, p.101921.*

## Benefits of BIO-WELL

- Include stem questions that specifically ask participants to consider
  their wellbeing in relation to **different elements of biodiversity**,
  such as species diversity, ecological processes, and attributes like
  sounds.

- Captures the **holistic experience of biodiversity** by situating
  participants within a natural environment and incorporates a
  biopsychosocial-spiritual model of wellbeing, including **physical,
  emotional, cognitive, social, and spiritual domains of wellbeing**

- Combines measures of the environment and wellbeing into a **single
  scale** ranging from 0 to 100.

- Applicable to **diverse research settings**, including scenario-based
  studies, in situ evaluations, and studies that incorporate measures of
  actual and perceived biodiversity.

- The scale’s qualitative underpinning and strong psychometric
  properties make it a **reliable and valid instrument**.

- It has been developed with input from the target population and
  **minimizes participant burden** by using a small number of response
  items.

# Package features

1)  **Customization**: Adapt the scale to diverse research settings and
    environments. Whether you’re studying woodlands, wetlands, urban
    parks, or other ecological contexts, the `BIO-WELL` package allows
    for easy modification of stem questions and attributes to suit the
    specific environment under investigation.

2)  **Validity and Reliability**: Leverage the strength of the BIO-WELL
    scale, which has undergone rigorous validation and psychometric
    evaluation in previous studies. Benefit from a robust measurement
    tool that ensures the quality of data collected through your custom
    surveys.

3)  **Seamless Integration**: The `BIO-WELL` package integrates the R
    statistical programming environment, offering a familiar platform
    for survey design and analysis.

    - Upload your BIO-WELL surveys to the free **Shiny Server** for
      sharing surveys via URL.

    - Utilises free cloud storage on **Dropbox** for survey response
      data.

    - Take advantage of **R’s extensive packages** to analyse your
      survey response data.

4)  **Documentation**: The package comes with comprehensive
    documentation, including Vignette tutorials and function examples,
    to assist you in utilising the `BIO-WELL` package to its full
    potential.

# Get started!

Install the `BIOWELL` package by running the line below!

``` r
devtools::install_github("r-a-dobson/BIO-WELL")
```

There are six key stages (and associated functions) in the BIOWELL
package:

1)  **Activate Dropbox** - Set-up cloud storage for survey response data
    with `activate_dropbox()`.

2)  **Build survey** - Develop your custom BIO-WELL survey from start to
    finish with `build_survey()`.

3)  **Create URL** - Upload your survey to the Shiny Servers and obtain
    survey access link to share with participants with `create_URL()`.

4)  **Download data** - Download and combine responses from survey
    participants into R with `download_data()`.

5)  **Evaluate survey** - Calculate key statistics including Cronbach’s
    Alpha and Item-Total with `evaluate_survey()`.

6)  **Explore patterns** - Generate plots of BIO-WELL scores across
    environments and stem questions with `explore_data()`.

<a href='https://github.com/r-a-dobson/BIO-WELL'><img src="https://raw.githubusercontent.com/r-a-dobson/BIO-WELL/main/man/V2/bw_framework.png" align="centre" height="800" width = "100%"/></a>

## Need help learning the BIOWELL package functions?

For more details, see the package manual
[here](https://github.com/r-a-dobson/BIOWELL/blob/main/man/manual/BIOWELL_1.0.pdf)
for more details on each function.

Try our package vignettes that guide you through the stages from
building custom BIO-WELL surveys to analysing survey response data!

If you encounter an error or bug when installing and using BIOWELL,
please post a comment
[here](https://github.com/r-a-dobson/BIOWELL/issues) for guidance and
support from us.
