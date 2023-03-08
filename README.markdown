# New York City Energy Consumption

# Steps for FBProphet installation:

1. Create conda environment with python version 3.7
```
conda create -n fbprophet python=3.7
```
2. Activate the environment
```
conda activate fbprophet
```
3. Install C++ Compiler
```
conda install libpython m2w64-toolchain -c msys2
```
4. Install Dependencies
```
conda install numpy cython -c conda-forge
```
```
conda install matplotlib scipy pandas -c conda-forge
```
5. Install pystan
```
conda install pystan -c conda-forge
```
6. Install Ephem
```
conda install -c anaconda ephem
```
7. Install fbprophet
```
conda install -c conda-forge fbprophet
```
8. To avoid error while importing ipywigets and plotly
```
conda install -c conda-forge ipywidgets
```
```
conda install -c plotly plotly
```
9. Open Anaconda Navigator and goto fbprophet and install Jupyter Notebook **[Imp]**