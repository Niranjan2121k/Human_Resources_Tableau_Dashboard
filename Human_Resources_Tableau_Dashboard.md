**Human_Resources_Tableau_Dashboard**

## **1. Project Overview**
This project analyzes hospital employee data, focusing on hiring trends, terminations, gender distribution, education levels, and geographic workforce distribution. The goal is to provide insights that improve workforce management and optimize HR policies.

## **2. Dashboard Features**
The dashboard includes:
- **Interactive Filters:** Filter data by age, gender, state, and education level.
- **Geographic Visualizations:** Show workforce distribution across different locations.
- **Trend Analysis:** Identify hiring and termination trends over time.
- **Comparative Charts:** Compare gender and education distributions.
- **Key Metrics:** Display total active employees, hires, and terminations.

### **Hiring Trends by Year**  
This area chart illustrates the total number of employees hired each year, highlighting fluctuations in recruitment over time.  

- The trend shows periods of rapid hiring growth followed by sharp declines.  
- Peaks represent high recruitment phases, possibly due to expansion, seasonal hiring, or increased workforce demand.  
- Declines indicate reduced hiring activity, which could be influenced by economic conditions, budget constraints, or organizational changes.  
- The data is filtered by **Status (Hired), Gender (Male and Female), and Location (Branch and HQ)** to provide a more focused analysis of hiring trends.  

Understanding these patterns helps in workforce planning and optimizing hiring strategies for future growth.

<img width="1686" alt="Screenshot 2025-03-16 at 11 16 53 AM" src="https://github.com/user-attachments/assets/43b9584c-d008-4940-8a93-9397fafde52b" />

### **Termination Trends by Year**  
This area chart illustrates the number of employees who left the company each year, highlighting termination patterns over time.  

- The trend shows a sharp increase in terminations from 2017 onward, with fluctuations in later years.  
- Peaks indicate periods of high employee turnover, possibly due to layoffs, resignations, or company restructuring.  
- Periods of decline suggest improved retention strategies or lower workforce reductions.  
- Understanding these trends helps in assessing workforce stability and developing strategies to reduce unwanted attrition.  

<img width="1683" alt="Screenshot 2025-03-16 at 11 17 56 AM" src="https://github.com/user-attachments/assets/f9a48dfc-4ba0-4828-97c1-65ef0fe9f4f4" />

### **Employee Distribution and Terminations by Department**  
This stacked bar chart visualizes the total number of employees in each department, with a breakdown of active and terminated employees.  

- The **green section** represents active employees.  
- The **purple section** represents terminated employees.  

#### **Key Insights:**  
- **Operations** has the largest workforce with 2,429 active employees and 289 terminations, indicating a relatively stable department despite some turnover.  
- **Sales** and **Customer Service** have significant employee counts but also relatively high terminations (201 and 184, respectively), suggesting a higher turnover rate in these roles.  
- **HR** has the smallest workforce, with only 152 active employees and 20 terminations, indicating a stable department with minimal attrition.  
- Departments with higher termination rates may require deeper analysis to understand the causes, such as job satisfaction, workload, or organizational changes.  

This visualization provides a clear comparison of workforce stability across departments, helping in strategic workforce planning.  
<img width="1631" alt="Screenshot 2025-03-16 at 11 23 52 AM" src="https://github.com/user-attachments/assets/ed4f458f-11e3-4ffb-b0c3-89db8722a993" />

### **Employee Count by Job Title**  
This horizontal bar chart displays the total number of employees by job title, highlighting the most and least populated roles within the organization.  

#### **Key Insights:**  
- **Logistics Coordinator (1,061 employees) and Inventory Specialist (1,044 employees)** are the most common job roles, suggesting a strong focus on supply chain and inventory management.  
- **Sales Representatives (740 employees) and Software Developers (627 employees)** are also among the top roles, reflecting the organization's emphasis on sales and technology.  
- **Managerial roles, such as HR Manager (1 employee) and Finance Manager (9 employees),** have the fewest employees, indicating a lean leadership structure in these areas.  
- The **green bars** highlight the top two job roles with the highest employee count.  
- Other job roles are represented in **gray**, showing a more evenly distributed workforce across various functions.  

This visualization helps in workforce planning, identifying critical job functions, and understanding hiring trends within the company.  

<img src="https://github.com/user-attachments/assets/your-image-id" />

### **Employee Distribution by State**  
This horizontal bar chart displays the number of employees in different U.S. states, highlighting the states with the highest workforce concentration.

#### **Key Insights:**  
- **New York (6,270 employees)** has the highest employee concentration, significantly surpassing other states.  
- **Michigan (976 employees)** follows as the second-largest state in terms of employee count.  
- Other states, including **Pennsylvania (435), North Carolina (430), and Illinois (285),** have moderate workforce distributions.  
- States with the lowest workforce presence include **Virginia (180) and West Virginia (103).**  
- The **green bars** highlight the two states with the highest number of employees, while **gray bars** represent the remaining states.  

