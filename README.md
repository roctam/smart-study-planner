# Smart Study Planner

## Project Overview
Smart Study Planner is an AI application designed to help students organize their assignments and exam preparation. It estimates task completion times and creates a study schedule based on deadlines and available study hours.

## AI Areas
1. **Classical Machine Learning:** A regression model predicts how long a study task may take.
2. **Search and Planning:** A planning algorithm uses the predicted durations to arrange tasks around deadlines and available time.

The predicted duration from the machine-learning model is used as input to the planning algorithm.

## Planned Features
- Add study tasks and deadlines.
- Set task complexity and available study time.
- Estimate task durations.
- Generate a study schedule.
- Identify tasks that may not fit before their deadlines.

## Technology
- Python
- scikit-learn
- Streamlit
- Git and GitHub

## Data
The initial version will use a generated synthetic dataset of study tasks. The data and its limitations will be documented in the project.

## Evaluation
The regression model will be evaluated using Mean Absolute Error (MAE) and compared with a simple mean-duration baseline. The planner will be tested for deadline compliance and available-time constraints.

## Project Status
Proposal and planning stage. Implementation and evaluation are planned as part of the course project.

## Author
Mani Rostami
