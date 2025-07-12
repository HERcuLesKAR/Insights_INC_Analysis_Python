
# Insights INC Project Performance Dashboard

## Overview
This project aims to analyze and visualize the performance of various projects using data from multiple sources. The data includes project details such as timelines, application names, revenue, and delay reasons. The goal is to create an interactive dashboard that provides insights into project status, revenue breakdown, and performance across different verticals.

## Project Structure

- **`Insights INC. - Project Details - Dataset.xlsx`**: The main dataset containing project details and delay reasons.
- **`Test1.ipynb`**: Jupyter notebook for loading, cleaning, and merging the dataset. It generates an interactive dashboard with visualizations using Gradio.
- **`Test2.ipynb`**: A more advanced version of the notebook with detailed KPI metrics and visualizations for project performance.

## Features

1. **Project Status Breakdown**: A pie chart visualizing the ratio of delayed vs. on-time projects.
2. **Application-wise Project and Revenue Breakdown**: Bar charts to show projects and revenue by application.
3. **Vertical Head Performance**: A bar chart representing revenue performance across different vertical heads.
4. **WIP Projects Breakdown**: A bar chart categorizing the status of work-in-progress (WIP) projects by their age.

## Technologies Used
- Python
- Pandas (for data manipulation)
- Matplotlib (for plotting visualizations)
- Gradio (for creating the interactive dashboard)

## Installation & Setup

### Requirements:
- Python 3.6+
- Install required packages using:
  ```bash
  pip install pandas matplotlib gradio
  ```

### Steps to Run:
1. Download the dataset `Insights INC. - Project Details - Dataset.xlsx`.
2. Run the Jupyter notebooks (`Test1.ipynb` or `Test2.ipynb`) in a Jupyter environment.
3. The dashboard will be launched in your browser where you can interact with the project performance visualizations.

## How to Use
- **Interactive Dashboard**: The dashboard presents four visualizations that give a clear picture of project performance.
  - View the **status** of projects (Delayed vs. On-time).
  - Check the **revenue** and **project counts** by application.
  - Review the performance of each **vertical head**.
  - Analyze the **ageing categories** of WIP projects.

## Contributing
Feel free to fork this project and submit issues or pull requests. Contributions are always welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

