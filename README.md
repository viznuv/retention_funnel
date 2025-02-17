# User Journey Analysis with Retentioneering

This project performs user journey analysis using the **Retentioneering** library. It processes event-stream data, visualizes user behavior, and applies various analytical techniques such as **funnel analysis, step matrix visualization, clustering, and trajectory analysis** to better understand user retention and conversion paths.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Code Description](#code-description)
- [Example Output Interpretation](#example-output-interpretation)
- [License](#license)
- [Contact](#contact)

---

## Overview

This repository contains a Python script for analyzing user event data collected from a digital platform. It utilizes **Retentioneering**, a powerful tool for **behavioral data analysis**, to:

- **Track user interactions**
- **Visualize user paths**
- **Identify conversion bottlenecks**
- **Cluster users based on their activity**
- **Analyze key decision points in user retention**
- **Detect trends in user behavior over time**

The script loads data from a `.dat` file, cleans it, and processes it through multiple stages of user journey analysis.

---

## Features

- **Eventstream Creation:** Loads event data and converts it into an event stream.
- **Step Matrix Analysis:** Visualizes how users move through different touchpoints.
- **Short Path Filtering:** Removes users with minimal activity to refine analysis.
- **Sankey Diagrams:** Displays the flow of user actions.
- **Funnel Analysis:** Identifies conversion rates across various stages.
- **User Lifetime Analysis:** Examines session duration and retention trends.
- **Trajectory Clustering:** Uses machine learning to segment users based on behavior.
- **Cluster Projection:** Uses UMAP to visualize user clusters.

---

## Prerequisites

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Retentioneering](https://github.com/retentioneering/retentioneering)

---

## Installation
pip install pandas matplotlib retentioneering

1. **Clone the repository:**
   ```bash
   git clone https://github.com/viznuv/retention_funnel.git
   cd retention_funnel
