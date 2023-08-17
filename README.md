# Analysing the Fatality of COVID-19 Cases Based on Acquisition

## Overview

This repository contains an analysis of COVID-19 fatality rates based on different methods of case acquisition. The main goal is to determine whether COVID-19 cases acquired through travel have a higher fatality rate compared to cases acquired through other methods. The analysis employs propensity score matching and logistic regression to investigate this question.

## Data Source

This analysis utilizes the "Confirmed Positive Cases of COVID-19 in Ontario" dataset from the Open Ontario Portal. The dataset provides information on confirmed positive COVID-19 cases in Ontario, including variables such as age group, gender, case acquisition method, and outcome.

## Files in the Repository

1. `Analysing the Fatality of COVID-19 Cases Based on Aquisition.Rmd`: This file contains the source code, narrative text, and visualizations for the COVID-19 fatality analysis.
   
2. `Analysing the Fatality of COVID-19 Cases Based on Aquisitiony.pdf`: This is a PDF document generated from the R Markdown file. It presents a compiled version of the analysis, including text, code, graphs, and conclusions, in a printable and shareable format.

## Conclusion

The analysis results indicate that travel-related COVID-19 cases do not have a higher fatality rate compared to non-travel-related cases. Contrary to the initial hypothesis, the fatality rate is found to be lower for travel-related cases. Propensity score matching and logistic regression were employed for the analysis. It is suggested that the relatively healthier batch of subjects in the travel-related group and the presence of other potentially deadlier acquisition methods in the non-travel-related group could contribute to this unexpected result.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries regarding this analysis, feel free to contact the author, [Chun Ki Yip](mailto:jackyyipchunki@gmail.com).

## References

A list of references used in the analysis, including datasets and R packages, can be found in the references section of the R Markdown document.
