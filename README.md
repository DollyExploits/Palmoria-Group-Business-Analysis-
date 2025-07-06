## Palmoria Group HR Analysis - README.md

This document presents an HR analysis of Palmoria Group's employee data, focusing on gender-related issues, salary structure, and bonus allocations. The insights are derived from the provided `Palmoria Group emp-data.csv` and `Palmoria Group Bonus Rules.xlsx - Bonus Rules.csv` files.

### 1. Data Preparation and Cleaning

The following steps were taken to prepare and clean the employee data:

* **Handling Undisclosed Gender:** Employees with no gender specified have been assigned a generic gender status of 'Undisclosed'.
* **Removing Employees Without Salary:** Employees with missing or invalid salary data (e.g., empty or non-numeric) were excluded from the analysis as they are considered no longer with the company.
* **Removing NULL Departments:** Employees whose department was listed as 'NULL' were removed from the analysis.

**Summary of Cleaned Data:**

* Total Employees (After Cleaning): 208
* Removed due to missing Salary: 10
* Removed due to NULL Department: 10
* Removed due to both (counted once): 3
* Employees with Gender assigned 'Undisclosed': 15

### 2. Gender Distribution Analysis

#### 2.1 Overall Gender Distribution

* **Female:** 101 employees (48.56%)
* **Male:** 92 employees (44.23%)
* **Undisclosed:** 15 employees (7.21%)

#### 2.2 Gender Distribution by Region

**Lagos:**
* Female: 33 employees (46.48%)
* Male: 35 employees (49.30%)
* Undisclosed: 3 employees (4.23%)
* Total: 71 employees

**Abuja:**
* Female: 37 employees (47.44%)
* Male: 33 employees (42.31%)
* Undisclosed: 8 employees (10.26%)
* Total: 78 employees

**Kaduna:**
* Female: 31 employees (50.82%)
* Male: 24 employees (39.34%)
* Undisclosed: 6 employees (9.84%)
* Total: 61 employees

#### 2.3 Gender Distribution by Department

* **Accounting:**
    * Female: 8, Male: 8, Undisclosed: 1
* **Business Development:**
    * Female: 10, Male: 11, Undisclosed: 2
* **Engineering:**
    * Female: 12, Male: 11, Undisclosed: 2
* **Human Resources:**
    * Female: 16, Male: 11, Undisclosed: 1
* **Legal:**
    * Female: 10, Male: 15, Undisclosed: 0
* **Marketing:**
    * Female: 9, Male: 11, Undisclosed: 2
* **Product Management:**
    * Female: 13, Male: 12, Undisclosed: 1
* **Research and Development:**
    * Female: 8, Male: 10, Undisclosed: 2
* **Sales:**
    * Female: 11, Male: 12, Undisclosed: 0
* **Services:**
    * Female: 11, Male: 10, Undisclosed: 2
* **Support:**
    * Female: 6, Male: 13, Undisclosed: 1
* **Training:**
    * Female: 7, Male: 8, Undisclosed: 1

### 3. Insights on Ratings Based on Gender

* **Average:** Female: 36, Male: 37, Undisclosed: 9
* **Good:** Female: 30, Male: 24, Undisclosed: 4
* **Not Rated:** Female: 10, Male: 6, Undisclosed: 0
* **Poor:** Female: 13, Male: 15, Undisclosed: 0
* **Very Good:** Female: 11, Male: 8, Undisclosed: 1
* **Very Poor:** Female: 1, Male: 2, Undisclosed: 1

### 4. Salary Structure Analysis and Gender Pay Gap

#### 4.1 Average Salary by Gender (Company-wide)

* **Female Average Salary:** $73,733.66
* **Male Average Salary:** $73,831.30
* **Undisclosed Average Salary:** $72,566.00

There is a negligible difference in average salaries between genders at the company-wide level.

#### 4.2 Average Salary by Gender and Department

While the overall average salary difference is small, variations exist within departments:

* **Accounting:**
    * Female: $72,008.75
    * Male: $76,715.00
    * Undisclosed: $107,110.00
* **Business Development:**
    * Female: $74,834.00
    * Male: $74,383.64
    * Undisclosed: $48,330.00
* **Engineering:**
    * Female: $78,574.17
    * Male: $69,451.82
    * Undisclosed: $86,375.00
* **Human Resources:**
    * Female: $69,963.75
    * Male: $72,836.36
    * Undisclosed: $99,450.00
