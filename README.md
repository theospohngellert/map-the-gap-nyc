# Map the Gap NYC

An interactive tool showing the gap between New York City's official "affordable housing" income benchmarks and what households in each neighborhood actually earn.

**Live site:** https://mapthegap.nyc/

## What it shows

NYC prices affordable housing against a regional Area Median Income (AMI) — $152,700 for a 3-person household in 2026 — calculated across the entire metro region, including its wealthiest suburban counties. This tool compares that benchmark against the real median household income in all 55 Furman Center sub-borough areas covering the entire city, showing:

- **The gap map** — every neighborhood's median income as a percentage of regional AMI, colored by HPD's own published income bands
- **Gap cards** — what rent each neighborhood's median household can actually afford (30%-of-income standard), what current tenants actually pay, and what "affordable" units at 30%, 50%, 80%, and 130% AMI charge
- **A personal calculator** — enter household income and size (1–8 people) to see your real AMI percentage, which lottery bands you'd qualify for, and what rent is genuinely affordable to you
- **Closing the Gap** — what would and wouldn't actually close the gap between the benchmark and neighborhood incomes, and what this project argues for

## Data sources

- **Neighborhood incomes and rents:** [NYU Furman Center CoreData.nyc](https://coredata.nyc), median household income and median gross rent by sub-borough area, in 2025 dollars (latest available year per area: 2024; one area uses 2023 for income)
- **AMI:** [NYC HPD Area Median Income schedule](https://www.nyc.gov/site/hpd/services-and-information/area-median-income.page), HUD FY2026
- **"Affordable" rent formula:** 30% of the band's income ceiling ÷ 12
- **Block by Block plan figures:** NYC's Block by Block housing plan (2026)

Full methodology and caveats are in the Method & Sources section of the site.

**Data as of:** August 2026. Income and rent data refresh annually with new ACS releases; AMI updates each spring.

## Pages

- `index.html` — the interactive map and calculator
- `about.html` — methodology, the AMI calculation, and the Block by Block plan
- `closing-the-gap.html` — what would close the gap, and what this project argues for
- `contact.html` — get in touch

## Author

Built by Theodore Spohngellert — public administration graduate student at Baruch College's Marxe School of Public and International Affairs and public policy professional in NYC, focused on housing policy, harm reduction, and criminal justice reform.

## Contact

mapthegapnyc@gmail.com
