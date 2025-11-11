# Data Visualizations with Python

A collection of Jupyter notebooks demonstrating various data visualization techniques using Pandas, Matplotlib, and Plotly.

## Overview

This repository contains 7 exercises covering fundamental to advanced visualization techniques in Python. Each notebook includes practical examples with detailed explanations and multiple variations of each visualization type.

## Notebooks

### 1. Pandas Bar Plot (`ex01_pandas_plot-bar_plot.ipynb`)
- Basic bar plots using Pandas `.plot()` method
- Visualizing age distribution and comparing multiple variables
- Grouped bar charts for children and pets data

**Key Concepts:**
- Pandas plotting wrapper around matplotlib
- `kind='bar'` parameter for bar charts
- Customizing titles, legends, and figure size

### 2. Pandas Scatter Plot (`ex02_pandas_scatter_plot.ipynb`)
- Creating scatter plots to explore relationships
- Age vs. number of children analysis
- Customizing scatter plot appearance

**Key Concepts:**
- `kind='scatter'` for correlation visualization
- Setting axis labels and titles
- Grid customization

### 3. Matplotlib Basics (`ex03_matplotlib_1.ipynb`)
- Direct matplotlib usage for fine-grained control
- Custom line styles and markers
- Combining multiple plot elements

**Key Concepts:**
- Line styles: solid (`-`), dashed (`--`), dashdot (`-.`)
- Marker customization: circles, sizes, colors
- Axis limits and grid configuration

### 4. Matplotlib Twin Axes (`ex04_matplotlib2_twin_axes.ipynb`)
- Plotting data with different scales on same figure
- Secondary y-axis creation with `twinx()`
- Color-coded axes for clarity

**Key Concepts:**
- `twinx()` for dual y-axes
- Independent axis styling
- `tick_params()` customization

### 5. Matplotlib Subplots (`ex05_matplotlib_subplots.ipynb`)
- Creating multi-panel figures (2x3 grid)
- Subplot spacing and layout control
- Systematic subplot iteration

**Key Concepts:**
- `plt.subplots()` for grid creation
- `hspace` and `wspace` for spacing
- Programmatic subplot population

### 6. Plotly Time Series (`ex06_plotly_time_series.ipynb`)
- Interactive time series visualization
- Stock price simulation and plotting
- Both Plotly Express and Graph Objects approaches

**Key Concepts:**
- `px.line()` for quick time series
- `go.Scatter()` for detailed control
- Date handling with pandas
- Interactive hover and zoom features

### 7. Plotly Box Plots (`ex07_plotly_box_plots.ipynb`)
- Statistical distribution comparison
- Box plot with multiple samples
- Controlling outlier and point display

**Key Concepts:**
- `go.Box()` for distribution visualization
- `boxpoints` parameter options: 'outliers', 'all', False
- Color customization and legends

## Requirements

```python
pandas
matplotlib
numpy
plotly
jupyter
```

## Installation

```bash
pip install pandas matplotlib numpy plotly jupyter
```

## Usage

1. Clone the repository
2. Install dependencies
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open any notebook and run the cells

## Key Libraries

- **Pandas**: Data manipulation and quick plotting
- **Matplotlib**: Low-level plotting with fine control
- **Plotly**: Interactive, publication-quality visualizations
- **NumPy**: Numerical data generation

## Learning Path

Follow the notebooks in order (ex01 → ex07) for a progressive learning experience:
1. Start with Pandas plotting (simple, high-level)
2. Move to Matplotlib (more control, customization)
3. Advance to Plotly (interactive, modern visualizations)

## Features

- ✅ Multiple visualization libraries
- ✅ Progressive difficulty
- ✅ Practical examples with real-world scenarios
- ✅ Detailed comments and explanations
- ✅ Multiple variations of each plot type

## Contributing

Feel free to submit issues or pull requests to improve the examples or add new visualization techniques.

## License

MIT License
