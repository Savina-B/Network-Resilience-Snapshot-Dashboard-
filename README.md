# Network-Resilience-Snapshot-Dashboard

**Overview**

This project demonstrates an interactive dashboard that generates route-level “snapshot” summaries for a transport network. Users can select a route/corridor, view key resilience metrics, compare actual vs normalized scores (0–100), visualise the route on a map, and export results.

⚠️ This repository is sanitised for public sharing. Names, identifiers, and location-specific information have been anonymised. Data values and structures are representative.

**Key Features**

- Route selector (dropdown-driven UI)

- Snapshot card with key metrics and qualitative notes (issues, constraints, stakeholders, alternatives)

- Metric comparison chart

  - Actual values
  
  - Normalized scoring to support quick benchmarking across routes

- Map view with route marker

- Exports

  - CSV download
  
  - PDF report generation (includes chart + narrative summary)

- Lightweight usage analytics

  - Simple log file capturing interactions (route selected, downloads)

**Technology Stack**

- Python

- Dash + Dash Bootstrap Components

- Plotly

- Dash Leaflet

- Pandas

- ReportLab (PDF report generation)

**Notes on Anonymisation**

This public version:

- Replaces all route/location/operator identifiers with placeholders

- Removes organisational branding and internal references

- Uses representative data schemas and synthetic or aggregated values
