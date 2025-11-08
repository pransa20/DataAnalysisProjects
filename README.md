# Data Analysis Projects

This repository contains a collection of data analysis projects focusing on various topics, including earthquake visualization in Nepal, tourism trends in Nepal, and content analysis of YouTube Kids videos. Each project is self-contained within its own directory.

## Projects Included

### 1. Nepal Earthquake Visualization
- **Description**: This project analyzes earthquake data in Nepal, visualizing seismic activity using interactive maps and charts. It leverages data from the USGS API to provide insights into earthquake magnitudes, locations, and frequency.
- **Technologies**: Python, Pandas, Matplotlib, Folium, Jupyter Notebook.
- **Location**: `nepal_earthquake_visualization/`

### 2. Nepal Tourism Trends
- **Description**: This project explores tourism data related to Nepal to identify trends, popular destinations, and factors influencing tourist arrivals. It aims to provide insights for tourism development and marketing strategies.
- **Technologies**: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook.
- **Location**: `nepal_tourism_trends/`

### 3. YouTube Kids Content Analysis
- **Description**: This project analyzes content available on YouTube Kids to identify patterns, popular themes, and potential issues related to child-friendly content. It uses the YouTube Data API to collect video and comment data for analysis.
- **Technologies**: Python, Pandas, Matplotlib, Seaborn, YouTube Data API, Jupyter Notebook.
- **Location**: `yt_kids_content_analysis/`

## Getting Started

To run these projects locally, follow these steps:

### Prerequisites

- Python 3.x installed
- Git installed

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/pransa20/DataAnalysisProjects.git
    cd DataAnalysisProjects
    ```

2.  **Navigate to a project directory**:
    For example, for the Nepal Earthquake Visualization project:
    ```bash
    cd nepal_earthquake_visualization
    ```

3.  **Install dependencies**:
    Each project has its own `requirements.txt` file. Install them using pip:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
    This will open a new tab in your web browser. Navigate to the respective project folder and open `main.ipynb`.

5.  **Execute Notebook Cells**:
    Run all cells in the `main.ipynb` notebook to see the analysis and visualizations.

### API Keys (if applicable)

- **YouTube Kids Content Analysis**: This project requires a YouTube Data API key. Please refer to the project's specific `README.md` or the notebook for instructions on how to obtain and use it.
- **Nepal Air Quality Analysis**: (If you decide to add this project later) This project would require an API key for air quality data.

## Contributing

If you'd like to contribute to these projects, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (if you create one).
