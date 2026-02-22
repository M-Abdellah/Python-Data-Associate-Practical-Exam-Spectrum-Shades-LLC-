<h1 align="center">🏭 Production Data Analysis & Quality Insights</h1>

<p align="center">
  <strong>بسم الله الرحمن الرحيم</strong><br>
  <em>And my success is only by Allah</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project performs professional data cleaning, transformation, aggregation, and statistical analysis
on production batch data to uncover quality performance insights.
</p>

<ul>
  <li>✅ Data Cleaning & Preprocessing</li>
  <li>📊 Aggregation & Grouped Analysis</li>
  <li>📈 Statistical Analysis</li>
  <li>🔍 Correlation Analysis</li>
  <li>📉 Quality Performance Evaluation</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><strong>Python</strong></li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>

<hr>

<h2>📂 Dataset Structure</h2>

<table>
  <tr>
    <th>Column</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>batch_id</td>
    <td>Unique batch identifier</td>
  </tr>
  <tr>
    <td>production_date</td>
    <td>Date of production</td>
  </tr>
  <tr>
    <td>raw_material_supplier</td>
    <td>National / International supplier</td>
  </tr>
  <tr>
    <td>pigment_type</td>
    <td>Type of pigment used</td>
  </tr>
  <tr>
    <td>pigment_quantity</td>
    <td>Quantity of pigment (kg)</td>
  </tr>
  <tr>
    <td>mixing_time</td>
    <td>Mixing duration</td>
  </tr>
  <tr>
    <td>mixing_speed</td>
    <td>Mixing speed level</td>
  </tr>
  <tr>
    <td>product_quality_score</td>
    <td>Final quality score</td>
  </tr>
</table>

<hr>

<h2>🧹 Task 1: Data Cleaning</h2>

<ul>
  <li>✔ Converted <code>production_date</code> to datetime format</li>
  <li>✔ Replaced supplier codes (1 → national, 2 → international)</li>
  <li>✔ Standardized pigment type naming</li>
  <li>✔ Converted pigment quantity to integer</li>
  <li>✔ Filled missing <code>mixing_time</code> values using mean</li>
  <li>✔ Rounded numerical values to 2 decimals</li>
</ul>

<hr>

<h2>📊 Task 2: Supplier-Based Aggregation</h2>

<table>
  <tr>
    <th>Supplier</th>
    <th>Avg Quality Score</th>
    <th>Avg Pigment Quantity</th>
  </tr>
  <tr>
    <td>International Supplier</td>
    <td>5.97</td>
    <td>34.42</td>
  </tr>
  <tr>
    <td>National Supplier</td>
    <td>8.02</td>
    <td>44.23</td>
  </tr>
</table>

<p><strong>Insight:</strong> National suppliers show significantly higher average quality performance.</p>

<hr>

<h2>🎯 Task 3: Quality Score (International Supplier &gt; 35kg)</h2>

<p>
Filtered batches where pigment quantity exceeds 35kg for international suppliers.
Observed moderate quality consistency ranging between <strong>5.7 – 6.7</strong>.
</p>

<hr>

<h2>📈 Task 4: Statistical & Correlation Analysis</h2>

<table>
  <tr>
    <th>Metric</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>Product Quality Mean</td>
    <td>6.68</td>
  </tr>
  <tr>
    <td>Product Quality Std Dev</td>
    <td>1.39</td>
  </tr>
  <tr>
    <td>Pigment Quantity Mean</td>
    <td>37.85</td>
  </tr>
  <tr>
    <td>Pigment Quantity Std Dev</td>
    <td>6.83</td>
  </tr>
  <tr>
    <td>Correlation Coefficient</td>
    <td>0.49</td>
  </tr>
</table>

<p>
<strong>Key Insight:</strong><br>
There is a <strong>moderate positive correlation (0.49)</strong> between pigment quantity and product quality.
Increasing pigment quantity tends to improve quality — but it is not the sole determining factor.
</p>

<hr>

<h2>🚀 How to Run</h2>

<pre>
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install pandas numpy matplotlib seaborn
python script_name.py
</pre>

<hr>

<h2>📌 Future Improvements</h2>

<ul>
  <li>📊 Correlation heatmaps</li>
  <li>📈 Regression modeling</li>
  <li>🧠 Machine learning quality prediction</li>
  <li>📦 Modular project structure</li>
  <li>🧪 Unit testing</li>
</ul>

<hr>

<h2>👤 Author</h2>

<p>
<strong>Mohamed</strong><br>
Data Analyst | Python Enthusiast
</p>

<p align="center">
  ⭐ If you found this project helpful, consider starring the repository!
</p>
