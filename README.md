</head>
<body>

  <h1>OpenFDA Adverse Event Health Report</h1>

  <p class="status">Status: In Progress</p>
  <p><strong>Data Source:</strong> OpenFDA Adverse Event Reporting System</p>

  <h2>Overview</h2>
  <p>
    This project aims to build a <strong>data-driven health and safety report</strong> using adverse event data
    from the <strong>OpenFDA API</strong>. The goal is to identify trends, risks, and patterns associated with foods
    and translate those findings into actionable public health insights.
  </p>

  <h2>Objectives</h2>
  <ul>
    <li><strong>Identify Health Risks:</strong> Discover commonly reported adverse reactions.</li>
    <li><strong>Analyze Product Safety:</strong> Determine which products and industries generate the most reports.</li>
    <li><strong>Understand Consumer Demographics:</strong> Explore age and gender-related trends.</li>
    <li><strong>Track Trends Over Time:</strong> Analyze how reports change year over year.</li>
  </ul>

  <h3>Key Data Fields</h3>
  <ul>
    <li>Adverse event outcomes (hospitalization, ER visits, life-threatening events)</li>
    <li>Reported reactions and symptoms</li>
    <li>Product name, category, and industry</li>
    <li>Consumer demographics (age, gender)</li>
    <li>Event dates and reporting timelines</li>
  </ul>

  <h2>Methodology</h2>

  <h3>Data Cleaning & Preprocessing</h3>
  <ul>
    <li>Standardize and consolidate product information</li>
    <li>Group reactions into broader categories (e.g., gastrointestinal, cardiovascular)</li>
    <li>Handle missing or incomplete fields</li>
  </ul>

  <h3>Core Analysis</h3>
  <ul>
    <li><strong>Frequency Analysis:</strong> Products and industries with the highest reports</li>
    <li><strong>Reaction Analysis:</strong> Common symptoms and severity</li>
    <li><strong>Temporal Analysis:</strong> Trends over time</li>
    <li><strong>Demographic Trends:</strong> Differences by age and gender</li>
  </ul>

  <h3>Advanced Analysis (Planned)</h3>
  <ul>
    <li>Correlation between reactions and product types</li>
    <li>Identification of potential risk factors</li>
    <li>Severity-based outcome comparisons</li>
  </ul>

  <h2>Visualizations (Planned)</h2>
  <ul>
    <li>Bar charts by product and industry</li>
    <li>Heatmaps of reaction vs. outcome correlations</li>
    <li>Time series plots of adverse events</li>
    <li>Pie charts of reaction categories</li>
    <li>Demographic breakdowns</li>
  </ul>


  <h2>Tools & Technologies</h2>
  <ul>
    <li><strong>Programming:</strong> Python, Pandas, NumPy</li>
    <li><strong>Visualization:</strong> Matplotlib, Seaborn, Jupyter Notebooks</li>
    <li><strong>Data Access:</strong> OpenFDA API</li>
    <li><strong>Dashboards (Planned):</strong> Tableau or Power BI</li>
  </ul>

  <h2>Recommendations (Planned)</h2>
  <ul>
    <li>Highlight high-risk products or ingredients</li>
    <li>Support regulatory and consumer safety discussions</li>
    <li>Improve public awareness</li>
    <li>Identify areas for follow-up studies</li>
  </ul>

  <h2>Project Status & Roadmap</h2>
  <ul>
    <li>✔ Project design and analysis framework</li>
    <li>✔ Data extraction via OpenFDA API</li>
    <li>⬜ Data cleaning and preprocessing</li>
    <li>⬜ Exploratory data analysis</li>
    <li>⬜ Visualization development</li>
    <li>⬜ Final report and executive summary</li>
  </ul>

  <h2>Disclaimer</h2>
  <p>
    This project analyzes <strong>self-reported adverse event data</strong>, which may contain reporting bias or
    incomplete information. Results should be interpreted as signals, not proof of causation.
  </p>


</body>
</html>
