## Algorithm: CSV Data Processing Automation
 Step-by-Step Procedure:
1. Start the program.
2. Input the CSV file path.
3. Open the CSV file in read mode.
4. Read data into a structured format (list/dictionary or DataFrame).
5. Validate data (check for empty cells, duplicates).
6. Display menu for user operations:
   a. View data
   b. Filter rows
   c. Add new row
   d. Delete row
   e. Sort data
   f. Generate summary statistics
7. Perform the selected operation.
8. Save updated data into a new CSV file.
9. Close files.
10. End program.

## Logic / Method Used:
- File handling with Python’s csv/pandas.
- Conditional filtering using if-statements or queries.
- Iteration for row updates/deletions.
- Aggregation functions for statistics.
- Error handling for missing files or invalid input.

## Model / Technique Applied:
- Structured programming with modular functions.
- Data cleaning techniques (remove duplicates, handle nulls).
- Menu-driven approach for user interaction.
- Automation for repetitive tasks.

# Process Flow of the System:
Start → Input CSV → Read Data → Validate Data → User Chooses Operation → Perform Operation → Save to New CSV → End
