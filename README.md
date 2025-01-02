# OKR App

A Frappe application for managing OKR Cycles, Objectives, Key Results, Initiatives, and Weekly Updates, with optional support for Teams, a single Owner, and multiple Contributors.

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)
3. [Setup & Configuration](#setup-and-configuration)
4. [Usage Flow](#usage-flow)
5. [License](#license)

## Overview

This OKR App helps you:
* Define OKR Cycles (e.g., quarterly or yearly)
* Create Objectives and assign an Owner and optional Team
* Attach Key Results to your Objectives (boolean or numeric)
* Organize supporting Initiatives if your Key Results involve projects or tasks
* Log Weekly Updates for both Key Results and Initiatives to track progress over time
* Collaborate with Contributors (e.g., multiple team members), all supporting a single goal

## Installation
1. Ensure you have a working Frappe/Bench setup
2. From your bench directory, install this app:
```bash
bench get-app https://github.com/anoop-ak/okr.git
bench --site your-site-name install-app okr
```
3. Reload and migrate your site:
```bash
bench migrate
bench clear-cache
```

## Setup & Configuration
1. Create an OKR Cycle: For example, "Q1 2025"
2. Add Objectives under each cycle, and give them a priority and status
3. Assign Owner & Contributors: Decide who is ultimately responsible for each Objective and who will contribute
4. Define Key Results (boolean or numeric) under each Objective
5. Initiatives: Create sub-projects or tasks to help achieve each Key Result, if needed
6. Weekly Updates: Log progress for Key Results (numeric/boolean) and Initiatives (project status) every week
7. Reporting & Dashboards: Use standard Frappe features to filter records, create charts, or build custom dashboards

## Usage Flow
1. Plan: Decide on the OKR Cycle (timeframe) and outline Objectives
2. Create: Under each Objective, add Key Results that define success metrics or milestones
3. Execute: Spin off Initiatives or tasks to achieve those Key Results
4. Update: Post weekly updates to reflect the current state or progress
5. Review: Monitor statuses (e.g., "On Track," "Behind," "Achieved"), make adjustments, and finalize achievements at the end of each cycle

## License

This project is licensed under the MIT License. You are free to adapt and reuse it according to your organization's needs.

## Contact
For questions or feedback, please open an issue on GitHub or reach out to contact@anoop-ak.com

Happy OKR tracking!