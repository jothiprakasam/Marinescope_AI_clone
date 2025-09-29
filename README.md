# Marinescope_AI

An AI-driven marine biodiversity platform that integrates data ingestion, processing, and visualization
for real-time insights.

## Repository Overview
This repository consist of the 4 main server System.
# Server 1 - Ingestion tool 
- This server is built on the Prefect Library Python.
- The prefect alows us to run the Task and Flows efficently which helps in collects oceanographic, biological, and sensor data from APIs and external sources.
- Centralized dashboard to configure and manage data flows.

# Server 2 - Python preprocessor tool 
- This preprocessor server is to Cleans, validates, and processes heterogeneous data (CSV, NetCDF, sensor stream).
- Metadata-based clustering for efficient organization and retrieval.
- This preprocessor server in implemented in core python ML library which is Pytorch and the logic is impplemented using ARIMA MODEL, ARIMA MODEL, Time series.

# Server 3 - 
## Solution Overview

**Marinescope_AI_clone** is a unified, scalable ecosystem designed to automate the collection, processing, and visualization of marine biodiversity data. Its main features include:

- **Automated Data Ingestion:** Collects oceanographic, biological, and sensor data from APIs and user-provided sources. An advanced dashboard pipelines the data and manages data flows.
- **Preprocessing & Clustering:** Cleans, validates, and processes heterogeneous datasets (CSV, NetCDF, sensor streams). Utilizes metadata-based clustering for efficient organization and retrieval.
- **Centralized Repository:** Supports taxonomy, otolith morphology, eDNA data, and WOD (World Ocean Database) data for comprehensive marine research.
- **Real-Time Monitoring & Updates:** Enables continuous marine biodiversity monitoring, with support for updating data and insights.
- **AI-Driven Processing:** Leverages machine learning for automated analysis, clustering, and visualization.
- **Interactive Visualization:** Presents processed data in intuitive dashboards for actionable insights.

## Repository Overview

- **Primary Language:** TypeScript (84.5%)
- **Other Languages:** Python (12%), CSS (3.1%), JavaScript (0.4%)
- **Default Branch:** `main`
- **Public Repository**

## Main Directories & Files

- [`app/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/app) - Main application code.
- [`components/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/components) - UI components and shared logic.
- [`hooks/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/hooks) - Custom React hooks for advanced state and data management.
- [`lib/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/lib) - Library code and utilities.
- [`public/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/public) - Static assets.
- [`styles/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/styles) - CSS and styling files.
- [`ingestion-tool-server/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/ingestion-tool-server) - Backend server for automated data ingestion.
- [`python-preprocessor-backend/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/python-preprocessor-backend) - Python backend for preprocessing and clustering.
- [`python-telegram-server/`](https://github.com/jothiprakasam/Marinescope_AI_clone/tree/main/python-telegram-server) - Python backend for Telegram integration.

**Config & Metadata Files:**
- [`package.json`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/package.json) / [`package-lock.json`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/package-lock.json)
- [`pnpm-lock.yaml`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/pnpm-lock.yaml)
- [`tsconfig.json`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/tsconfig.json)
- [`next.config.mjs`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/next.config.mjs)
- [`tailwind.config.js`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/tailwind.config.js)
- [`components.json`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/components.json)
- [`postcss.config.mjs`](https://github.com/jothiprakasam/Marinescope_AI_clone/blob/main/postcss.config.mjs)

## Getting Started

Install dependencies and run the project:

```bash or Powershell
npm install
npm run dev
```

## Features

- **Automated Data Ingestion:** Seamlessly collects and pipelines various marine data sources.
- **Preprocessing & Clustering:** Handles data cleaning, validation, and organizes data with metadata-based clustering.
- **Centralized Data Repository:** Stores taxonomy, otolith morphology, eDNA, and WOD data for easy retrieval and research.
- **AI-Powered Analysis:** Applies machine learning for insightful clustering and analysis.
- **Interactive Dashboards:** Visualizes real-time data for actionable marine biodiversity monitoring.
- **Python Microservices:** Supports data preprocessing and integration with platforms like Telegram.
- **Modular Frontend:** Built with reusable components in TypeScript and React.
- **Rapid UI Development:** Uses Tailwind CSS for fast and responsive design.

