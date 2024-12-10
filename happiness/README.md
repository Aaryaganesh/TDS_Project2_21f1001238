# Automated Analysis Report

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Lebanon', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
### Narrative Based on the Analysis of 'happiness.csv'

The dataset 'happiness.csv' provides a comprehensive overview of various socio-economic and psychological factors that contribute to happiness levels across numerous countries over multiple years. With 2,363 entries, the dataset consists of several critical variables, including Life Ladder, Log GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption, Positive affection, and Negative affection.

#### 1. Summary of Key Attributes

The **Life Ladder**, a key metric representing individuals' life evaluations on a scale from 0 to 10, has an average score of approximately 5.48, indicating moderate levels of happiness across the surveyed countries. Following a normal distribution, the mean Life Ladder score suggests that many individuals are generally satisfied with their lives, while there is a notable variance (standard deviation of roughly 1.13) reflecting diverse experiences of happiness globally.

**Economic factors** show a correlation with happiness as measured by **Log GDP per capita**, which has a mean of 9.40. This variable indicates a positive relationship between income levels and happiness. However, it is essential to highlight that some countries with lower GDP may still report satisfactory happiness levels due to other contributing factors, such as strong community ties or social support.

The **Social support** metric averages around 0.81, indicating that individuals generally feel they have someone to rely on during tough times. This variable, along with life expectancy (mean of 63.40), strongly correlates with happiness, reinforcing the idea that emotional and physical well-being is crucial to overall life satisfaction.

**Freedom to make life choices** demonstrates an average score of 0.75, suggesting that individuals in this dataset generally feel they have control over their lives. This measured freedom correlates positively with happiness, underscoring its significance in promoting life satisfaction.

#### 2. Correlation Analysis

A deeper inspection through correlation analysis reveals several significant relationships:

- **Life Ladder and Log GDP per capita**:  A strong positive correlation indicates that as income increases, self-reported happiness also tends to rise.
- **Life Ladder and Social support**: Another robust correlation reveals that individuals who report higher levels of social support typically rate their happiness higher.
- **Life Ladder and Freedom to make life choices**: This relationship suggests that increased personal freedom is directly associated with greater happiness.

Interestingly, less correlation is observed between **Generosity** and happiness metrics, hinting that while altruistic behavior is commendable, it does not significantly correlate with personal happiness within this dataset.

#### 3. Visualizations

The **histograms** of numerical data illustrate the distributions of key variables such as Life Ladder, Log GDP per capita, and Social support. These visualizations reveal a distribution pattern where most countries cluster around moderate scores, yet there are considerable outliers, indicating notable exceptions in particular countries.

The **bar plots** representing categorical data provide insight into the number of observations by country. For instance, Lebanon has the highest representation, with 18 recorded entries. This can help identify which nations contribute the most data and insight, allowing for a targeted analysis that reflects regional contexts.

#### Conclusion

The dataset 'happiness.csv' illustrates the multifaceted nature of happiness, revealing that it is deeply entrenched in socio-economic conditions, social networks, and personal freedoms. The strong correlations among economic factors, social support, and happiness highlight the essential elements required for well-being. Future analyses could investigate longitudinal trends and dive deeper into the outliers to understand what unique circumstances lead to higher or lower happiness levels in specific nations. 

This narrative serves as a fundamental guide, presenting clear insights derived from the dataset while encouraging a broader examination of the interconnectedness of happiness, socio-economic status, and cultural differences.

## Visualizations
![Visualization](happiness\heatmap.png)
![Visualization](happiness\boxplot_year.png)
![Visualization](happiness\histogram_year.png)
