# Mean Field Approximation Simulation Software

**Mean Field Approximation Simulation Software** is a comprehensive tool designed to help physicists and material scientists simulate the Mean Field Approximation in various magnetic systems. This software provides a user-friendly interface to study phase transitions, material properties, and thermodynamic behaviors through customizable simulations.

## Real-Time Simulations
[![Watch the video](https://img.youtube.com/vi/u2iI6KBrinQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=u2iI6KBrinQ)

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

1. Download the latest version from the [releases](https://github.com/AmineSlimani/Mean-Field-Simulation-Software) page.
2. Downloaded .exe file.
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

## Installing GCC on Windows

in programming option choice there are two choice : Python(Numpy) and C , if you're going to use C for the simulation you have to do the next steps :

### Step 1: Install MinGW
- Download the MinGW installer from [MinGW SourceForge](https://sourceforge.net/projects/mingw/).
- Run the installer and during the installation, make sure to select the `gcc-g++` component for C/C++ support.
- 
### Step 2: Add MinGW to the System Path
- After installation, go to **Control Panel > System > Advanced system settings > Environment Variables**.
- In the **System Variables** section, find **Path**, click **Edit**, and add the path to the **MinGW bin** directory (usually `C:\MinGW\bin`).

### Step 3: Verify Installation
- Open **Command Prompt** and type the following command to ensure GCC is installed correctly:

    ```bash
    gcc --version
    ```

If installed correctly, this will display the GCC version and confirm that you're ready to compile C/C++ files.


## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue on the [issue tracker](https://github.com/AmineSlimani/Mean-Field-Simulation-Software/issues).

By Amine Slimani 
Email : amineslimani3011@gmail.com

