# Vermont Wastewater Report 2026

A comprehensive Jupyter Book analyzing Vermont's wastewater systems, infrastructure, and environmental impacts.

## Overview

This project provides an in-depth examination of Vermont's wastewater management systems, incorporating GIS analysis, watershed mapping, and environmental resilience studies. The analysis aims to support policy development, infrastructure planning, and environmental protection efforts across the state.

## Report Structure

The report is organized into the following chapters:

1. **Vermont's Wastewater Systems: An Overview** - Introduction to Vermont's wastewater infrastructure
2. **Data Sources and GIS Workflow** - Methodology and data sources
3. **Mapping Wastewater Infrastructure** - Geographic visualization of facilities
4. **Wastewater and Watersheds** - Watershed health and wastewater impacts
5. **Environment Disaster and Wastewater Resilience** - System resilience assessment
6. **Case Study: Lake Champlain Basin** - Detailed basin analysis
7. **Scenario Analysis and Planning Tools** - Future planning tools
8. **Policy Implications and Regulatory Context** - Policy recommendations
9. **Appendix** - Supporting materials and references

## Installation

### Prerequisites

- Python 3.9 or higher
- pip package manager

### Setup

1. Clone this repository:
```bash
git clone https://github.com/VERSO-UVM/Vermont-Wastewater-Report-2026.git
cd Vermont-Wastewater-Report-2026
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Building the Book

To build the Jupyter Book:

```bash
jupyter-book build .
```

The HTML output will be generated in the `_build/html/` directory.

To view the built book locally, open `_build/html/index.html` in your web browser.

## Cleaning Build Files

To clean previous build files:

```bash
jupyter-book clean .
```

To clean and remove all build outputs:

```bash
jupyter-book clean . --all
```

## Project Structure

```
Vermont-Wastewater-Report-2026/
├── _config.yml              # Jupyter Book configuration
├── _toc.yml                 # Table of contents
├── intro.md                 # Introduction page
├── chapters/                # Chapter notebooks
│   ├── 01_overview.ipynb
│   ├── 02_data_sources.ipynb
│   ├── 03_mapping.ipynb
│   ├── 04_watersheds.ipynb
│   ├── 05_resilience.ipynb
│   ├── 06_case_study.ipynb
│   ├── 07_scenario_analysis.ipynb
│   ├── 08_policy.ipynb
│   └── 09_appendix.ipynb
├── data/                    # Data files (not included in repo)
├── references.bib           # Bibliography
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

## Data

Data files should be placed in the `data/` directory. See `data/README.md` for more information about required datasets and sources.

## Contributing

Contributions to improve the analysis and documentation are welcome. Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

See the LICENSE file for details.

## Contact

For questions or additional information about this project, please contact the Vermont Wastewater Analysis Team.

## Acknowledgments

This project uses data from:
- Vermont Department of Environmental Conservation (DEC)
- U.S. Environmental Protection Agency (EPA)
- U.S. Geological Survey (USGS)
- Vermont Center for Geographic Information (VCGI)