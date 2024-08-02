# Smartsheets - IT Projects overview
## Purpose: Provide those outside the PMO team w/ a summary report w/out needing to register them a SmartSheets account
Automated report replacing the monthly PMO project rolllup, based on the prior SmartSheets monthly pdf. Moved this reporting into PowerBI so non-PMO staff can have visibility of content w/out needing a (free) SmartSheets license (and IT from having to manage those licenses)

## Pages
Page | About	| Image
-----|----------|---------
Landing	| An overview of the PMO's portfolio, the size and spread of those projects. | <img src="readMeImages\01Landing.png" width="800" Landing>
Project list	| A list of all the current and previous projects, with key callouts	|	<img src="readMeImages\02List.png" width="800" Project list>
Project detail	| Provides an overview of the selected project, it's health, sponsors and key contacts (which include mailto links) | <img src="readMeImages\03Drill.png" width="800" Project detail page dependancies>
Risks	| Provides an overview of the risks related to the specific project | <img src="readMeImages\04Risks.png" width="800" Risks>
Decisions	|	Provides an overview of the decisions related to the specific project | <img src="readMeImages\05Decisions.png" width="800" Decisions>
Proposed projects list | Outlines the projects which have yet to be scoped and accepted / declined	| <img src="readMeImages\06Proposals.png" width="800" Proposed projects list>
Portfolio risk summary | Provides an overview of the PMO's risk exposure, and calls out the projects with the most emerging risks or issues	| <img src="readMeImages\07Summary.png" width="800" Portfolio risk summary>

## Datasets - TODO
### Connection process
Pulls queries from the three (3) components of SmartSheets, via the public PowerBI connector
- Tables
- Views
- Reports

<img src="readMeImages\Load.png" width="800" Query dependancies>

### Schema
<img src="readMeImages\Schema.png" width="800" Relationship diagram>

### Tables

Table | Defintion
---------|----------
Intake Sheet | All the project requests, as lodged by our users / teams
Portfolio Managers | PMO staff
Projects | Core table
Project Contacts | Key people related to each project; requestee, project manager and the executive sponsor
Decision Log | Decisions made related to specific projects, determining scope
Risk Register | Identified and graded risks to the project's launch / release
Lessons Learnt | Registered incidents / issues / near-misses from previous and ongoing projects
Milestones | Key dates in the project schedule
Schedule Table | All tasks in the project schedule
Portfolio Metrics | pre-generated report available in SmartSheets
Overdue | pre-generated view from SmartSheets

## Measures - TODO
Measure | Defintion
--------|-------------
Projects	| m1 def
Active Projects	| m1 def
Active Projects at Risk	| m1 def
Active Projects at low health	| m1 def
Proposals	| m def
Tasks		| m def

## User guide: 
TODO
