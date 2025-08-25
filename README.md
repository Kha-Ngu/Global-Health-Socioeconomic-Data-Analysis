<h1>🌍 Global Health & Socioeconomic Data Analysis</h1>

<p>
A Python-based data science project analyzing the global relationship between <strong>life expectancy</strong>, <strong>income composition</strong>, and <strong>healthcare expenditure</strong>. The research aims to identify key drivers of health disparities across developed and developing nations using real-world data and statistical visualizations.
</p>

<hr>

<h2>📌 Overview</h2>
<ul>
  <li><strong>Author:</strong> Khanh Nguyen</li>
  <li><strong>Platform:</strong> Google Colab (Python)</li>
  <li><strong>Tools Used:</strong> Pandas, NumPy, Matplotlib, Seaborn</li>
  <li><strong>Dataset Source:</strong> <a href="https://www.kaggle.com/">Kaggle</a></li>
  <li><strong>Live Notebook:</strong> <a href="https://colab.research.google.com/drive/1asivF5sphOr0HWfZQUSvhLE9Ys_bjSr5?usp=sharing">Analysis Notebook</a></li>
  <li><strong>Sample Size:</strong> 650 rows, 131 countries</li>
  <li><strong>Time Range:</strong> 2010–2015 (filtered subset)</li>
</ul>

<hr>

<h2>🔬 Research Objective</h2>
<p>
To investigate how variables such as income, health spending, schooling, and disease prevalence impact <strong>life expectancy</strong> globally. Special attention is paid to disparities between developed and developing countries.
</p>

<hr>

<h2>📊 Variables Explored</h2>
<ul>
  <li><strong>Dependent Variable:</strong> Life Expectancy</li>
  <li><strong>Independent Variables:</strong> Income Composition, HIV/AIDS, Hepatitis B, Total Health Expenditure, Schooling, GDP</li>
  <li><strong>Categorical:</strong> Country, Status (Developed/Developing)</li>
</ul>

<hr>

<h2>🛠 Data Wrangling & Preprocessing</h2>
<ul>
  <li>Used <code>pandas</code> for data manipulation and filtering by year (2010–2015)</li>
  <li>Filtered a 2014 subset (131 countries) for focused analysis</li>
  <li>Cleaned missing or inconsistent entries and checked data types</li>
  <li>Plotted histograms, scatter plots, and bar charts to analyze relationships</li>
</ul>

<hr>

<h2>📈 Visualizations and Key Findings</h2>
<ul>
  <li><strong>Life Expectancy vs. Country</strong>: Avg. global life expectancy in 2014 was 70. Highest: Belgium, Germany, Portugal; Lowest: Sierra Leone</li>
  <li><strong>Healthcare Expenditure vs. Life Expectancy</strong>: Weak correlation (R = 0.32); spending doesn’t guarantee longer lifespan</li>
  <li><strong>Income Composition vs. Life Expectancy</strong>: Strong positive correlation (R = 0.89), especially in developing countries</li>
  <li><strong>Schooling vs. Life Expectancy</strong>: R = 0.80; education appears highly predictive of lifespan</li>
  <li><strong>HIV/AIDS & Hepatitis B</strong>: HIV/AIDS prevalence has a strong negative correlation with life expectancy</li>
  <li><strong>GDP & Population</strong>: GDP is weakly correlated; population shows little direct effect</li>
</ul>

<hr>

<h2>🧠 Analysis Highlights</h2>
<ul>
  <li>Developing countries show steeper gains in life expectancy with increased schooling and income</li>
  <li>Health access is more tightly tied to individual income levels than government spending alone</li>
  <li>Insurance, health literacy, and targeted policies are essential to bridging equity gaps</li>
</ul>

<hr>

<h2>📉 Correlation Matrix</h2>
<p>
A complete Pearson correlation matrix was generated to visualize variable relationships.
</p>

<pre><code>
Life Expectancy  → Income (0.72), Schooling (0.73), GDP (0.44)
Life Expectancy  → HIV/AIDS (-0.59), Hep B (0.20), Population (-0.02)
</code></pre>

<hr>

<h2>💬 Policy Implications</h2>
<ul>
  <li><strong>For Governments:</strong> Target low-income populations for equitable health access</li>
  <li><strong>For Insurance Providers:</strong> Offer inclusive, affordable health plans</li>
  <li><strong>For Healthcare Providers:</strong> Optimize resource allocation and promote preventive care</li>
</ul>

<hr>

<h2>⚠️ Limitations</h2>
<ul>
  <li>Dataset is limited to 2000–2015 and not fully up to date</li>
  <li>Missing values for some countries and variables (e.g., Hep B, HIV/AIDS)</li>
  <li>Only two countries have full data for 2015, limiting trend analysis</li>
</ul>

<hr>

<h2>📎 File Structure</h2>
<pre><code>
├── Health and Demographics.csv     # Raw dataset
├── Correlation Matrix.csv          # Output of Pearson correlations
├── colab_notebook.ipynb            # Full Python code and visualizations
├── README.md
</code></pre>

<hr>

<h2>📚 Conclusion</h2>
<p>
The research shows that while health infrastructure and government spending are important, individual income and education levels are the most powerful indicators of life expectancy. Effective policy should prioritize equity in income distribution and education access to improve global health outcomes.
</p>
