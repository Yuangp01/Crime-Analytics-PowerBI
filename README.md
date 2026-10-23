
<h1>LOS ANGELES CRIME ANALYTICS DASHBOARD</h1>

<blockquote>
  An interactive Power BI investigation and executive reporting
  solution that transforms historical LAPD incident records into
  clearer geographic, temporal, and case-level insights.
  Designed as a data analytics portfolio project to support
  evidence-informed public safety analysis.
</blockquote>

<p>
  <a href="https://powerbi.microsoft.com/">
    <img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  </a>
  <a href="https://learn.microsoft.com/en-us/power-query/">
    <img src="https://img.shields.io/badge/POWER%20QUERY-217346?style=for-the-badge&logoColor=white" alt="Power Query">
  </a>
  <a href="https://learn.microsoft.com/en-us/dax/">
    <img src="https://img.shields.io/badge/DAX-FFB900?style=for-the-badge&logoColor=black" alt="DAX">
  </a>
  <a href="https://learn.microsoft.com/en-us/power-bi/guidance/star-schema">
    <img src="https://img.shields.io/badge/DATA%20MODELING-0078D4?style=for-the-badge&logoColor=white" alt="Data Modeling">
  </a>
  <a href="https://www.microsoft.com/microsoft-365/excel">
    <img src="https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logoColor=white" alt="Excel">
  </a>
  <img src="https://img.shields.io/badge/GEOSPATIAL%20ANALYSIS-654FA2?style=for-the-badge&logoColor=white" alt="Geospatial Analysis">
</p>

<p>
  <a href="#project-at-a-glance">At a Glance</a> &nbsp;•&nbsp;
  <a href="#business-context">Business Context</a> &nbsp;•&nbsp;
  <a href="#dashboard-gallery">Dashboards</a> &nbsp;•&nbsp;
  <a href="#technical-approach">Technical Approach</a> &nbsp;•&nbsp;
  <a href="#key-findings">Findings</a> &nbsp;•&nbsp;
  <a href="#recommendations">Recommendations</a>
</p>

<hr>

<h2 id="project-at-a-glance">📌 Project at a Glance</h2>

<table>
  <tr>
    <th align="center">800K+</th>
    <th align="center">2020–2024</th>
    <th align="center">21+</th>
    <th align="center">2</th>
  </tr>
  <tr>
    <td align="center">Reported crime records</td>
    <td align="center">Analysis period</td>
    <td align="center">LAPD reporting divisions</td>
    <td align="center">Power BI report views</td>
  </tr>
</table>

<p>
  <strong>Primary audience:</strong>
  Crime analysts, investigative teams, operational leadership,
  and public safety stakeholders.
</p>

<p>
  <strong>Data source:</strong>
  Publicly available incident-level records from the
  <a href="https://data.lacity.org/">Los Angeles Open Data Portal</a>.
</p>

<p>
  <strong>Project scope:</strong>
  Historical analysis and investigative exploration;
  not a live LAPD operational deployment.
</p>

<hr>

<h2 id="business-context">🎯 Business Context</h2>

<p>
  Crime incident data is valuable only when analysts can
  translate thousands of individual records into meaningful patterns.
  Static summaries can make it difficult to connect
  <strong>where incidents occur</strong>,
  <strong>how activity changes over time</strong>,
  and <strong>which related cases warrant closer review</strong>.
</p>

<p>
  <strong>Analytical challenge:</strong>
  Build a unified, self-service reporting experience that moves
  from citywide monitoring to case-level investigation without
  requiring users to manually reconcile separate maps,
  spreadsheets, and incident lists.
</p>

<h3>Stakeholders &amp; Analytical Questions</h3>

<table>
  <tr>
    <th>Stakeholder</th>
    <th>Decision-Support Question</th>
    <th>Relevant Analysis</th>
  </tr>
  <tr>
    <td><strong>Operational Leadership</strong></td>
    <td>Which divisions have the greatest reported incident volume?</td>
    <td>Division comparisons and geographic concentrations</td>
  </tr>
  <tr>
    <td><strong>Crime Analysis Teams</strong></td>
    <td>How do incident patterns vary by year, month, and offense?</td>
    <td>Trend analysis, calendar patterns, offense categories</td>
  </tr>
  <tr>
    <td><strong>Investigators</strong></td>
    <td>What is known about a selected case and what incidents are geographically nearby?</td>
    <td>Case-number lookup, incident details, proximity analysis</td>
  </tr>
  <tr>
    <td><strong>Public Safety Stakeholders</strong></td>
    <td>How does reported activity differ across locations and categories?</td>
    <td>Map, division, and crime-category breakdowns</td>
  </tr>
