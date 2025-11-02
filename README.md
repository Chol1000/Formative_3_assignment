# Formative 3 Assignment: Probability Distributions, Bayesian Probability, and Gradient Descent Implementation

## Overview

This project implements key concepts in probability theory and machine learning, including probability distributions, Bayesian probability, and gradient descent optimization. The assignment demonstrates both theoretical understanding and practical implementation skills.

## Project Structure

```
Formative_3_assignment/
├── README.md                    # This file
├── main_notebook_.ipynb         # Main Jupyter notebook with all implementations
├── Part3_Manual_Calculations.pdf # Manual gradient descent calculations
├── data/                        # Dataset directory
│   ├── StudentsPerformance.csv  # Student performance dataset
│   └── IMDB Dataset.csv         # IMDB movie reviews dataset
└── figures/                     # Generated visualizations
    ├── part1_3d_surface.png     # 3D visualization of bivariate normal distribution
    ├── part1_contour_plot.png   # Contour plot of bivariate normal distribution
    ├── part2_bayes_probabilities.png # Bayesian analysis results
    ├── part4_error_over_iterations.png # Gradient descent error visualization
    └── part4_parameters_over_iterations.png # Parameter evolution visualization
```

## Assignment Components

### Part 1: Probability Distributions

**Objective**: Implement and visualize bivariate normal distribution from scratch.

**Implementation**:
- Used the Students Performance dataset (math and reading scores)
- Calculated statistical parameters (mean, standard deviation, covariance, correlation)
- Implemented bivariate normal PDF formula without statistical libraries
- Created both 2D contour plots and 3D surface visualizations

**Key Features**:
- From-scratch implementation of bivariate normal distribution
- Statistical analysis of real-world data
- Multiple visualization approaches for comprehensive understanding

### Part 2: Bayesian Probability

**Objective**: Apply Bayesian theorem to sentiment analysis using IMDB movie reviews.

**Implementation**:
- Selected keywords indicating positive and negative sentiment
- Calculated prior, likelihood, marginal, and posterior probabilities
- Implemented Bayes' theorem using basic Python operations only
- Created visualizations showing probability distributions

**Key Calculations**:
- Prior: P(Positive)
- Likelihood: P(keyword|Positive)
- Marginal: P(keyword)
- Posterior: P(Positive|keyword)

### Part 3: Manual Gradient Descent Calculations

**Objective**: Perform manual gradient descent calculations for linear regression.

**Implementation**:
- Manual computation of three gradient descent iterations
- Derivation of cost function gradients using Mean Squared Error (MSE)
- Step-by-step calculation documentation in PDF format
- Analysis of parameter convergence trends

**Parameters**:
- Initial m = 0, b = 0
- Learning rate α = 0.01
- Data points: (1, 2) and (2, 3)

### Part 4: Gradient Descent Implementation

**Objective**: Convert manual calculations into Python code using SciPy.

**Implementation**:
- Python implementation of gradient descent algorithm
- Parameter update visualization over iterations
- Error reduction tracking and visualization
- Comparison with manual calculations for verification

**Visualizations**:
- Parameter evolution (m and b) over iterations
- Cost function reduction over time
- Final model predictions vs actual data

## Technical Requirements Met

### Academic Integrity
- All implementations are original work
- AI tools used only for concept clarification, not solution generation
- Each step explained and documented thoroughly

### Programming Standards
- Modular code following DRY (Don't Repeat Yourself) principle
- Clear documentation and comments
- Efficient algorithms without excessive abstraction
- Proper error handling and validation

### Mathematical Rigor
- From-scratch implementations without relying on statistical libraries
- Detailed mathematical derivations included
- Step-by-step calculation documentation
- Verification of results through multiple approaches

## Key Results

### Bivariate Normal Distribution
- Successfully modeled math and reading scores relationship
- Correlation coefficient: 0.8176 (strong positive correlation)
- Clear visualization of probability density across score ranges

### Bayesian Analysis
- Effective sentiment classification using keyword analysis
- Demonstrated practical application of Bayes' theorem
- Quantified uncertainty in sentiment predictions

### Gradient Descent
- Successful convergence to optimal parameters
- Demonstrated understanding of optimization principles
- Clear visualization of learning process

## Dependencies

- Python 3.x
- NumPy (for numerical computations)
- Pandas (for data manipulation)
- Matplotlib (for visualizations)
- Jupyter Notebook (for interactive development)

## Usage

1. **Setup Environment**:
   ```bash
   pip install numpy pandas matplotlib jupyter
   ```

2. **Run Analysis**:
   ```bash
   jupyter notebook main_notebook_.ipynb
   ```

3. **View Results**:
   - Open the Jupyter notebook for interactive exploration
   - Check the `figures/` directory for generated visualizations
   - Review `Part3_Manual_Calculations.pdf` for manual calculations

## Data Sources

- **Students Performance Dataset**: Academic performance data including math and reading scores
- **IMDB Dataset**: Movie reviews with sentiment labels for Bayesian analysis

## Learning Outcomes

This project demonstrates:
- Deep understanding of probability theory and statistical distributions
- Practical application of Bayesian inference
- Implementation of optimization algorithms from first principles
- Data visualization and interpretation skills
- Mathematical modeling of real-world phenomena

## Author

This project was completed as part of the Formative 3 assignment, demonstrating comprehensive understanding of probability theory, Bayesian statistics, and optimization algorithms through both theoretical analysis and practical implementation.

---

*Note: This project emphasizes understanding fundamental concepts through implementation rather than using pre-built libraries, providing deeper insight into the mathematical foundations of machine learning and statistics.*
