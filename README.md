# Northern Ireland Road Safety Analysis 2016
### A Data-Driven Investigation into Traffic Collisions and Speeding Patterns

![Project Banner - Map Visualization]

## 🎯 Project Overview
A spatial and temporal analysis of road traffic collisions and speeding offences across Northern Ireland's 11 council districts, investigating correlations between high-frequency speeding locations and collision hotspots.

**Key Finding:** Belfast and Derry showed highest collision rates correlating with elevated speeding offences, suggesting a measurable relationship between speed violations and accident frequency.

## 📊 Dataset
- **Source:** OpenDataNI (PSNI & Road Safety Partnership)
- **Period:** January - December 2016
- **Records:** 
  - 6,225 collision incidents
  - 9,591 casualty records
  - 43,658 traffic offence records
- **Scope:** 11 council districts across Northern Ireland

## 🔍 Key Questions Explored
1. Is there a spatial correlation between speeding hotspots and collision locations?
2. Which districts show highest collision and offence rates?
3. What temporal patterns exist in speeding offences throughout the year?
4. What proportion of incidents involved different vehicle types?

## 🎨 Methodology

### Data Analysis Pipeline
1. **Data Acquisition** → Sourced 3 comparable 2016 datasets from OpenDataNI
2. **Exploratory Analysis** → R-based statistical analysis using ggplot2
3. **Spatial Mapping** → Coordinate transformation (EPSG:29903 → EPSG:4326)
4. **Visualization Design** → Multi-format outputs for different insights
5. **Synthesis** → Infographic creation for public accessibility

### Technical Stack
- **Analysis:** R (ggplot2, sp, rgdal, maps)
- **Spatial:** Coordinate system transformation for accurate mapping
- **Design:** Adobe Creative Cloud for final visualizations
- **Data Format:** CSV, RDS (spatial polygons)

## 📈 Key Findings

### Geographic Analysis
- **Belfast City** accounted for 25% of all collisions (1,565 incidents)
- Urban centers showed concentrated collision patterns
- Spatial correlation identified between speeding frequency and crash locations

### Vehicle Distribution
- 84% passenger vehicles
- 7% goods vehicles
- 3% motorcycles
- 2% buses

### Temporal Patterns
- Monthly variation in offences by district
- Seasonal trends visible in line graph analysis

## 🖼️ Visualizations

### 1. Collision Location Map
![Collision Map Description]
- **Type:** Spatial point plot
- **Insight:** Clear hotspots in Belfast and Derry urban areas
- **Method:** Transformed Irish Grid coordinates to lat/long for plotting

### 2. Temporal Offence Trends
![Line Graph Description]
- **Type:** Multi-series line graph
- **Insight:** District-level monthly variations throughout 2016
- **Design:** Each line represents one of 11 council districts

### 3. Summary Infographic
![Infographic Description]
- **Type:** Multi-format data visualization
- **Purpose:** Public-facing summary of key statistics
- **Approach:** Designed for accessibility and immediate comprehension

## 💡 Design Decisions

See [Design Decisions Documentation](docs/design-decisions.md) for detailed rationale on:
- Color palette choices for accessibility
- Map projection selection
- Graph type selection for different data types
- Infographic layout and hierarchy

## Project Context

This project was completed as part of MED331 - Designing with Data (2017) to explore:
- Visual data communication principles
- Statistical analysis fundamentals
- Public data accessibility and interpretation

### Learning Outcomes
- Spatial data analysis and coordinate system transformations
- Multi-source data integration and comparative analysis
- Design-driven data storytelling for non-technical audiences

##  Future Development Ideas

If expanding this project, potential directions include:
- **Temporal Expansion:** Multi-year trend analysis (2015-2020)
- **Interactive Dashboard:** D3.js or Shiny implementation
- **Predictive Modeling:** Risk modeling for high-frequency locations
- **Deeper Causality:** Integration with road infrastructure data
- **Mobile Accessibility:** Responsive design for public engagement


## 📄 License

This project uses open data from OpenDataNI. Visualizations and analysis code are available under MIT License.