</table>

<hr>

<h2 id="dashboard-gallery">🖼️ Dashboard Gallery</h2>

<p>
  Click either screenshot to view it at full resolution.
</p>

<table>
  <tr>
    <th align="center">01 — Executive Crime Overview</th>
    <th align="center">02 — Interactive Case Investigation</th>
  </tr>
  <tr>
    <td width="50%" align="center">
      <a href="./images/crime.png">
        <img
          src="./images/crime.png"
          alt="Crime analytics executive dashboard with division map, KPI cards, and temporal analysis"
          width="100%">
      </a>
    </td>
    <td width="50%" align="center">
      <a href="./images/Case_Investigation.png">
        <img
          src="./images/Case_Investigation.png"
          alt="Case investigation dashboard with case search, map, and nearby incidents"
          width="100%">
      </a>
    </td>
  </tr>
  <tr>
    <td>
      Citywide crime distribution, headline metrics,
      offense mix, and time patterns.
    </td>
    <td>
      Case-level exploration, configurable proximity radius,
      and geographically related incidents.
    </td>
  </tr>
</table>

<details>
  <summary><strong>🔎 Explore Page 1 — Executive Crime Overview</strong></summary>
  <br>
  <p>
    The executive page supports a top-down analysis workflow:
  </p>
  <ol>
    <li>
      <strong>Locate concentrations:</strong>
      Inspect the LAPD division map and compare reported incident counts.
    </li>
    <li>
      <strong>Understand the mix:</strong>
      Review person, property, and society-related groupings.
    </li>
    <li>
      <strong>Find time patterns:</strong>
      Examine year-over-year activity, monthly changes,
      and the calendar heatmap.
    </li>
    <li>
      <strong>Refine the analysis:</strong>
      Use the report's available selections to narrow the view.
    </li>
  </ol>
  <p>
    <strong>Why it matters:</strong>
    Provides context before analysts move to a specific location or case.
  </p>
</details>

<details>
  <summary><strong>🧭 Explore Page 2 — Interactive Case Investigation</strong></summary>
  <br>
  <p>
    The case-investigation page is organized around a repeatable workflow:
  </p>
  <ol>
    <li>
      <strong>Search:</strong>
      Locate an incident using its case number.
    </li>
    <li>
      <strong>Review:</strong>
      Inspect the selected case's available details
      and offense information.
    </li>
    <li>
      <strong>Set proximity:</strong>
      Choose a distance radius around the case location.
    </li>
    <li>
      <strong>Explore:</strong>
      Review nearby incidents on the map and in a linked detail table.
    </li>
  </ol>
  <p>
    <strong>Important:</strong>
    Geographical proximity suggests candidates for review;
    it does not establish that incidents are causally
    or criminally linked.
  </p>
</details>

<hr>

<h2 id="technical-approach">⚙️ Technical Approach</h2>

<p>
  The project follows an analytical workflow from raw
  incident data through transformation, modeling,
  calculation, and interactive reporting.
</p>

<table>
  <tr>
    <th align="center">01</th>
    <th align="center">02</th>
    <th align="center">03</th>
    <th align="center">04</th>
    <th align="center">05</th>
  </tr>
  <tr>
    <td align="center"><strong>Source Data</strong></td>
    <td align="center"><strong>Power Query</strong></td>
    <td align="center"><strong>Data Model</strong></td>
    <td align="center"><strong>DAX</strong></td>
    <td align="center"><strong>Power BI</strong></td>
  </tr>
  <tr>
    <td align="center">LAPD incident records</td>
    <td align="center">Clean and shape</td>
    <td align="center">Relate analytical tables</td>
    <td align="center">Measures and calculations</td>
    <td align="center">Explore and investigate</td>
  </tr>
</table>

<details>
  <summary><strong>🧹 01–02 | Data Preparation and Quality Controls</strong></summary>
  <br>
  <p>
    Power Query supports the preparation of reporting-ready crime data,
    including date and field typing, consistent descriptors,
    and the handling of missing or incomplete values.
  </p>
  <p>
    <strong>Key checks:</strong>
    Valid incident identifiers, usable location fields,
    duplicate handling, and date consistency.
    Geographic visuals should not silently treat missing coordinates
    as incidents that did not occur.
  </p>