This visualization helps in understanding regional workforce distribution and identifying key employment hubs within the organization.  

<img width="1687" alt="Screenshot 2025-03-16 at 11 27 43 AM" src="https://github.com/user-attachments/assets/a0f0d431-a037-4264-bb99-b205ca2f8be0" />

### **Employee Distribution in Michigan Cities**  
This bar chart presents the distribution of employees in the top three cities within Michigan.

#### **Key Insights:**  
- **Detroit (364 employees)** has the highest workforce concentration in Michigan.  
- **Grand Rapids (313 employees)** follows closely as the second-largest employment hub.  
- **Warren (299 employees)** ranks third in terms of employee count.  
- The **green bar** highlights the city with the highest number of employees, while **gray bars** represent the other cities.  

This visualization provides a clear view of workforce concentration across key Michigan cities, which can help with strategic workforce planning and resource allocation.  

<img width="1688" alt="Screenshot 2025-03-16 at 11 28 35 AM" src="https://github.com/user-attachments/assets/22a620b0-d7ac-4bf2-acd8-54788b42a4f1" />

### **Headquarters vs. Branch Employee Distribution with Hover Interaction**  

This visualization compares the employee distribution between the **Headquarters (HQ)** and **Branch** locations.  

#### **Hover Interaction Feature:**  
- When hovering over the **Branch bar**, a tooltip appears showing the **total number of employees (2,680)** and their **percentage (30%)** of the total workforce.  
- The tooltip further breaks down branch employees by **state**, highlighting:  
  - **Michigan: 976 employees**  
  - **Pennsylvania: 435 employees**  
  - **North Carolina: 430 employees**  
  - **Illinois: 285 employees**  
  - **Ohio: 271 employees**  
  - **Virginia: 180 employees**  
  - **West Virginia: 103 employees**  
- Similarly, hovering over the **HQ bar** shows its **70.06%** workforce share.  

This interactive feature allows users to explore workforce distribution dynamically by hovering over different bars.  

<img width="1688" alt="Screenshot 2025-03-16 at 11 29 44 AM" src="https://github.com/user-attachments/assets/f4e2b0dd-2ef6-4aa6-9632-1ae6f68f0f84" />

### **Employee Distribution Across States - Pennsylvania Focus**

This visualization presents an interactive **map of employee distribution** across multiple states. The **size of the circles** represents the number of employees in each city, while **hovering over a state** reveals detailed statistics.

#### **Key Insights for Pennsylvania**
- **Total Employees:** **435**
- **Breakdown by City:**
  - **Philadelphia:** 164 employees
  - **Allentown:** 147 employees
  - **Pittsburgh:** 124 employees

#### **Interactive Features**
- Hovering over **Pennsylvania** highlights the state in color.
- A tooltip displays the **total number of employees** along with a **bar chart breakdown** of the **top three cities** by employee count.
- Other states also contain employee data represented by circles, allowing for comparisons.

This map provides a **geographic visualization** of workforce distribution, helping in regional analysis and decision-making.

<img width="1642" alt="Screenshot 2025-03-16 at 11 32 07 AM" src="https://github.com/user-attachments/assets/98c29555-78e9-4b7a-ae5a-9aa221cfed0d" />

### **Employee Hiring and Termination by Gender**

This visualization presents two **donut charts**, one for **female employees** and another for **male employees**, displaying their **hiring and termination rates**.

#### **Key Insights**
- **Top Chart (Female Employees)**
  - **Hired:** 89%
  - **Terminated:** 11%
  - **Total Female Representation:** 46%

- **Bottom Chart (Male Employees)**
  - **Hired:** 89%
  - **Terminated:** 11%
  - **Total Male Representation:** 54%

#### **Observations**
- The **hiring and termination percentages** are identical for both genders.
- There is a **slightly higher proportion of male employees** (54%) compared to female employees (46%).
- The **low termination rate (11%)** indicates overall retention stability.

This breakdown provides a **gender-based perspective on workforce dynamics**, helping to analyze **hiring equity and retention trends**.

<img width="1700" alt="Screenshot 2025-03-16 at 11 34 05 AM" src="https://github.com/user-attachments/assets/b8a3771e-5b95-4bb2-bca6-446e2658da5a" />

### **Employee Distribution by Age and Education Level**

This **bubble chart** visualizes the distribution of employees based on their **age groups** and **educational qualifications**. 

#### **Axes Explanation**
- **Y-axis (Left Side):** Age groups categorized as:
  - **< 25**
  - **25-34**
  - **35-44**
  - **45-54**
  - **> 55**
  
- **X-axis (Top Labels):** Education levels:
  - **H_Sch** (High School)
  - **Bachelor**
  - **Master**
  - **PhD**

