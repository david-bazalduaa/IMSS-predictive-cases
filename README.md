# Analysis of Morbidity and Health Service Usage at IMSS

## Project Objective
The objective of this project is to analyze morbidity patterns and the use of health services at IMSS to identify trends, behaviors, and factors associated with service utilization. This analysis aims to provide valuable insights to improve resource planning, optimize offered services, and develop more effective public health strategies.

## Business Approach
This project takes a strategic approach to:
- Optimize the allocation of medical resources (staff, supplies, infrastructure) based on demand.
- Identify and predict trends in diseases and service usage to improve planning and response to emerging needs.
- Reduce operational costs by identifying inefficiencies in healthcare service delivery.
- Enhance patient care and satisfaction through a data-driven approach that ensures the availability of critical services.

## Methodology
The project will be developed in several key stages:

### 1. Data Collection
- **Morbidity Data:** Public IMSS datasets containing information on the most common treated diseases (by service type: outpatient consultation, hospitalization, emergencies) and broken down by variables such as age, gender, region, and time.
- **Service Usage Data:** Detailed statistics on the utilization of health services at IMSS, including the number of consultations, hospitalizations, surgeries, emergencies, and other procedures.
- **Sociodemographic Data:** Information about the insured population, including distribution by age, gender, geographic location, and socioeconomic conditions.

### 2. Data Cleaning and Preparation
- Processing data to remove duplicates, handle missing values, and correct errors.
- Normalizing data to ensure consistency in key variables (e.g., standardizing disease codes).

### 3. Exploratory Data Analysis (EDA)
- Data visualization to identify morbidity patterns based on age, gender, region, and service type.
- Temporal analysis to detect trends in disease prevalence and service usage over time.
- Geospatial analysis to visualize the distribution of diseases and service utilization by region.

### 4. Predictive Modeling
- Development of predictive models to anticipate healthcare service demand using Machine Learning techniques such as multiple linear regression, decision trees, and neural networks.
- Application of classification models to predict the risk of certain diseases based on demographic characteristics and healthcare service usage behavior.

## Technologies Used
- **Languages:** Python, R
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook, Power BI 

## Installation and Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/youruser/imss-analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```sh
   python main.py
   ```


