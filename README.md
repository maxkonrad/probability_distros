# Probability IZTECH EE

This project provides a web-based tool to visualize and analyze different probability distributions. The tool allows users to select a distribution, specify parameters, generate random variables, and compare sample statistics with theoretical values.

## Features

- Supports Uniform, Gaussian, and Exponential distributions.
- Allows customization of distribution parameters.
- Generates random variables and calculates sample mean and variance.
- Compares sample statistics with theoretical values.
- Visualizes the distribution using a histogram.

## Usage

1. Open `index.html` in a web browser.
2. Select a distribution from the dropdown menu.
3. Enter the desired parameters for the selected distribution.
4. Specify the number of random variables to generate.
5. Click the "Generate" button to see the results.

## Distributions and Parameters

### Uniform Distribution
- `a`: Lower bound
- `b`: Upper bound

### Gaussian Distribution
- `μ`: Mean
- `σ²`: Variance

### Exponential Distribution
- `λ`: Rate parameter (also 1/μ)

## Results

The results section displays the following information:
- Distribution type
- Sample mean
- Sample variance
- Theoretical mean
- Theoretical variance
- Difference between sample and theoretical mean
- Difference between sample and theoretical variance

A histogram is also generated to visualize the distribution of the generated data.

## Dependencies

- [D3.js](https://d3js.org/) for data visualization