#### **Observations**
- The **largest bubble** (highlighted in green) represents employees aged **35-44** with a **Bachelor’s degree**, indicating this is the **most common age-education combination**.
- The **25-34** age group also has a significant number of employees with **Bachelor’s degrees**.
- Employees with **Master’s and PhD degrees** are less frequent, indicated by smaller bubbles.
- The **High School education category** has a relatively balanced distribution across multiple age groups but is less dominant than the Bachelor’s degree category.

#### **Key Insights**
- The workforce is **heavily concentrated in the 25-44 age range**.
- A **Bachelor’s degree is the most common educational qualification**.
- Higher education levels (Master’s & PhD) are **less prevalent**, possibly due to industry-specific requirements or job roles.

This visualization helps in understanding **workforce demographics** based on **education level and age**, which can be useful for **hiring strategies and career development planning**.

<img width="1696" alt="Screenshot 2025-03-16 at 11 35 44 AM" src="https://github.com/user-attachments/assets/361f5719-fd3e-4bcf-8914-85b97e166d5a" />

### **Employee Distribution by Age Group (Bar Chart)**

This **horizontal bar chart** visualizes the number of employees in different **age groups**.

#### **Observations**
- The **35-44 age group** has the highest number of employees, represented by the longest green bar.
- The **25-34** and **45-54** age groups also have a significant number of employees.
- The **<25** and **>55** age groups have the least representation, indicated by shorter bars.

#### **Key Insights**
- The majority of employees fall within the **35-44 age range**, making it the dominant workforce group.
- The **youngest (<25) and oldest (>55) groups** have the fewest employees, which could indicate:
  - Fewer young professionals entering the company.
  - Older employees leaving or retiring earlier.
- Understanding this distribution can help in **recruitment planning, workforce retention, and succession planning**.

This visualization highlights **workforce age demographics**, offering insights for **HR strategies and company policies**.

<img width="1524" alt="Screenshot 2025-03-16 at 11 37 34 AM" src="https://github.com/user-attachments/assets/aa73de51-34e4-4e36-bcab-0b58f567fb18" />

### **Employee Distribution by Education Level (Bar Chart)**

This **vertical bar chart** represents the number of employees based on their **education level**.

#### **Observations**
- Employees with a **Bachelor's degree** form the largest group, represented by the tallest green bar.
- The **High School** and **Master’s degree** categories have a moderate number of employees.
- Employees with a **PhD** form the smallest group.

#### **Key Insights**
- The dominance of **Bachelor’s degree holders** suggests that most roles in the company require at least an undergraduate degree.
- The relatively lower number of **PhD holders** could indicate that fewer specialized research roles exist.
- The company may focus on hiring professionals with **Bachelor’s and Master’s degrees**, with limited demand for PhD-level expertise.

This visualization highlights the **workforce's education distribution**, which is valuable for **talent acquisition and workforce development strategies**.

<img width="1529" alt="Screenshot 2025-03-16 at 11 39 39 AM" src="https://github.com/user-attachments/assets/a87cbbf5-d425-4a7c-bc0b-6dc435811106" />

### **Performance Distribution by Education Level (Square Chart)**

This **square chart** visualizes employee performance ratings across different **education levels**.

#### **Structure**
- **Columns** represent different **education levels**: High School (H_Sch), Bachelor, Master, and PhD.
- **Rows** represent different **performance ratings**: Excellent, Good, Satisfactory, and Needs Improvement.
- The **size of each square** represents the proportion of employees in that category.
- Some squares contain **percentage values**, highlighting significant proportions.

#### **Key Observations**
1. **Bachelor’s Degree Holders**:
   - **50%** of them fall into the **Good** performance category (largest proportion).
   - Other performance levels have smaller but varying proportions.

2. **PhD Holders**:
   - **48%** are in the **Excellent** performance category.
   - This suggests that PhD employees tend to perform at higher levels.

3. **High School Graduates**:
   - **32%** are in the **Satisfactory** category.
   - **34%** fall under **Needs Improvement**, indicating a larger share struggling with performance.

4. **Master’s Degree Holders**:
   - Their performance is more evenly distributed across categories, without a standout trend.

