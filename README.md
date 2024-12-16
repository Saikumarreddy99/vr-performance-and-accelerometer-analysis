# VR Performance and Accelerometer Data Analysis

This repository contains two parts of the project aimed at analyzing virtual reality (VR) performance conditioned on cognitive function and accelerometer data to produce meaningful movement measures for stroke survivors.

---

## Project Overview

### Part 1: Hypothesis Testing and Statistical Analysis
- **Objective**: Assess within-VR performance of participants conditioned on cognitive function using statistical measures.
- **Tasks**:
   - Compute descriptive statistics and report results.
   - Analyze task completion times and cognitive scores.
   - Conduct Spearman correlation analysis and create scatter plots.
   - Propose new quantitative measures correlating cognitive function with VR task performance.

### Part 2: Accelerometer Data Analysis
- **Objective**: Analyze accelerometer data from stroke survivors to compare conventional approaches with movement measures (M2).
- **Tasks**:
   - Process accelerometer data to compute movement measures.
   - Generate scatter plots and fit linear regression lines.
   - Compare M2 with conventional assessments like Fugl-Meyer Assessment (FMA) and Motor Activity Log (MAL).
   - Discuss advantages, limitations, and practical applications of movement measures.

---

## Folder Structure

### Part 1: Hypothesis Testing and Statistics
- **Files**:
   - `part1-assignment-analysis.ipynb` - Python notebook containing statistical analysis, correlation computation, and visualizations.
   - `part1-assignment-report.pdf` - Professional report documenting results, APA-formatted statistics, and interpretations.
   - `part1-assignment-goals-and-instructions.pptx` - Assignment goals, and tasks.
   - **Datasets**:
     - `C008_SimpleStew_CompletedStepsData.csv`
     - `C009_SimpleStew_CompletedStepsData.csv`
     - `C013_SimpleStew_CompletedStepsData.csv`
     - `C016_SimpleStew_CompletedStepsData.csv`
     - `Assessments.xlsx`

### Part 2: Accelerometer Analysis
- **Files**:
   - `part2-accelerometer-analysis.py` - Python script for accelerometer data processing, scatter plot generation, and linear regression.
   - `part2-conventional-vs-physical-data.pptx` - Presentation comparing accelerometer-based measures (M2) with conventional approaches (FMA, MAL). Assignment goals, and tasks.
   - `part2-conventional-vs-physical-report.pdf` - Detailed report with analysis, visualizations, and pros/cons discussion.
   - **Datasets**:
     - `patients.csv` - Accelerometer data file.
     - `13.zip` to `33.zip` - Processed accelerometer files for analysis.

---

## Key Insights

### Part 1:
- Weak correlation between cognitive function (Block Design Scores) and VR task completion times.
- **New Metrics**:
   - Average time per step.
   - Number of pauses (significantly correlating with cognitive function).

### Part 2:
- Movement measures (M2) derived from accelerometer data provide clinically meaningful insights compared to conventional approaches.
- Scatter plots and regression analysis highlight differences between movement measures and traditional assessments like FMA.

---

## Tools and Technologies
- **Programming**: Python, Jupyter Notebook
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Environment**: PyCharm CE
- **Data Formats**: CSV, Excel, ZIP

---

## How to Run

### Part 1:
1. Open `part1-assignment-analysis.ipynb` in Jupyter Notebook.
2. Ensure all CSV and Excel datasets are in the same directory.
3. Run all cells for statistical results and visualizations.

### Part 2:
1. Run `part2-accelerometer-analysis.py` using PyCharm CE or any compatible Python IDE.
2. Place `patients.csv` and all ZIP files in the project directory.
3. Analyze the generated scatter plots and regression outputs.

---

## Authors
- Keerthika Sunchu  
- Meghana Darla
- Ramya Keerthi 

---

## Contact
For questions or suggestions, please contact:  
**Keerthika Sunchu** - [ksunchu@iu.edu](mailto:ksunchu@iu.edu)  
