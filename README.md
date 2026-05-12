# Decennial Headship Rates
Uses census api to compare headship rates from 2010-2020 across 10 largest Western US metro areas

## Install
1. Install UV using powershell
    
    ```powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"```
2. Sync the UV environment 
    
    ```uv sync```
2. Open and run metro_headship_rates.ipynb jupyter notebook
3. Render the quarto dashboard
    
    ```quarto render metro_headship_rates.ipynb```