# Mean Field Approximation Simulation Software

**Mean Field Approximation Simulation Software** is a comprehensive tool designed to help physicists and material scientists simulate the Mean Field Approximation in various magnetic systems. This software provides a user-friendly interface to study phase transitions, material properties, and thermodynamic behaviors through customizable simulations.

## Key Features

- **Customizable Parameters**: Modify key parameters including:
  - Spin (\( S \))
  - Temperature range
  - Type of magnetism (e.g., ferromagnetism)
  - Coupling constant (\( J \))
  - Convergence conditions
- **Real-Time Data Visualization**: Instantly visualize key thermodynamic properties like:
  - Magnetization \( M(T) \)
  - Susceptibility \( X(T) \)
  - Heat capacity \( C_v(T) \)
- **Automatic Code Generation**: Export simulation results into C and Python (NumPy) code for further analysis or integration into larger projects.
- **Graphical User Interface (GUI)**: Easy-to-use GUI for effortless simulation setup.
- **Support for Multiple Physical Models**: Adapt the simulation for different material contexts and magnetic systems.

## Installation

To run the software, follow these steps:

1. Download the latest version from the [releases](https://github.com/AmineSlimani/Mean-Field-Simulation-Software/releases) page.
2. Extract the contents of the downloaded zip file.
3. Double-click the `.exe` file to launch the software.

**System Requirements:**
- **Operating System**: Windows
- **Minimum Requirements**: Standard Windows machine with sufficient resources to run simulations.

## How to Use

1. Launch the software by running the `.exe` file.
2. Enter your desired parameters (e.g., spin, temperature, coupling constants).
3. Click "Run Simulation" to view real-time thermodynamic properties and visualizations.
4. Export the simulation data or generated code for further analysis.

## Dependencies

The executable comes bundled with all required dependencies. If you are using the source code version, you need to have:

- Python 3.x
- NumPy
- Matplotlib

You can install dependencies using:
```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue on the [issue tracker](https://github.com/AmineSlimani/Mean-Field-Simulation-Software/issues).
