# Public perception of scientific work: Statistical Inference and Sampling Distributions Analysis

## Overview
This project explores the foundations of statistical inference through sampling distributions, focusing on analyzing public perception of scientific work's benefits using simulated Gallup poll data. The analysis demonstrates how sample statistics can serve as point estimates for population parameters and investigates the properties of sampling distributions.

## Key Features
- Creation and analysis of sampling distributions
- Investigation of sample size effects on estimation accuracy
- Visualization of sampling distributions using ggplot2
- Exploration of the Central Limit Theorem in practice
- Comparison of different sample sizes and their impacts on estimation precision

## Technologies Used
- R Programming Language
- Libraries:
  - tidyverse (for data manipulation and visualization)
  - openintro (for datasets)
  - infer (for resampling)
  - dplyr (for data manipulation)
  - tinytex (for PDF document generation)

## Project Structure
The project is organized as an R Markdown document containing:
- Initial data setup and population creation
- Multiple sampling experiments
- Visualization of sampling distributions
- Analysis of sample size effects
- Comparative analysis of different sampling approaches

## Key Findings
1. Population Parameter Estimation:
   - Successfully estimated the true population proportion of 20% (people who don't believe scientific work benefits them)
   - Demonstrated how sample size affects estimation accuracy

2. Sampling Distribution Properties:
   - Showed how larger sample sizes lead to more precise estimates
   - Illustrated the normal approximation of sampling distributions
   - Demonstrated reduced variability with increased sample size

3. Sample Size Effects:
   - Compared samples of sizes 15, 50, and 150
   - Documented the relationship between sample size and standard error
   - Illustrated practical implications of the Central Limit Theorem

## Getting Started

### Prerequisites
- R (version 4.0 or higher recommended)
- RStudio (for R Markdown compilation)
- Required R packages listed above

### Installation
```R
# Install required packages
install.packages(c("tidyverse", "openintro", "infer", "dplyr", "tinytex"))
```

### Usage
1. Clone the repository
2. Open the R Markdown file in RStudio
3. Install required packages if not already installed
4. Run the entire document or individual chunks as needed

## Reproducibility
The analysis uses set.seed(12124) for reproducibility. All random sampling can be replicated exactly by using this seed value.

## Data Description
The project uses simulated data based on a 2019 Gallup report about public perception of scientific work's benefits. The population consists of 100,000 simulated responses, with:
- 80,000 responses indicating "Benefits"
- 20,000 responses indicating "Doesn't benefit"

## Visualizations
The project includes multiple visualizations:
- Population distribution bar plots
- Sample distribution histograms
- Sampling distribution plots for various sample sizes
- Comparative visualization of different sampling approaches

## Results and Conclusions
1. The study effectively demonstrates how sample statistics can estimate population parameters
2. Larger sample sizes (n=150) provide more reliable estimates than smaller ones (n=15)
3. The sampling distribution becomes more normal and less variable as sample size increases
4. Point estimates become more precise with larger sample sizes

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Based on Gallup report data from 2019
- Inspired by statistical inference educational materials
- Built using R and the tidyverse ecosystem

## Contact Emmanuel
For questions or feedback about this project, please open an issue in the repository.
- ![cf3295c1-d301-4990-b9d4-265225b43cb5](https://github.com/user-attachments/assets/1cb35e99-201a-438d-83f3-c7f69021748b)
![b721c6ae-043d-49d1-b106-527c9a71a8a2](https://github.com/user-attachments/assets/0b0574aa-89c9-4fdb-86aa-3a501e32224b)
![860f308c-6b40-4d4d-bf87-b129e3f79a40](https://github.com/user-attachments/assets/44b71c96-505d-4f76-b7aa-f5d5eb7b8e10)
![dce09023-0491-499c-b747-346a074a7ce4](https://github.com/user-attachments/assets/dbfaf0b1-7472-41fd-8898-90181af529a4)
![8f31ebf6-b74d-4410-8a01-6cf00583c726](https://github.com/user-attachments/assets/a5d47ea7-1aff-4f13-b372-c8ab2dacebb5)
![Screenshot from 2025-02-18 21-34-59](https://github.com/user-attachments/assets/767392ac-a101-4375-96d3-363e23fb7ee5)
