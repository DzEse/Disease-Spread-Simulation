# Computational Modeling of Infectious Disease Spread Using the SIR Epidemiological Model

## Project Overview

This project uses the Susceptible-Infected-Recovered (SIR) epidemiological model to simulate the spread of an infectious disease within a population. The model was implemented in Python and solved numerically to examine how infection rates, recovery rates, and vaccination coverage influence disease transmission.

The project demonstrates mathematical modelling, differential equations, scientific computing, and data visualization in a real-world public health context.

## Research Question

How do changes in infection rate, recovery rate, and vaccination coverage affect the size and duration of a disease outbreak in a simulated population?

## Project Objectives

- Implement the SIR epidemiological model in Python.
- Simulate disease spread within a population over time.
- Visualize changes in susceptible, infected, and recovered populations.
- Analyze the effects of infection rate, recovery rate, and vaccination coverage.
- Demonstrate mathematical modelling and scientific computing skills.

## Methodology

The project uses the classical SIR model, which divides a population into three groups:

- **Susceptible (S):** individuals who can become infected.
- **Infected (I):** individuals who currently have the disease and can transmit it.
- **Recovered (R):** individuals who have recovered and are assumed to have immunity.

The model is represented by a system of differential equations and solved numerically using Python.

## Experiments Conducted

1. Baseline SIR simulation
2. Infection rate analysis
3. Recovery rate analysis
4. Vaccination coverage analysis
5. Baseline key metrics calculation

## Key Findings

### Baseline Simulation Results

| Metric | Value |
|---|---:|
| Peak Infected Individuals | 301 |
| Day of Peak Infection | 38 |
| Final Recovered Individuals | 941 |
| Outbreak Duration | 115 days |

### Main Observations

- Higher infection rates produced faster and larger outbreaks.
- Higher recovery rates reduced the number of infected individuals and shortened the outbreak duration.
- Increased vaccination coverage significantly reduced disease transmission and outbreak severity.
- Vaccination had the strongest overall effect on reducing the spread of disease.

## Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Skills Demonstrated

- Mathematical modelling
- Differential equations
- Scientific computing
- Numerical methods
- Data visualization
- Data analysis
- Python programming
- Technical communication

## Repository Structure

```text
Disease-Spread-Simulation/
├── Computational Modeling of Infectious Disease Spread Using the SIR Epidemiological Model.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
└── .gitignore
```

## Future Improvements

Potential extensions include:

- SEIR epidemiological models
- Age-based population groups
- Birth and death rates
- Network-based disease transmission
- Real-world epidemiological datasets

## Author

**Eseosa Iyobosa**  
B.Sc. Mathematics  
Trent University

## License

This project is licensed under the MIT License.