* **Legal:**
    * Female: $69,118.00
    * Male: $69,720.00
* **Marketing:**
    * Female: $72,216.67
    * Male: $69,380.91
    * Undisclosed: $79,805.00
* **Product Management:**
    * Female: $70,883.08
    * Male: $75,567.50
    * Undisclosed: $84,990.00
* **Research and Development:**
    * Female: $69,970.00
    * Male: $70,410.00
    * Undisclosed: $63,395.00
* **Sales:**
    * Female: $71,118.18
    * Male: $75,348.33
* **Services:**
    * Female: $73,191.82
    * Male: $70,050.00
    * Undisclosed: $80,090.00
* **Support:**
    * Female: $60,948.33
    * Male: $74,354.62
    * Undisclosed: $104,800.00
* **Training:**
    * Female: $81,390.00
    * Male: $77,597.50
    * Undisclosed: $84,680.00

**Departments with noticeable gender pay gaps (favoring males):**

* **Accounting:** Males earn, on average, more than females.
* **Product Management:** Males earn, on average, more than females.
* **Support:** Males earn significantly more, on average, than females.

**Departments with noticeable gender pay gaps (favoring females):**

* **Engineering:** Females earn, on average, more than males.
* **Marketing:** Females earn, on average, more than males.
* **Training:** Females earn, on average, more than males.

#### 4.3 Average Salary by Gender and Region

* **Lagos:**
    * Female: $75,998.48
    * Male: $71,780.00
    * Undisclosed: $54,950.00
* **Abuja:**
    * Female: $74,960.54
    * Male: $70,477.27
    * Undisclosed: $81,421.25
* **Kaduna:**
    * Female: $70,551.94
    * Male: $79,252.08
    * Undisclosed: $70,510.00

**Regions with noticeable gender pay gaps:**

* **Lagos:** Females earn, on average, more than males.
* **Abuja:** Females earn, on average, more than males.
* **Kaduna:** Males earn, on average, more than females. This region should be a focus for management to investigate potential gender pay gaps.

### 5. Compliance with Minimum Wage Regulation ($90,000)

#### 5.1 Does Palmoria Meet the Requirement?

No, Palmoria does not meet the requirement that all manufacturing employees be paid a minimum of $90,000.

* **Number of Employees Below $90,000:** 137 employees (65.87% of cleaned data)
* **Number of Employees At or Above $90,000:** 71 employees (34.13% of cleaned data)

This indicates a significant portion of the workforce is paid below the new regulation.

#### 5.2 Pay Distribution by $10,000 Bands (Company-wide)

* **$20,000 - $30,000:** 4 employees
* **$30,000 - $40,000:** 24 employees
* **$40,000 - $50,000:** 25 employees
* **$50,000 - $60,000:** 26 employees
* **$60,000 - $70,000:** 24 employees
* **$70,000 - $80,000:** 24 employees
* **$80,000 - $90,000:** 10 employees
* **$90,000 - $100,000:** 23 employees
* **$100,000 - $110,000:** 23 employees
* **$110,000 - $120,000:** 25 employees

#### 5.3 Pay Distribution by $10,000 Bands and Region

**Lagos:**
* **$20,000 - $30,000:** 2 employees
* **$30,000 - $40,000:** 6 employees
* **$40,000 - $50,000:** 9 employees
* **$50,000 - $60,000:** 7 employees
* **$60,000 - $70,000:** 7 employees
* **$70,000 - $80,000:** 7 employees
* **$80,000 - $90,000:** 5 employees
* **$90,000 - $100,000:** 9 employees
* **$100,000 - $110,000:** 9 employees
* **$110,000 - $120,000:** 10 employees

**Abuja:**
* **$20,000 - $30,000:** 2 employees
* **$30,000 - $40,000:** 9 employees
* **$40,000 - $50,000:** 10 employees
* **$50,000 - $60,000:** 11 employees
* **$60,000 - $70,000:** 7 employees
* **$70,000 - $80,000:** 9 employees
* **$80,000 - $90,000:** 4 employees
* **$90,000 - $100,000:** 9 employees
* **$100,000 - $110,000:** 8 employees
* **$110,000 - $120,000:** 9 employees

