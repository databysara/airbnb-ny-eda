# Here's a list of limitations of the EDA
- The zero values were removed from data that represented the availability of the rental properties i.e. availability_30/60/90/365 in order to examine the relationship between hosts and occupancy.
  - A hypothesis was made that some of the zero values may have been blanks and did not represent full occupancy. This assumption has not been validated and may have skewed the analysis of the data.
- The number of reviews per listing in the data were relatively low (never exceeded 20) which may point to an issue of the validity of the data.
- I have made assumptions about which indicators are leading and which are lagging.
- I have made inferences about what Superhosts know based on the parameters that distinguished Superhosts from regular hosts.
- I used correlation coefficients of above modulus 0.1 to validate correlation.
- There are several trends I saw during the EDA that I couldn’t explain that are not included in the analysis. I may venture to explore these unanswered questions in the future.
- I normalized the rental price for size by dividing rental price by accommodates. Although this relationship is fairly linear in fig 1. it is not perfectly so and my method could have skewed the analysis.
- Pie charts may be easier for the reader to interpret than the histograms presented in figures 7, 8 and 9.
