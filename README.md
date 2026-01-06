
# Quantifying "Mama Africa": The Miriam Makeba Cultural Impact Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Research%20Prototype-green)
![License](https://img.shields.io/badge/License-MIT-purple)
![Domain](https://img.shields.io/badge/Domain-Digital%20Humanities-orange)

## 📋 Overview

This project implements a rigorous mathematical framework to quantify the cultural, political, and musical impact of **Miriam Makeba** (1932–2008). By moving beyond qualitative biography, this codebase utilizes **Network Theory**, **Information Theory**, **Stochastic Modeling**, and **Bayesian Statistics** to empirically validate historical hypotheses regarding her role as a global civil rights icon.

The system simulates and analyzes data across four distinct career phases:
1.  **Early/Traditional** (1954–1958)
2.  **US Commercial** (1959–1967)
3.  **Political Exile** (1968–1978)
4.  **Return/Global** (1979–1999)

## 🔬 Scientific Methodology

The codebase is built upon several advanced analytical modules:

### 1. Structural Brokerage (Network Theory)
We utilize `networkx` to model Makeba's position within global artist-activist networks.
*   **Metric:** Betweenness Centrality.
*   **Hypothesis:** Makeba acted as a "structural broker" connecting disparte clusters (e.g., US Civil Rights, Pan-Africanism, Global Pop).

### 2. Lyrical Entropy (Information Theory)
We apply Shannon Entropy to analyze lyrical complexity and resistance to assimilation.
*   **Metric:** Information Fidelity & KL Divergence.
*   **Finding:** High-entropy signals (politicized lyrics) showed higher resistance to commercial dilution during the Exile phase.

### 3. Cultural Diffusion (Epidemiology)
We employ **SIR (Susceptible-Infected-Recovered)** differential equations to model the spread of "Makeba-mania" and anti-apartheid sentiment.
*   **Metric:** Basic Reproduction Number ($R_0$).

### 4. The Makeba Soft Power Index (MSPI)
A custom composite index calculated over time ($t$):
$$MSPI(t) = 0.4(C_a) + 0.3(D_r) + 0.3(P_a)$$
Where $C_a$ is Cultural Appeal, $D_r$ is Diplomatic Reach, and $P_a$ is Political Alignment.

## ⚙️ Installation

### Prerequisites
*   Python 3.8 or higher
*   Scientific Python Stack

### Dependencies
Create a `requirements.txt` file or install directly:

```bash
pip install numpy pandas matplotlib networkx scipy
```

## 🚀 Usage

The entire analysis pipeline is contained within a single execution script. To run the empirical analysis, generate figures, and output the report:

```bash
python makeba_analysis.py
```

*(Note: Replace `makeba_analysis.py` with the actual name of your script file)*

## 📊 Outputs & Visualizations

The script automatically generates high-resolution (300 DPI) figures and data exports:

### Generated Figures
1.  **Figure 1: Musical Evolution** - Bar charts comparing Tempo, Vocal Range, and Lyrical Entropy across career phases.
2.  **Figure 2: Network Analysis** - Graph visualization of collaborations and centrality metrics over time.
3.  **Figure 3: Soft Power Dynamics** - SIR diffusion models and MSPI time-series data.
4.  **Figure 4: Mathematical Proofs** - Statistical significance testing and effect size analysis.
5.  **Figure 5: Empirical Validation** - Monte Carlo simulation results and Bootstrap confidence intervals.
6.  **Supplementary Figure** - A career timeline combined with a comparative radar chart.

### Data Exports
*   `makeba_analysis_results.json`: Complete dataset containing simulation results, p-values, and raw metrics.
*   **Console Report**: A summary of hypothesis tests (t-statistics, Cohen's d) printed to stdout.
*   **LaTeX Tables**: The script generates LaTeX code blocks for "Musical Features" and "Statistical Significance" ready for copy-pasting into academic papers.

## 📂 Project Structure

```text
.
├── makeba_analysis.py         # Main execution script
├── README.md                  # Project documentation
├── requirements.txt           # Dependencies
└── output/                    # Generated upon execution
    ├── Figure1_Musical_Evolution.png
    ├── Figure2_Network_Analysis.png
    ├── ...
    └── makeba_analysis_results.json
```

## 🧠 Code Architecture

*   **`MakebaAnalytics`**: Static methods for robust math/stats calculations.
*   **`EmpiricalDataCollector`**: Simulates data retrieval (Lyrics, Audio Features, Wikipedia timelines).
*   **`EmpiricalValidator`**: Handles Bootstrap CIs, Bayesian A/B testing, and Time Series stationarity tests.
*   **`EnhancedMakebaAnalytics`**: Extends the core class with Information Theory and Cultural Diffusion metrics.
*   **`MakebaResearchPipeline`**: The controller class that orchestrates the data flow from collection to reporting.

## 🤝 Contributing

This project is open for collaboration, particularly from researchers in:
*   Computational Musicology
*   African History
*   Network Science

Please submit a Pull Request or open an Issue to discuss methodology changes.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
*Analysis generated on: Wednesday, January 7, 2026*
*Location: South Africa*
