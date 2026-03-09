# Expat Tax Calculator

A web-based tax calculator for expatriates in France and the Netherlands, helping users estimate savings from preferential tax regimes.

## Supported Tax Regimes

### France — Régime des Impatriés (Art. 155 B CGI)
- 8-year regime window from year of arrival
- Prime d'impatriation exemption (flat-rate 30% or custom up to 50% of gross)
- 10% professional expense deduction (frais professionnels, Art. 83 CGI)
- Progressive tax brackets with décote reduction and family quotient (quotient familial)
- Tracks refund eligibility within the 2-year amended return window

### Netherlands — 30% Ruling
- 5-year regime window from year of arrival
- 30% ruling (transitional to 27% from 2027 for post-2023 arrivals)
- Box 1 income tax with social insurance contributions (volksverzekeringen)
- WNT salary cap and minimum salary threshold validation
- Tax credits: algemene heffingskorting and arbeidskorting

## Features

- Year-by-year breakdown of taxes, savings, and net salary
- Interactive per-year salary inputs with sliders
- Status badges indicating actionable years (refundable, apply now, future)
- Detailed tooltips with tax formula steps and legal references
- Responsive design for desktop and mobile
- Uses official tax brackets sourced from Légifrance, BOFiP, and Belastingdienst

## Tech Stack

- React 18 (loaded via CDN)
- Babel Standalone for in-browser JSX transpilation
- No build step required — static HTML + JSX, deployable to GitHub Pages