#### **Insights**
- Employees with **higher education levels (PhD & Master's)** tend to perform better.
- A **large share of Bachelor's degree holders** falls into the **Good** category, reinforcing its importance in hiring.
- **High school graduates** show a **higher concentration in lower performance categories**, possibly highlighting a need for further training or support.

This visualization helps in identifying trends between **education levels and performance**, aiding workforce development strategies.

<img width="1528" alt="Screenshot 2025-03-16 at 11 40 45 AM" src="https://github.com/user-attachments/assets/cb65404c-2938-4399-961f-3a48468d59bf" />

### **Salary Distribution by Education Level (Bar Chart)**

This **bar chart** visualizes the distribution of **salaries** based on different **education levels**.

#### **Structure**
- Each **horizontal bar** represents a specific **education level**.
- The **length of the bar** indicates the corresponding **salary amount**.
- Labels at the **end of each bar** provide exact salary values.

#### **Key Observations**
1. **High School (H_Sch) Graduates**:
   - Earn **$61K**, which is the lowest salary among all education levels.

2. **Bachelor’s Degree Holders**:
   - Earn **$66K**, showing a moderate increase compared to high school graduates.

3. **Master’s and PhD Holders**:
   - Both earn **$80K**, the highest salaries in the dataset.
   - There is no apparent salary distinction between Master's and PhD levels.

#### **Insights**
- A **Bachelor’s degree** leads to a slight salary increase over a **High School diploma**.
- Advanced degrees (**Master’s and PhD**) provide a **significant salary boost**.
- There is no observed salary differentiation between **Master’s and PhD holders**, suggesting that employers might value work experience or other factors equally at this level.

This visualization helps understand how **education level influences salary expectations** in this dataset.

<img width="1687" alt="Screenshot 2025-03-16 at 11 42 12 AM" src="https://github.com/user-attachments/assets/a81e4b08-3e33-481c-9d92-efb19508d933" />

### **Salary vs. Age by Job Title (Scatter Plot)**

This **scatter plot** visualizes the relationship between **age**, **salary**, and **job titles**.

#### **Structure**
- **X-axis**: Represents **Age** of employees.
- **Y-axis**: Represents **Salary** in **USD**.
- Each **diamond marker** represents a different **job title**.
- Labels next to markers indicate specific job roles.

#### **Key Observations**
1. **Higher Salaries for Senior Roles**:
   - **Finance Manager** earns the **highest salary (~$125K)** and is among the **oldest (50+ years)**.
   - **IT Manager** also earns a high salary (~$115K).
   - **Sales Manager, Marketing Manager, and Operations Manager** earn moderately high salaries ($90K–$105K).

2. **Mid-Level Salaries (~$75K–$95K) for Skilled Roles**:
   - Roles like **Software Developer, Customer Service Manager, and Financial Analyst** fall within this range.

3. **Entry-Level and Support Roles Have Lower Salaries (~$60K–$70K)**:
   - Positions like **HR Assistant, Sales Representative, Marketing Coordinator, and Help Desk Technician** are concentrated in the lower salary range.

4. **Age Distribution**:
   - **Lower salaries tend to be associated with younger employees (~35–40 years old).**
   - **Higher salaries correlate with employees aged 45–50+.**

#### **Insights**
- **Experience & seniority** play a significant role in salary growth.
- **Managerial and specialized roles** lead to higher salaries over time.
- Employees in **early career stages (~35–40 years old) tend to have lower salaries** and occupy **support roles**.

This visualization highlights how **career progression influences salary levels** across different age groups.

<img width="1692" alt="Screenshot 2025-03-16 at 11 44 08 AM" src="https://github.com/user-attachments/assets/e14bb00f-4dee-4cc2-a82d-a81460ed364b" />

# **Features of the Human Resources Dashboard**

## **1. Overview Panel**
- **Active Employees**: Displays the total number of currently employed staff.
- **Hiring & Termination Trends**: Line chart showing yearly trends of hired and terminated employees.
- **Department-wise Distribution**: Bar chart comparing the number of hired and terminated employees across different departments.
- **Location Breakdown**: A visual representation of employee distribution between headquarters and branch offices, along with a geographical map.

---

## **2. Demographics Panel**
- **Gender Distribution**: Two circular charts showing the percentage split between male and female employees, with hiring and termination ratios.
- **Education & Age**: A bubble matrix visualizing employee distribution based on educational qualifications and age groups.
- **Education & Performance**: A heatmap-style visualization showing performance ratings segmented by education level (High School, Bachelor's, Master's, PhD).

---

## **3. Income Panel**
- **Education & Gender Salary Comparison**: Horizontal bar graphs comparing salaries across different education levels for male and female employees.
- **Age & Salary Distribution**: A scatter plot showcasing the relationship between employee age, job roles, and salaries.

---

## **4. Interactive Filters**
- **Gender Filter**: Allows selection of male, female, or both.
- **Location Filter**: Enables filtering of data by specific regions or offices.
- **Status Filter**: Filters employees based on their employment status.
- **Hire Date Filter**: Allows selecting employees based on their hiring year.

This dashboard provides **real-time insights into HR metrics**, enabling strategic workforce analysis and decision-making.

<img width="1237" alt="Screenshot 2025-03-16 at 11 48 36 AM" src="https://github.com/user-attachments/assets/a7a8102c-5f97-4a87-a4df-5404398b16f1" />





