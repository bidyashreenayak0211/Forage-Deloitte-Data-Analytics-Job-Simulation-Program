# Forage Deloitte Data Analytics Job Simulation Program

## Task 1: Analyzing Telemetry Data in Tableau
Your task is to analyze the telemetry data collected by Daikibo using Tableau. Follow these steps:

1. **Download and Install Tableau**
   - Download the free trial of Tableau from the link provided in the Resources.
   - Install Tableau on your computer and register an account using the same email used to download the software.

2. **Import Data into Tableau**
   - Download the `daikibo-telemetry-data.json.zip` file from the Resources.
   - Unzip the file.
   - Import the extracted JSON file into Tableau.

3. **Create Calculated Measure**
   - Create a calculated measure field called **"Unhealthy"**.
   - Assign a value of **10** for every unhealthy status (representing 10 minutes of potential downtime since the previous message).

4. **Create Visualizations**
   - **Bar Chart: "Down Time per Factory"**
   - **New Sheet: "Down Time per Device Type"** (another bar chart)

5. **Build a Dashboard**
   - Include both bar charts created in the previous step.
   - Set the first chart (**"Down Time per Factory"**) to act as a filter.
   - Selecting a factory in the first chart should filter the downtime of machines in that factory in the second chart.

6. **Final Step: Submission**
   - Select the factory with the most downtime (click on its bar).
   - Take a **screenshot** of the dashboard.
   - Upload the screenshot as your submission for this task.

Refer to the **step-by-step Task Guide PDF** in the Resources for detailed instructions.

![Task 1 - Delloite Data Analytics Virtual Internship Dashboard](https://github.com/user-attachments/assets/cc495b92-a0a2-459f-8dfb-b0369fb4c424)

---

## Task 2: Editing the Equality Table in Excel
We have processed employee compensation data and provided an Excel file (**Equality Table.xlsx**) containing 3 columns:
- **Factory**
- **Job Role**
- **Equality Score** (integer ranging from -100 to +100, where 0 is ideal)

### Your Task:
1. **Add a 4th Column: "Equality class"**
   - Classify the **Equality Score** into 3 categories:
     - **Fair** (Score between -10 and +10, inclusive)
     - **Unfair** (Score between -20 and -11 OR between 11 and 20)
     - **Highly Discriminative** (Score below -20 OR above 20)

2. **Examples of Classification:**
   - **6 → Fair**
   - **-9 → Unfair**
   - **-30 → Highly Discriminative**

3. **Formula to Use in Excel:**
   ```excel
   =IF(ABS(C2) <= 10, "Fair", IF(ABS(C2) <= 20, "Unfair", "Highly Discriminative"))
   ```
   - Apply this formula in the **Equality class** column for each row.

4. **Save and Upload**
   - Save the edited **Equality Table.xlsx** file.
   - Upload the updated version as your submission.

Refer to the **Resources** for the necessary files and further instructions.

---

## Certificate of Completion

![image](https://github.com/user-attachments/assets/f3a51678-e2d5-4f4c-8ae4-2ee080990693)

