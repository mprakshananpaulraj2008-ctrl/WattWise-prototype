# ⚡ WattWise – Smart Energy Monitoring & Waste Detection

**Smarter Energy. Sustainable Future.**

WattWise is an intelligent energy monitoring platform designed to help educational institutions, offices, hostels, and other buildings monitor electricity consumption, identify energy wastage, and improve energy efficiency through data-driven insights.

## 🌍 Problem Statement

Electricity wastage is a major challenge in institutions and commercial buildings. Lights, fans, air conditioners, and other electrical equipment are often left running unnecessarily, resulting in increased electricity bills and environmental impact.

Traditional energy monitoring systems may not provide users with clear insights into where and when electricity is being wasted.

## 💡 Our Solution

WattWise provides a centralized dashboard that visualizes energy consumption, estimates electricity costs, detects unusual usage patterns, and generates intelligent energy-saving recommendations.

The platform helps users make informed decisions and encourages responsible electricity consumption.

## ✨ Key Features

### 1. Energy Monitoring
- Monitor simulated electricity consumption.
- View daily, weekly, and monthly energy usage.
- Identify peak electricity consumption periods.

### 2. Smart Dashboard
- Total energy consumption (kWh).
- Estimated electricity bill (₹).
- Energy saved (kWh).
- Estimated carbon emissions (kg CO₂).

### 3. AI Energy Analyzer
- Identifies unusual electricity consumption patterns.
- Highlights possible energy wastage.
- Analyzes simulated energy usage data.
- Generates energy-saving insights.

### 4. AI-Powered Recommendations
- Provides intelligent energy-saving suggestions.
- Identifies potential areas of electricity wastage.
- Displays recommendation priorities and estimated savings.

### 5. Building Comparison
Compare energy consumption across different areas:
- Academic Block
- Computer Laboratory
- Library
- Hostel

### 6. Reports & Analytics
- Visualize energy consumption trends.
- Estimate electricity expenses.
- Download energy reports in CSV format.

### 7. Custom Settings
- Adjust electricity tariff.
- Select buildings.
- Manage notification preferences.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive design |
| JavaScript | Functionality and interactions |
| Chart.js | Data visualization |
| SVG | Visual illustrations |

## 🏗️ System Architecture

The current prototype uses a frontend-based architecture with simulated energy consumption data.

```text
              USER
                |
                v
         WATTWISE WEB APP
                |
       HTML + CSS + JavaScript
                |
                v
        ENERGY DATA MODULE
                |
        +-------+--------+
        |                |
        v                v
   Data Analysis     Dashboard
        |                |
        v                v
  Usage
