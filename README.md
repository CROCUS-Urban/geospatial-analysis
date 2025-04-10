# CROCUS Geospatial Analysis

Combined geospatial analysis dashboard for CROCUS

## Overview

This initiative focuses on data integration and visualization within the broader CROCUS program. CROCUS is an urban integrated field laboratory established by Argonne National Laboratory that researches how extreme weather conditions impact the Chicago region and its people. Our data integration effort aims to establish a unified approach to managing, integrating, and visualizing diverse CROCUS datasets to enable cross-disciplinary analyses and maximize their scientific value through interactive interfaces that make data accessible to researchers and the public.

## Objectives

### 1. Data Quality and Security
- Implement standardized QAQC procedures across all datasets
- Keep track of data sources and changes over time
- Establish appropriate access controls for sensitive or preliminary data

### 2. Data Inventory and Catalog
- Create a comprehensive inventory of all CROCUS datasets (observations, models, satellite imagery) with links to raw data where available
- Standardize metadata across dataset types and document spatial coverage
- Include geospatial information for all datasets
- Coordinate with existing CROCUS data management efforts

### 3. Visualization and Analysis Tools
- Develop interactive tools to explore urban environmental heterogeneity with Zoomable interface 
- Enable cross-variable analyses to identify relationships between environmental factors using cached data for front-end analysis where possible to optimize performance
- Support CROCUS's mission to create accurate climate models by providing integrated datasets that can validate climate models and help to study extreme weather impacts 

### 4. Dual-Purpose Implementation
- Internal-Facing Tools: Research-grade data access with advanced querying and cross-dataset integration capabilities
- Structure data for easy download with formats that can be used directly for other applications, e.g., climate model assimilation, comparison of observations
- Downloadable in user-specified text, csv, and nc formats. 
- External-Facing Tools: Simplified visualizations with key findings and basic querying features for public use

## Approach
1. Complete data inventory with GIS information and detailed metadata
2. Begin with 4-5 representative dataset types (observations, models, satellite data)
3. Develop wireframes with input from researchers and UI experts
4. Create a prototype focusing on researcher needs before expanding capabilities
5. Implement in phases: inventory → basic visualization → query capabilities → integration

## Technical Considerations
- **Data Volume**: Multiple terabytes across various formats (point observations, gridded models, geospatial layers, time-series data)
- **Hosting Options**: UIC (90TB storage), LCRC/ALCF resources
- **User Requirements**: Quality-controlled data, preview capabilities, flexible download options, interactive interface, cross-dataset visualization tools, optimized for stakeholders as main end-users
- **Access Controls**: Different levels for sensitive or preliminary data

## Timeline
1. **Planning and Inventory**
    - Complete data inventory with geospatial information
    - Develop interface wireframes
    - Identify technical solutions for integration challenges
    - Finalize infrastructure requirements
2. **Prototype Development**
    - Implement data catalog with basic metadata search
    - Develop prototype visualization tools with 4-5 representative datasets
    - Test initial query capabilities with research team
3. **Internal Platform Development**: Expanding capabilities for research users.
4. **External Tool Development**: Creating interfaces for non-technical stakeholders.


## Data Sources
All geospatial data files can be found in the directory:

```bash
data/
```
