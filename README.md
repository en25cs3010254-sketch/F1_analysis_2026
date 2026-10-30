# Formula 1 Race Intelligence

An interactive Tableau-based project that uses data visualization to explore various aspects of Formula 1 racing. It focuses on team and driver performance, tyre-compound results, Grand Prix hosting trends, podium accomplishments, and race reliability.

## Project Scenarios

### 1. F1 Team Performance Strategist

- **Constructor Championship Points Trend:** analyzes and compares team championship points over multiple seasons.
- **Tyre Compound Performance by Circuit Type:** examines podium results based on starting tyre compounds and different circuit types.
- **Driver Talent and Performance Ranking:** evaluates and compares driver performance within a selected season.

### 2. Motorsport Broadcast Analyst

- **All-Time Driver Points Leaderboard:** displays driver rankings based on their total points across the available seasons.
- **Countries Hosting the Most Grand Prix Rounds:** identifies countries with the highest number of hosted races using distinct race counts.
- **Podium Achievements by Driver and Team:** analyzes podium finishes achieved by different drivers and their respective teams.

### 3. F1 Technical Regulation Analyst

- **DNF Reasons by Team:** analyzes the different recorded reasons for race retirements across teams.
- **DNF Patterns by Circuit Type and Driver:** explores retirement trends among drivers across various circuit types.
- **Driver and Team Reliability Trend:** evaluates race-completion percentages and compares reliability across seasons.

## Dataset Description

| Sheet | Description |
|---|---|
| `circuits` | Contains information and details about different circuits. |
| `championship_standings` | Includes driver championship standings and points for each season. |
| `lap_intelligence` | Provides lap-level data for detailed race analysis. |
| `qualifying_results` | Contains information about qualifying session results. |
| `race_results` | Includes race results, driver and team details, finishing positions, tyre information, and retirement records. |

## Sharing Through Tableau Public

1. Launch the workbook using Tableau Public Edition.
2. Log in using your Tableau Public account.
3. Navigate to **Server → Tableau Public → Save to Tableau Public** (the menu name may differ depending on the version).
4. Once published, visit your Tableau Public profile to access the visualization.
5. Click **Share** to obtain the public link to your project.

## Tools Used

- **Tableau** — used to create visualizations, dashboards, interactive filters, and stories.
- **Microsoft Excel / Spreadsheet Data** — used for examining and preparing the dataset.
- **GitHub** — used for project management, version control, and sharing.

## Notes and Limitations

- The analysis is based only on the seasons and records available in the provided dataset. The most recent season might contain incomplete information.
- Championship standings contain driver-level records. Calculating team totals from these records requires accurate driver-to-team assignments for every season.
- The country hosting a Grand Prix should not be confused with a driver's nationality. Nationality-based analysis requires a reliable nationality field or a verified reference table.
- DNF analysis relies on the status classifications available in the dataset. These definitions should be checked before interpreting the results.
- Combining tables with different levels of detail may lead to duplicated records. Row counts and aggregated values should be verified after joining tables, and Tableau relationships should be used where appropriate.
- The visualizations highlight trends and relationships in the data but do not independently establish the reasons behind those patterns.
