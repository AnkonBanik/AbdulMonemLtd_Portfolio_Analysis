# Abdul Monem Ltd. — Tableau Portfolio Report

An independent Tableau analysis of Abdul Monem Ltd.’s recorded project and work-package portfolio in Bangladesh.

The report presents the collection as a magazine-style visual story, combining portfolio composition, project activity, geographic presence, funding, employers, timelines, duration, and executed financial value.

## Project summary

- **126** project and work-package records
- **19** project-type categories
- **7** broad sectors
- **BDT 96.40 billion** total recorded executed value
- Coverage period: **1980–2023**
- Geographic scope: Bangladesh divisions and project locations recorded in the source register

## Dashboards and Report Sections

The workbook contains six presentation dashboards supported by additional worksheets and calculations:

1. **Portfolio overview** — headline KPIs, project collection summary, and geographic presence.
2. **Portfolio mix** — distribution of records across broad sectors and detailed project types.
3. **Value concentration** — executed value by project, including a top-five view and cumulative share of total value.
4. **Project history and duration** — commencement patterns, completion status, project duration bands, and activity over time.
5. **Geography and employers** — regional presence and the organizations associated with the recorded work.
6. **Project record explorer** — an interactive project profile with filters and detail cards for sector, project type, employer, funding, dates, duration, and recorded value.

<img width="1184" height="777" alt="image" src="https://github.com/user-attachments/assets/227dffff-25de-48bf-9a96-9f7a8aad71b3" />


<img width="1190" height="803" alt="image" src="https://github.com/user-attachments/assets/4ba44262-c92b-49c3-bbd3-7719126178df" />


## Key Findings Highlighted

- Transport infrastructure is the largest part of the collection by record count and recorded value.
- Road construction and improvement is the most frequent detailed project type, followed by road rehabilitation and maintenance.
- The largest projects account for a substantial share of the total recorded value; the top five projects represent approximately half of the displayed cumulative value in the report.
- Project activity is concentrated in the 2000s, with a smaller but continuing presence in later years.
- Government funding and public-sector employers make up a major part of the recorded register.

## Files

- `AML_Portfolio.twbx` — packaged Tableau workbook, including the workbook structure and packaged data extract.
- `AML_Portfolio_Presentation.pdf` — static PDF presentation of the report dashboards.

## How to view the workbook

Open `AML_Portfolio.twbx` with **Tableau Public** or **Tableau Desktop**. The packaged workbook contains the supporting worksheets, calculations, filters, and dashboard layouts used to build the report.

Use the project selector on the **Project Record Explorer** dashboard to inspect an individual record. The detail cards update to show the selected project’s attributes and recorded value.

## Methodology

The analysis uses the project register supplied for this independent portfolio study. Records were grouped into broad sectors and detailed project types, and the following measures were calculated or displayed:

- record count
- executed value in Bangladeshi taka (BDT)
- cumulative share of total executed value
- commencement and completion periods
- duration in months and years
- employer and funding-label distributions
- division-level geographic presence

Values are presented as recorded in the source register. BDT amounts are nominal recorded values and are not adjusted for inflation, exchange rates, or changes in project scope.

## Important Limitations

- This is an independent analysis of the supplied register, not an audited financial statement.
- A register record may represent a project, phase, package, or work package; record count should not be interpreted as a count of unique contracts without further validation.
- Missing, ambiguous, or provisional dates and locations may affect timeline and map views.
- Funding labels and employer names are retained from the source wording and may contain naming variations.
- Executed value indicates recorded financial value; it does not by itself measure profitability, physical progress, quality, or project performance.

## Source

Project information was compiled from Abdul Monem Ltd.’s publicly available project register:

<https://www.amlbd.com/page/9/projects>

## Author

Prepared as an independent Tableau portfolio study by **ANKON**.