</details>

<details>
  <summary><strong>🗂️ 03 | Analytical Data Model</strong></summary>
  <br>
  <p>
    The project presentation documents a
    <strong>snowflake-style analytical model</strong>
    supporting geographic, temporal, offense,
    and incident-level analysis.
  </p>
  <p>
    Relationships and grain should be checked so
    aggregate crime counts do not double-count
    multi-offense or repeated records.
  </p>
</details>

<details>
  <summary><strong>📐 04 | DAX and Analytical Measures</strong></summary>
  <br>
  <p>
    DAX supports context-sensitive crime counts,
    time comparisons, and other indicators used by report visuals.
    A reliable measure should preserve its intended incident grain
    under filtering.
  </p>
  <p>
    The repository README summarizes measure categories;
    it does not claim to reproduce every formula from
    the original PBIX.
  </p>
</details>

<details>
  <summary><strong>🧩 05 | Dashboard Design and User Experience</strong></summary>
  <br>
  <p>
    The experience separates executive monitoring from
    case investigation. Maps, linked detail views,
    trend visuals, and case-number search support
    progressive exploration from overview to detail.
  </p>
  <p>
    <strong>Design principle:</strong>
    Provide supporting detail when relevant without
    overloading the primary page.
  </p>
</details>

<hr>

<h2 id="key-findings">📈 Key Findings</h2>

<p>
  The following observations reflect the findings documented
  in the project presentation for the historical analysis period.
</p>

<table>
  <tr>
    <th>Observation</th>
    <th>Interpretation</th>
  </tr>
  <tr>
    <td><strong>Peak Year: 2022</strong></td>
    <td>
      Reported crime volume reached its highest level
      in the project's 2020–2024 comparison.
    </td>
  </tr>
  <tr>
    <td><strong>Highest-Volume Division: Central</strong></td>
    <td>
      The Central area recorded the largest count
      among the divisions examined.
    </td>
  </tr>
  <tr>
    <td><strong>Largest Broad Grouping: Property Crime</strong></td>
    <td>
      Property-related incidents represented the
      leading category in the project summary.
    </td>
  </tr>
  <tr>
    <td><strong>Day-of-Week Signal: Monday</strong></td>
    <td>
      Monday showed elevated activity across several
      months in the documented analysis.
    </td>
  </tr>
</table>

<p>
  <strong>Interpretation:</strong>
  These are descriptive patterns, not evidence
  that one factor caused the others.
  Incident volume is also not the same as
  population-adjusted crime risk, and findings
  should be revalidated after changing
  source records or filters.
</p>

<hr>

<h2 id="recommendations">🎯 Recommendations and Decision Support</h2>

<table>
  <tr>
    <th>Priority</th>
    <th>Recommended Follow-up</th>
    <th>Why It Matters</th>
  </tr>
  <tr>
    <td>01</td>
    <td>
      <strong>Review high-volume divisions</strong>
      with geographic and temporal context.
    </td>
    <td>
      Focus further investigation where
      recorded activity is concentrated.
    </td>
  </tr>
  <tr>
    <td>02</td>
    <td>
      <strong>Analyze property-related incidents</strong>
      by offense type and reporting area.
    </td>
    <td>
      Understand the components of
      the largest broad category.
    </td>
  </tr>
  <tr>
    <td>03</td>
    <td>
      <strong>Compare patterns across equivalent time windows</strong>
      before drawing operational conclusions.
    </td>
    <td>
      Avoid treating seasonal or reporting
      effects as confirmed changes in risk.
    </td>
  </tr>
  <tr>
    <td>04</td>
    <td>
      <strong>Use proximity results as leads for review</strong>,
      then consult the underlying case details.
    </td>
    <td>
      Make case exploration more systematic
      without assuming incidents are related.
    </td>
  </tr>
</table>

<hr>

<h2 id="workflow-value">⚡ Value of the Analytical Workflow</h2>

<table>
  <tr>
    <th>Traditional Multi-Step Review</th>
    <th>Interactive Analytical Workflow</th>
  </tr>
  <tr>
    <td>
      Open separate static reports and spreadsheets.
    </td>
    <td>
      Begin with one consolidated Power BI overview.
    </td>
  </tr>
  <tr>
    <td>
      Build manual summaries by division and offense.
    </td>
    <td>
      Use linked visual comparisons and report filters.
    </td>
  </tr>
  <tr>
    <td>
      Cross-reference incidents by location manually.
    </td>
    <td>
      Explore a case and nearby incidents through
      the investigation page.
    </td>
  </tr>
  <tr>
    <td>
      Repeat analysis whenever the question changes.
    </td>
    <td>
      Adjust the selection and review the
      corresponding analytical view.
    </td>
  </tr>
