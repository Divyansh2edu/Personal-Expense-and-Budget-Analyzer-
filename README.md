Project Title = Budget Expense Tracker 

Problem Statement: College students often struggle to track where their monthly allowance goes, leading to overspending before the month ends. They need a simple, centralized tool to record daily spending and monitor their remaining balance. 

Intended Users: College students, young professionals, or anyone managing a fixed monthly budget. 

Goals & Scope 
(a)Objectives: 
   Record daily income and expenses.  
   Classify expenses into distinct categories like Food, Travel, and Academics.  
   Calculate total monthly expenditure and identify the highest spending category.  
   Compare total expenditure with a predefined budget to provide simple rule-based alerts.  
(b)Proposed Solution: A Python-based terminal application that utilizes a menu-driven interface, stores financial records persistently in a CSV or TXT file, and uses core data structures (dictionaries and lists) to summarize spending patterns.  

Planning & Organization 
(a)Main Features / Modules: 
   Data Entry Module: Functions to handle user input for expenses and budget, including error handling for incorrect inputs.  
   Storage Module: Functions to read and write the expense data to a TXT or CSV file.  
   Computation Module: The logic for calculating sums and identifying the highest spending categories.  
   Reporting Module: The logic that generates monthly summaries and rule-based budget alerts.  
(b)Team-Member Responsibilities: Distribute these among your 3 to 5 group members. For example:  
   Member Naveen: Main loop, menu navigation, and input validation. 
   Member Divyansh: CSV/TXT file handling for data storage. 
   Member Raghav: Logic for calculating totals and finding the highest spending category. 
   Member Sushant: Designing the summary report and budget alert logic. 

Technical Design 
   Here is the basic algorithm for your program design:  
   (a)Start 
   (b)Load existing expense data from the storage file. 
   (c)Display the main menu (Add Expense, View Summary, Exit). 
   (d)If user selects "Add Expense": 
      Prompt for amount and category. 
      Validate input to ensure it is correct.  
      Save to storage. 
    (e)If user selects "View Summary": 
      Calculate total expenses using a loop.  
      Group and sum expenses by category using a dictionary.  
      Compare the total sum to the budget.  
      Print the total, category breakdown, and budget alert.  
    (f)Loop back to step 3 until the user selects "Exit". 
    (g)Stop 

 

 

 

 
