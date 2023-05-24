
<!-- README.md is generated from README.Rmd. Please edit that file -->

# <span style="color:#0097AD; font-weight:bold">BIO-WELL</span>

<span style="color:#004A86; font-weight:bold">Introducing `BIOWELL`: An
R package that empowers researchers and practitioners to effortlessly
create and share customized surveys using the BIO-WELL scale</span>.

The BIO-WELL scale is an important tool for assessing the **contribution
of biodiversity to human wellbeing**.It was developed to address the
limited understanding of how interactions with nature and biodiversity
impact our health and wellbeing.

With the `BIOWELL` package, you have the flexibility to **design surveys
tailored to your specific research needs**.

This **user-friendly** package provides a range of functions and tools
to **streamline the survey creation process**, ensuring a seamless and
efficient workflow.

# <span style="color:#0097AD; font-weight:bold">What is the BIO-WELL scale?</span>

BIO-WELL is a reliable and validated scale that links biodiversity to
human wellbeing. It incorporates multi-sensory attributes of
biodiversity and ecological metrics. Five studies, involving 2962
participants, detail its development, validation, and psychometric
properties (Irvine et al., 2023). BIO-WELL provides a valuable tool for
researchers and decision-makers to understand the
biodiversity-health/wellbeing relationship and evaluate interventions.

<a href='https://github.com/r-a-dobson/BIO-WELL'><img src="https://raw.githubusercontent.com/r-a-dobson/BIO-WELL/main/data/BIOWELL_SCALE.jpg" align="centre" height="300"/></a>

**Read more about the development and application of BIO-WELL in:**

<span style="color:#004A86">*Irvine, K.N., Fisher, J.C., Bentley, P.R.,
Nawrath, M., Dallimer, M., Austen, G.E., Fish, R. and Davies, Z.G.,
2023. BIO-WELL: The development and validation of a human wellbeing
scale that measures responses to biodiversity. Journal of Environmental
Psychology, 85, p.101921.*</span>

## <span style="color:#0097AD; font-weight:bold">Benefits of BIO-WELL </span>

- Include stem questions that specifically ask participants to consider
  their wellbeing in relation to <span
  style="color:#004A86; font-weight:bold">different elements of
  biodiversity</span>, such as species diversity, ecological processes,
  and attributes like sounds.

- Captures the <span style="color:#004A86; font-weight:bold">holistic
  experience of biodiversity</span> by situating participants within a
  natural environment and incorporates a biopsychosocial-spiritual model
  of wellbeing, including <span
  style="color:#004A86; font-weight:bold">physical, emotional,
  cognitive, social, and spiritual domains of wellbeing</span>

- Combines measures of the environment and wellbeing into a <span
  style="color:#004A86; font-weight:bold">single scale</span>

- Applicable to <span style="color:#004A86; font-weight:bold">diverse
  research settings</span>, including scenario-based studies, in situ
  evaluations, and studies that incorporate measures of actual and
  perceived biodiversity.

- The scale’s qualitative underpinning and strong psychometric
  properties make it a <span
  style="color:#004A86; font-weight:bold">reliable and valid
  instrument</span>.

- It has been developed with input from the target population and <span
  style="color:#004A86; font-weight:bold">minimizes participant
  burden</span> by using a small number of response items.

# <span style="color:#0097AD; font-weight:bold">Package features </span>

1)  <span style="color:#004A86; font-weight:bold">Customization</span>:
    Adapt the scale to diverse research settings and environments.
    Whether you’re studying woodlands, wetlands, urban parks, or other
    ecological contexts, the `BIO-WELL` package allows for easy
    modification of stem questions and attributes to suit the specific
    environment under investigation.

2)  <span style="color:#004A86; font-weight:bold">Validity and
    Reliability</span>: Leverage the strength of the BIO-WELL scale,
    which has undergone rigorous validation and psychometric evaluation
    in previous studies. Benefit from a robust measurement tool that
    ensures the quality of data collected through your custom surveys.

3)  <span style="color:#004A86; font-weight:bold">Seamless
    Integration</span>: The `BIO-WELL` package seamlessly integrates
    with the R statistical programming environment, offering a familiar
    and efficient platform for survey design and analysis.

    - Effortlessly upload your BIO-WELL surveys to the free **Shiny
      Server** to share surveys with participants online.
    - Integrated free cloud storage on **Dropbox** for your survey
      response data.
    - Harness the power of **R’s extensive packages** to analyze and
      interpret your survey data.

4)  <span style="color:#004A86; font-weight:bold">Documentation and
    Support</span>: The package comes with comprehensive documentation,
    including user guides and examples, to assist you in utilising the
    `BIO-WELL` package to its full potential. Additionally, a dedicated
    support team is available to address any inquiries or technical
    challenges you may encounter.

# <span style="color:#0097AD; font-weight:bold">Get started! </span>

Unlock the potential of the BIO-WELL scale and revolutionize your
research on biodiversity and human wellbeing with the BIO-WELL Survey
Generator. Empower yourself to create custom surveys that provide
valuable insights into the intricate relationship between biodiversity
and various dimensions of human health and wellbeing.

Install the `BIOWELL` package by running the line below!

``` r
devtools::install_github("r-a-dobson/BIO-WELL")
```

There are six key stages (and associated functions) in the BIOWELL
package:

1)  <span style="color:#004A86; font-weight:bold">Activate
    Dropbox</span> - Set-up cloud storage for survey response data
    (`activate_dropbox()`).

2)  <span style="color:#004A86; font-weight:bold">Build survey</span> -
    Develop your custom BIO-WELL survey from start to finish
    (`build_survey()`).

3)  <span style="color:#004A86; font-weight:bold">Create URL</span> -
    Upload your survey to the Shiny Servers and obtain survey access
    link to share with participants (`create_URL()`).

4)  <span style="color:#004A86; font-weight:bold">Download data</span> -
    Download and combine responses from survey participants into R
    (`download_data()`).

5)  <span style="color:#004A86; font-weight:bold">Evaluate
    survey</span> - Calculate key statistics including Cronbach’s Alpha
    and Item-Total (`evaluate_survey()`).

6)  <span style="color:#004A86; font-weight:bold">Explore
    patterns</span> - Generate plots of BIO-WELL scores across BIO-WELL
    environments and stem questions (`explore_data()`).

## <span style="color:#0097AD; font-weight:bold">Need help learning the BIOWELL package functions? </span>

Try our package vignettes that guide you through the stages from
building custom BIO-WELL surveys to analysing survey response data!
