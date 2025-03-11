# Bus Data Analysis

## Overview
This project provides an analysis of public bus data using Python, focusing on data collection, cleaning, exploratory data analysis (EDA), geographic visualization, performance analysis, and predictive modeling. The project uses the following libraries:

- **pandas**: For data manipulation and analysis.
- **matplotlib & seaborn**: For data visualization.
- **folium**: For interactive geographic visualizations.
- **geopandas**: For handling geospatial data.

## Project Structure
1. **Coleta e Limpeza de Dados**  
    - Reads CSV files containing bus lines, demand, and complaints data.  
    - Performs basic data cleaning, including date conversion and removal of missing values.  

2. **Análise Exploratória de Dados (EDA)**  
    - Visualizes bus line demand with bar plots.  
    - Analyzes complaints by type using pie charts.  

3. **Visualização de Dados Geográficos**  
    - Uses Folium to create interactive maps centered in Curitiba.  
    - Plots bus line markers based on latitude and longitude data.  

4. **Análise de Desempenho (Optional)**  
    - Provides a histogram plot of travel times (if data is available).  

5. **Modelagem Preditiva (Optional)**  
    - Demonstrates a basic Linear Regression model for predicting passenger demand.  
    - Evaluates the model using Mean Squared Error (MSE).  

## Files
- `linhas_onibus.csv`: Contains bus line information, including line names and geographic data.
- `demanda_onibus.csv`: Contains bus demand data with timestamps and passenger counts.
- `reclamacoes_urb.csv`: Contains urban complaints data categorized by type.
- `mapa_linhas_onibus.html`: Output file generated with interactive map visualization.

## Requirements
Install the necessary packages with:
```bash
pip install pandas matplotlib seaborn folium geopandas scikit-learn
```

## Usage
Run the script to perform data analysis, visualization, and predictive modeling:
```bash
python bus_analysis.py
```

## Future Improvements
- Add more sophisticated predictive modeling using machine learning techniques.
- Improve the geographic visualization by integrating real bus routes.
- Provide dashboards for better visualization of trends and patterns.
- Acess more important datasets of URBS.

## License
This project is licensed under the MIT License.
