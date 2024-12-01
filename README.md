# Power BI Dashboard for Call Center Analysis

## Overview
This repository contains a Power BI dashboard designed to help call centers visualize and analyze key performance metrics. The dashboard provides insights into customer and agent behavior, helping management track trends in call volume, resolution rates, customer satisfaction, agent performance, and efficiency.

The dashboard includes various metrics, such as:
- Call volume analysis (answered vs. abandoned calls)
- Call resolution rates
- Speed of answer and average talk duration
- Agent performance evaluation
- Customer satisfaction trends

This project aims to enable data-driven decision-making in call centers, optimizing both agent performance and customer experience.

## Key Features
- **Total Calls**: Count of all calls in the dataset.
- **Answered vs. Abandoned Calls**: Compare the number of calls that were answered and those abandoned.
- **Speed of Answer**: Calculate the average time taken to answer calls.
- **Average Talk Duration**: Calculate the average duration of calls.
- **Agent Performance**: Visualize agent performance based on the number of calls handled and their resolution rates.
- **Customer Satisfaction**: Track customer satisfaction ratings and analyze trends over time.

## Technologies Used
- **Power BI**: Visualization and reporting tool used to build interactive dashboards.
- **Excel/CSV**: Data input format containing call center data.

## Setup Instructions
To get started with this project, follow these steps:

1. Clone or download this repository to your local machine.
2. Open the Power BI file (`Call_Center_Dashboard.pbix`) using Power BI Desktop.
3. Load your dataset (ensure it includes columns such as `Call Id`, `Agent`, `Date`, `Time`, `Answered`, `Resolved`, `Satisfaction Rating`, and others).
4. Review and customize the visuals based on your specific dataset or requirements (e.g., handling date/time formats or adjusting satisfaction rating scales).

## Data Structure
The dataset consists of the following columns:

- **Call Id**: A unique identifier for each call.
- **Agent**: The name of the agent handling the call.
- **Date**: The date on which the call took place.
- **Time**: The time at which the call occurred.
- **Topic**: The main topic of the call (e.g., "Contract related").
- **Answered**: Whether the call was answered (Y/N).
- **Resolved**: Whether the issue was resolved (Y/N).
- **Speed of Answer in Seconds**: Time taken to answer the call, in seconds.
- **AvgTalkDuration**: Average duration of the call (in `hh:mm:ss` format).
- **Satisfaction Rating**: Customer satisfaction rating for the call (scale of 1-5).

## Features & Visuals
- **KPI Cards**: Total calls, answered vs. abandoned calls, resolution rate, and average satisfaction.
- **Time-Based Metrics**: Line chart tracking calls over time and average satisfaction.
- **Agent Performance**: Bar chart visualizing calls handled by each agent and their resolution rates.
- **Scatter Plot (Agent Performance Quadrant)**: Shows agent performance by comparing the number of calls handled and the average talk duration.
- **Customer Satisfaction Trends**: Analyze satisfaction over time and by call topic.

## How to Contribute
We welcome contributions to improve this project! If you would like to help enhance the dashboard or add new features, please fork the repository, make your changes, and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any questions or feedback, feel free to open an issue or reach out to the repository owner.