</table>

<p>
  <strong>Impact statement:</strong>
  The project demonstrates a more streamlined
  self-service workflow. No measured time savings,
  operational deployment, or causal public safety
  outcomes are claimed.
</p>

<hr>

<h2 id="skills-demonstrated">🛠️ Skills Demonstrated</h2>

<table>
  <tr>
    <th>Capability</th>
    <th>Application in This Project</th>
  </tr>
  <tr>
    <td><strong>Power Query</strong></td>
    <td>Preparing historical incident data for reporting</td>
  </tr>
  <tr>
    <td><strong>Data Modeling</strong></td>
    <td>Organizing related data for geographic, time, offense, and case analysis</td>
  </tr>
  <tr>
    <td><strong>DAX</strong></td>
    <td>Building context-sensitive indicators and comparisons</td>
  </tr>
  <tr>
    <td><strong>Power BI</strong></td>
    <td>Developing multi-page interactive analytical dashboards</td>
  </tr>
  <tr>
    <td><strong>Geospatial Analytics</strong></td>
    <td>Mapping incident concentrations and nearby cases</td>
  </tr>
  <tr>
    <td><strong>Analytical UX</strong></td>
    <td>Connecting executive summaries to case-level exploration</td>
  </tr>
  <tr>
    <td><strong>Data Storytelling</strong></td>
    <td>Translating descriptive patterns into investigative questions</td>
  </tr>
</table>

<hr>

<h2 id="limitations">🔍 Data Quality, Scope, and Responsible Interpretation</h2>

<ul>
  <li>
    <strong>Historical snapshot:</strong>
    The project covers 2020–2024 and should not be
    described as a live crime-monitoring system.
  </li>
  <li>
    <strong>Reported incidents:</strong>
    The data reflects incidents recorded in the
    source system, not necessarily every offense
    that occurred.
  </li>
  <li>
    <strong>Geographic coverage:</strong>
    Missing or imperfect location records can
    affect mapping and proximity results.
  </li>
  <li>
    <strong>Metrics:</strong>
    Incident counts, offense counts, clearances,
    and population-adjusted rates are different
    measures and should not be conflated.
  </li>
  <li>
    <strong>Ethical use:</strong>
    Geographic concentrations must not be used
    alone to infer individual behavior or justify
    enforcement decisions.
  </li>
  <li>
    <strong>Project status:</strong>
    A portfolio demonstration, not an official
    LAPD product or a verified production deployment.
  </li>
</ul>

<hr>

<h2 id="explore-the-project">📁 Explore the Project</h2>

<p>
  <a href="./images/">
    <img src="https://img.shields.io/badge/VIEW-DASHBOARD%20IMAGES-0078D4?style=for-the-badge&logoColor=white" alt="View dashboard images">
  </a>
  <a href="./presentation/">
    <img src="https://img.shields.io/badge/VIEW-PRESENTATION-68459B?style=for-the-badge&logoColor=white" alt="View project presentation">
  </a>
  <a href="https://yuangp01.github.io/">
    <img src="https://img.shields.io/badge/EXPLORE-PORTFOLIO-238A66?style=for-the-badge&logoColor=white" alt="Visit portfolio">
  </a>
</p>

<p>
  Open the repository's available Power BI project files
  in Power BI Desktop to explore working report interactions.
  Screenshots on GitHub are static previews.
</p>

<hr>

<h2 id="author">👤 Author</h2>

<p>
  <strong>Yuan Gonzalez</strong><br>
  Data Analytics | Business Intelligence | Power BI<br>
  <a href="https://github.com/Yuangp01">GitHub</a> &nbsp;•&nbsp;
  <a href="https://yuangp01.github.io/">Portfolio</a> &nbsp;•&nbsp;
  <a href="mailto:yuan.gonzalez001@gmail.com">Email</a>
</p>

<p align="center">
  <strong>
    From incident records to clearer questions,
    better analysis, and more informed decisions.
  </strong>
</p>

<p align="right">
  <a href="#los-angeles-crime-analytics-dashboard">⬆ Back to top</a>
</p>
