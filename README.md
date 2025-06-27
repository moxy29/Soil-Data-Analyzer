# Soil-Data-Analyzer
In this section of the soil data analyzer, you will be able to process the data using Python and R Studio.

## Coordinate generator 
This Python script was made to generate coordinates for soil sample collection across an agricultural field using a random sampling technique. The agricultural field (43°09'36.0"N, 81°55'48.0"W; 180 m × 480 m) was divided into 8 grids (each of 120 m × 90 m) based on user-defined dimensions. Random 4 coordinates were generated within each grid, and the resulting coordinates.

## Soil flux
To analyze the data, the R code was used. The multiple generated soil probe data files were imported and bind into one, followed by converting the epoch time to EST. Then, the valve data was imported and averaged to a minute. All datasets (NO, NO2, HONO, valve state, and soil probe readings) were synchronized to one-minute intervals, producing a unified dataset on the same time base. Average hourly flux and integrated flux using the trapezoidal rule were calculated. The CSV file is then exported, and the data is plotted in Igor. 

## Bin data
An R code was produced to bin data into predefined soil VWC (e.g., 20-24). The code enables statistical comparisons among samples and trend visualization for NOy across these regimes. 


