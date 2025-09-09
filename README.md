# Daikibo Industrial Analytics Project

## Overview

This repository contains analytical work performed for **Daikibo Industrials**, focusing on two critical business investigations:

1. **Manufacturing Telemetry Analysis** - Machine downtime analysis across global factories
2. **Gender Pay Equity Assessment** - Investigation of salary equality across job roles and locations

## Background

### About Daikibo Industrials

Daikibo operates manufacturing facilities across four global locations:
- 🏭 **Daikibo Factory Meiyo** (Tokyo, Japan)
- 🏭 **Daikibo Factory Seiko** (Osaka, Japan)  
- 🏭 **Daikibo Berlin** (Berlin, Germany)
- 🏭 **Daikibo Shenzhen** (Shenzhen, China)

Each facility operates 9 different types of industrial machines that send telemetry data every 10 minutes.

## Project Tasks

### Task 1: Manufacturing Downtime Analysis 📊

**Objective**: Analyze telemetry data to identify:
- Which factory location experiences the most machine failures
- Which specific machines break down most frequently at that location

**Data Source**: `daikibo-telemetry-data.json` (May 2021 telemetry data)

**Analysis Steps**:
1. Import telemetry data into Tableau
2. Create calculated field "Unhealthy" (10-minute downtime intervals)
3. Build visualization: "Down Time per Factory" 
4. Build visualization: "Down Time per Device Type"
5. Create interactive dashboard with factory filtering capability
6. Identify highest-downtime factory and machine types

### Task 2: Gender Pay Equity Investigation ⚖️

**Objective**: Investigate internal complaints about gender-based salary inequality

**Data Source**: `Equality Table.xlsx` (Forensic team's processed compensation data)

**Analysis Steps**:
1. Review equality scores by factory and job role
2. Create classification system for equality assessment:
   - **Fair**: Equality score ±10
   - **Unfair**: Equality score <-10 OR >10  
   - **Highly Discriminative**: Equality score <-20 OR >20
3. Generate comprehensive equality classification report

## Tools & Technologies

- **Tableau Desktop** - Data visualization and dashboard creation
- **Microsoft Excel** - Data classification and analysis
- **JSON/CSV** - Data import and processing


## Key Findings

### Manufacturing Analysis
- **Highest Downtime Factory**: [To be determined from analysis]
- **Most Problematic Machines**: [To be determined from analysis]
- **Total Downtime Impact**: [Quantified in dashboard]

### Gender Pay Equity Analysis
- **Fair Compensation Roles**: [Count and percentage]
- **Unfair Compensation Issues**: [Identified problem areas]
- **Highly Discriminative Cases**: [Critical issues requiring immediate attention]

## How to Reproduce

### Prerequisites
- Tableau Desktop (free trial available)
- Microsoft Excel
- Downloaded data files from project resources

2. **Manufacturing Analysis**
   - Install Tableau Desktop
   - Import `daikibo-telemetry-data.json`
   - Follow analysis steps in Task Guide.pdf
   - Create dashboard and export screenshot

3. **Equity Analysis**
   - Open `Equality Table.xlsx`
   - Add classification column using provided criteria
   - Save updated analysis

## Results & Business Impact

### Manufacturing Recommendations
- Targeted maintenance programs for highest-downtime factory
- Predictive maintenance implementation for problematic machine types
- Resource allocation optimization based on failure patterns

### Equity Assessment Outcomes  
- Identification of job roles requiring salary adjustment
- Factory-specific compensation review priorities
- Policy recommendations for fair compensation practices

**Project Status**: Completed  
**Last Updated**: September 2025  
**Analyst**: [Your Name]  
**Client**: Daikibo Industrials
