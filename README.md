# StreamingData.com

A web application for visualizing Spotify's most streamed songs through interactive charts.

## Features

- **Home Page**: Presents information about the team and supervisor with a stylish design.
- **Graph Page**: Offers dynamic charting with multiple types (Bar, Line, Pie, Doughnut, Radar, Polar Area).
- **Interactive Charts**: Change chart types and see real-time updates.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/StreamingData.com.git
    cd StreamingData.com
    ```

2. **Set Up VS Code:**
    - **Install Extensions**:
        - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): For live reloading of changes.
        - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv): For CSV parsing and visualization.
    - **Open Project**: Launch VS Code and open the project folder: `code .`

3. **Run the Project**:
    - Right-click `Home.html` in VS Code.
    - Select `Open with Live Server` to view the application in your browser.

## Usage

- **Home Page**:
    - **Overview**: Provides team and supervisor details.
    - **Design**: Features a hero image and styled sections.

    ![Screenshot 2024-07-21 122130](https://github.com/user-attachments/assets/9cabc6d7-8af5-4c42-9282-8534b50498b6)

- **Graph Page**:
    - **Chart Selection**: Choose different chart types from the dropdown menu.
    - **Real-Time Data**: Displays data from `data.csv`, with different chart types updating dynamically.

    ![Screenshot 2024-07-21 122143](https://github.com/user-attachments/assets/7a0a4b51-40df-4ff5-a9ee-c5ce31eb8bb7)

## Code Explanation

### `Home.html`

Sets up the main structure of the web page:
- **Navigation Bar**: Includes links to Home and Graph pages.
- **Hero Image**: Displays a cover image with a stylish overlay.
- **Team and Supervisor Sections**: Shows details about the project team and supervisor.
- **Footer**: Contains a copyright notice.

### `Graph.html`

Handles the interactive chart display:
- **Dropdown Menu**: Allows users to select the type of chart to display.
- **Chart Rendering**: Uses Chart.js to render the selected chart type with data from `data.csv`.
- **Data Parsing**: Utilizes PapaParse to fetch and parse CSV data.
- **Dynamic Background**: Changes the background image based on the selected chart type.

#### JavaScript Code

- **Chart Creation**: Initializes and configures the chart based on the selected type.
- **Data Handling**: Fetches data from `data.csv`, updates chart data, and applies random colors.
- **Chart Update**: Updates the chart when the user changes the chart type from the dropdown.

## Technologies Used

- **HTML/CSS**: For page structure and styling.
- **Bootstrap**: For responsive design and navigation.
- **Chart.js**: For creating interactive charts.
- **PapaParse**: For parsing CSV data.

## Team

- **KOUSHIK BHARADWAJ R (4MH21CS041)**
- **M P CHANDAN (4MH21CS045)**
- **PRADEEP T R (4MH21CS068)**
- **CHINMAY GOWDA B S (4MH21CS015)**

## Supervisor

- **Prof. Victor Ikechukwu Agughasi**

