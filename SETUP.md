# SETUP

## Configure environment
```sh
# Create Environment
conda create -n face-similarity python=3.6
conda activate face-similarity

# Install Requirements
pip install tensorflow==1.11.0
pip install matplotlib
pip install opencv-python==4.1.0.25

# Prepare IpyKernel for VS Code
conda install -n face-similarity ipykernel --update-deps --force-reinstall
```

## Use VS Code GUI
1. Install Visual Studio Code
2. Open the Git folder in VS Code
3. Open `inference.ipynb`
4. Select the Kernel from Python Environments - use the environment `face-similarity`
5. Change paths in the last cell unde `# Fill with yout own paths`
6. Run all cells
