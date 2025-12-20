# Quantum Computing with Qiskit

This repository contains Jupyter notebooks demonstrating quantum computing concepts using IBM's Qiskit framework, including quantum circuit simulation, cat state generation, and quantum algorithm implementations.

## Prerequisites

Before you begin, you'll need:
- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system
- [Visual Studio Code](https://code.visualstudio.com/) (recommended) - a free code editor with excellent Jupyter notebook support
- Basic familiarity with using the command line/terminal (or follow the VS Code instructions below)

## Getting Started

### Step 1: Download the Repository

Choose one of the following methods:

#### Option A: Download ZIP (Recommended for Beginners)
1. On this GitHub page, click the green **"Code"** button (top right of the file list)
2. Select **"Download ZIP"**
3. Extract the ZIP file to a location you'll remember (e.g., your Desktop or Documents folder)
4. Note the folder location - you'll need it in the next step

#### Option B: Clone with Git
If you have Git installed and want to receive updates easily:
```bash
git clone https://github.com/Bendahboy/Qiskit-Basics-Running-Circuits-on-Simulators-and-IBM-Quantum-Hardware.git
```
---

## Setup Method Using VS Code (Recommended)

This method is ideal for beginners and provides the best experience for working with Jupyter notebooks.

### Step 1: Open the Folder in VS Code

1. Launch **Visual Studio Code**
2. Click **File** → **Open Folder** (or press `Ctrl+K Ctrl+O`)
3. Navigate to and select the folder where you downloaded/extracted this repository
4. Click **Select Folder**

### Step 2: Install Required VS Code Extensions

When you first open the folder, VS Code may prompt you to install recommended extensions. Click **Install** if prompted.

If not prompted, manually install these extensions:
1. Click the **Extensions** icon in the left sidebar (or press `Ctrl+Shift+X`)
2. Search for and install:
   - **Python** (by Microsoft)
   - **Jupyter** (by Microsoft)

### Step 3: Open the Integrated Terminal

1. Click **Terminal** → **New Terminal** (The Terminal option may be hidden if opening on a laptop, but can be found in the ... at the top bar of the screen)
2. A terminal panel will open at the bottom of VS Code
3. Make sure to open the Command Prompt by selecting it from the arrow dropdown next to the + sign

**Note:** If you have Anaconda installed, the terminal should automatically detect it. You'll see `(base)` at the start of your command prompt.

### Step 4: Create the Conda Environment

In the VS Code terminal at the bottom, type:

```bash
conda env create -f environment.yml
```

Press Enter and wait for the installation to complete.

### Step 5: Select the Python Interpreter

1. Press `Ctrl+Shift+P` to open the Command Palette
2. Type **"Python: Select Interpreter"** and select it
3. Choose **"Quantum"** from the list of conda environments
   - If you don't see it, click the refresh icon or restart VS Code

### Step 6: Open and Run Notebooks

1. In the **Explorer** panel (left sidebar), click on any `.ipynb` file
2. The notebook will open directly in VS Code
3. Click **"Select Kernel"** in the top right if prompted
4. Choose the **"Quantum"** environment
5. Run cells by clicking the **▶ Play** button next to each cell, or press `Shift+Enter`



### Available Notebooks

- **Defining and Simulating Quantum Circuit.ipynb** - Basic quantum circuit simulation and measurement analysis
- **Cat Generator With Explanations.ipynb** - Demonstrates quantum entanglement through cat state generation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
