# GDP per Capita vs. Life Expectancy (U.S. & China, 1982-2022)

Analysis of how GDP per capita relates to life expectancy in the United States and China.

**Data:** World Bank (NY.GDP.PCAP.CD, SP.DYN.LE00.IN), 1982-2022.

**Methods:** Pearson correlation, linear and logarithmic regression, significance testing (SciPy), SQL decade summaries (SQLite).

**Findings:** Both countries show a strong positive correlation (r = 0.84 U.S., 0.85 China). A linear model fits the U.S. (R^2 = 0.703); a logarithmic model fits China much better (R^2 = 0.965 vs. 0.721 linear), consistent with diminishing returns at higher GDP.

**Limitations:** Correlation is not causation, data is national-level, and 40 years is a limited window.

**Note:** Numbers differ slightly from my original Excel analysis because the World Bank has since revised its data.

**Files:** gdp_life_expectancy.ipynb (analysis), fits.png (charts), gdp_life.db (SQLite database)
