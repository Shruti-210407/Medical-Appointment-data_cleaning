# Task 1 : Data Cleaning and Preprocessing

outcomes: -- Understanding of data pre-processing
          -- Create a clean, structured dataset that is ready for analysis or modelling. 
          
   🐍 Python (Pandas in Jupyter Notebook)
1. Loaded the dataset using 'pandas.read_csv()'.
2. Checked data types of all columns using:
   'df.dtypes()'
3. Checked for missing values using:
   df.isnull().sum()
4. Removed duplicate rows, if any, using:
   df.drop_duplicates()

   📊 Microsoft Excel
1. Removed duplicates using the Remove Duplicates feature from the Data tab.
2. Converted the Patient_Id column from scientific notation to standard numeric format.
3. Split the Scheduled_Day column into two new columns:
   Scheduled_Date
   Scheduled_Time
   This was done using the Text to Columns feature with delimiter 'T'.
4. Applied the same split to the Appointment_Day column to extract date and time separately.
5. Converted all column headers to uppercase using the Excel formula:
   =UPPER(cell_reference)
6. Formatted the dataset as an Excel Table to improve readability and enable filtering/sorting features.
   
   


          
          
  
