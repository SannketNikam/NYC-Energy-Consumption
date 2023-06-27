# New York City Energy Consumption

>## NYC Energy Consumption Forecasting using Univariate Arima, Univariate FbProphet and Multivariate FbProphet

<!-- <img src="https://github.com/SannketNikam/NYC-Energy-Consumption/blob/main/Images/NYC_Energy_Demand.png"/> -->
![NYC_Energy_Demand](https://github.com/SannketNikam/NYC-Energy-Consumption/assets/77570082/9ed1eafc-1464-48fc-920a-7d3977866def)

<hr>

## Notebook files:
1. <a href="https://github.com/SannketNikam/NYC-Energy-Consumption/blob/main/Notebooks/1.%20Auto%20Arima%20Univariate.ipynb">Auto Arima Univariate</a><br>
2. <a href="https://github.com/SannketNikam/NYC-Energy-Consumption/blob/main/Notebooks/2.%20FbProphet%20Univariate.ipynb">FbProphet Univariate</a><br>
3. <a href="https://github.com/SannketNikam/NYC-Energy-Consumption/blob/main/Notebooks/3.%20FbProphet%20Multivariate.ipynb">FbProphet Multivariate</a><br>
<hr>

## Steps for FBProphet installation:

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
numpyconda install libpython m2w64-toolchain -c msys2
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
9. **[Imp]**  Open Anaconda Navigator, under environments select fbprophet and install Jupyter Notebook inside fbprophet environment.

<p style="text-align: center;"><b>OR</b></p>

```
conda install -c anaconda jupyter
```
```
conda install -c anaconda notebook
```
