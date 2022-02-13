# Pewlett-Hackard-Analysis

## Overview
The overview of this learn about data modeling, engineering, and analysis.Applying our knowledge of DataFrames and tabular data, we created entity relationship diagrams (ERDs), import data into a database, troubleshot common errors, and created queries that use data to answer questions using SQL techniques.

## Resources

  - **Data Source:** [departments.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055221/departments.csv), [dept_emp.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055225/dept_emp.csv), [dept_manager.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055226/dept_manager.csv), [employees.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055227/employees.csv), [salaries.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055228/salaries.csv), [titles.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055229/titles.csv)
  - **Software:** Postgres, pgAdmin

## Results
  
  **1.** A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955 and is exported as [retirement_titles.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055242/retirement_titles.csv).

  ![q1](https://user-images.githubusercontent.com/95719819/153746716-60838ac3-1e5e-4b9a-b591-6d4e1faeb4df.PNG)

  **2.** A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title and is exported as [unique_titles.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055244/unique_titles.csv).
  
  ![q2](https://user-images.githubusercontent.com/95719819/153746834-78d4b654-9429-4f23-92d3-dbbda24ac1b6.PNG)
  
  **3.** A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring and is exported as [retiring_titles.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055251/retiring_titles.csv).
   
  ![q3](https://user-images.githubusercontent.com/95719819/153746998-2e67e999-949b-4f15-a20a-debd5e1361ab.PNG)
  
  **4.** A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965 and is exported as [mentorship_eligibilty.csv](https://github.com/tkiruthika/Pewlett-Hackard-Analysis/files/8055255/mentorship_eligibilty.csv).

  ![q4](https://user-images.githubusercontent.com/95719819/153747116-e496b7c0-2b3b-494a-be7a-817cb5cf742c.PNG)
  
  ## Summary
  
   - **How many roles will need to be filled as the "silver tsunami" begins to make an impact?**
     72458 roles will need to be filled as the "silver tsunami" begins to make an impact.
     
   ![s1](https://user-images.githubusercontent.com/95719819/153748373-02f65c31-535d-420f-a9eb-a0cb4d8151ab.png)

   - **Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**
     No we only have 1549 retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees.
   
   ![s2](https://user-images.githubusercontent.com/95719819/153748393-c3cc2cce-795e-4d54-a392-c4ac53eaea0b.PNG)