**Kaduna:**
* **$30,000 - $40,000:** 9 employees
* **$40,000 - $50,000:** 6 employees
* **$50,000 - $60,000:** 8 employees
* **$60,000 - $70,000:** 10 employees
* **$70,000 - $80,000:** 8 employees
* **$80,000 - $90,000:** 1 employee
* **$90,000 - $100,000:** 5 employees
* **$100,000 - $110,000:** 6 employees
* **$110,000 - $120,000:** 6 employees

### 6. Annual Bonus Pay Allocation

#### 6.1 Bonus Rules

[cite_start]The bonus percentages are applied based on an employee's Department and Performance Rating[cite: 46].

* **Very Poor:** 0.5%
* **Poor:**
    * Sales: 1.2%
    * Engineering: 1.1%
    * Legal: 1.9%
    * Support: 1.0%
    * Human Resources: 1.3%
    * Product Management: 1.4%
    * Research and Development: 1.5%
    * Marketing: 1.2%
    * Accounting: 1.3%
    * Services: 1.0%
    * Business Development: 1.2%
    * Training: 1.1%
* **Average:**
    * Sales: 2.1%
    * Engineering: 3.5%
    * Legal: 2.1%
    * Support: 2.8%
    * Human Resources: 2.7%
    * Product Management: 2.5%
    * Research and Development: 2.2%
    * Marketing: 2.3%
    * Accounting: 2.0%
    * Services: 2.4%
    * Business Development: 2.1%
    * Training: 2.2%
* **Good:**
    * Sales: 5.1%
    * Engineering: 4.3%
    * Legal: 5.4%
    * Support: 4.9%
    * Human Resources: 5.4%
    * Product Management: 4.5%
    * Research and Development: 5.0%
    * Marketing: 4.8%
    * Accounting: 5.2%
    * Services: 4.7%
    * Business Development: 5.0%
    * Training: 4.6%
* **Very Good:**
    * Sales: 8.8%
    * Engineering: 6.1%
    * Legal: 6.4%
    * Support: 7.6%
    * Human Resources: 7.6%
    * Product Management: 6.8%
    * Research and Development: 7.2%
    * Marketing: 6.9%
    * Accounting: 7.0%
    * Services: 6.5%
    * Business Development: 7.0%
    * Training: 6.6%

#### 6.2 Calculated Bonus and Total Pay per Employee

Due to the large number of employees, individual employee bonus and total pay calculations are not listed here but have been performed for each employee in the cleaned dataset based on the above rules. This data can be provided upon request for integration into a detailed report or spreadsheet.

#### 6.3 Total Amount to be Paid Out per Region and Company-wide

**Total Bonus Paid Out:**

* **Lagos:** $208,614.99
* **Abuja:** $230,736.25
* **Kaduna:** $178,579.52
* **Company-Wide Total Bonus Payout:** $617,930.76

**Total Compensation (Salary + Bonus) Paid Out:**

* **Lagos:** $5,324,554.99
* **Abuja:** $5,948,846.25
* **Kaduna:** $4,484,799.52
* **Company-Wide Total Compensation:** $15,758,190.76

### Recommendations for Management

Based on this analysis, the Palmoria management team should consider the following:

1.  **Address Gender Pay Gaps in Specific Departments/Regions:**
    * Investigate the 'Accounting', 'Product Management', and 'Support' departments where males appear to earn more than females on average.
    * Investigate the 'Kaduna' region where males earn significantly more than females on average.
    * Conduct a deeper dive to understand the reasons behind these disparities (e.g., job roles, experience, tenure, negotiation skills) and implement corrective actions if genuine gaps exist.
2.  **Review and Adjust Salaries for Regulatory Compliance:**
    * A large number of employees (65.87%) are currently paid below the new $90,000 minimum regulation. This is a critical issue that needs immediate attention to avoid legal and reputational consequences.
    * Develop a clear strategy and budget to increase salaries for all employees below the minimum threshold.
3.  **Promote Gender Diversity in Departments:**
    * While overall gender distribution is relatively balanced, some departments show significant imbalances (e.g., more males in Legal and Support, more females in Human Resources). Promoting diversity initiatives could foster a more inclusive environment.
4.  **Leverage Performance-Based Bonuses:**
    * The current bonus structure allows for performance-based incentives. Ensure fairness and transparency in performance rating processes to maximize employee motivation and address any potential biases that could impact bonus payouts.

This analysis provides a foundational understanding of the HR landscape within Palmoria Group concerning gender equality and compensation. Further qualitative research, such as employee surveys and focus groups, can provide additional context and insights into the issues identified.
