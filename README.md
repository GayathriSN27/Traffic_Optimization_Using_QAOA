# Project Overview

This project utilizes quantum-classical hybrid algorithms, primarily QAOA, to optimize traffic congestion and green-light timings via quantum circuits. It lays the foundation for large-scale traffic optimization with potential for additional constraints or machine learning integration. Currently, it functions solely as a data optimization tool.


## Features

- **Traffic Flow Analysis**: Processes real-time or predefined traffic congestion data.

- **Quantum Optimization**: Uses QAOA to optimize traffic signal timings.

- **User-Friendly Interface**: Built using Streamlit for easy interaction and visualization.

- **Dynamic Traffic Signal Adjustments**: Computes optimized green-light durations based on quantum simulations.


## Installation

Ensure you have Python installed, then install the required dependencies:
```python
 pip install streamlit cirq numpy scipy sympy
```
## How to Run

- Navigate to the project directory.

- Run the Streamlit app:
```python
 streamlit run app.py
```

- Use the web interface to view traffic data, optimize congestion, and compute improved green-light timings.

## License

This project is licensed under [MIT](https://choosealicense.com/licenses/mit/) license.
