# excel_food_mart

 DA- food_mart contains Dashboard (excel file)

EDA   Utillising Advanced excel , Power Query and Power Pivot 


1. Data cleaning implementing Power Query 
                                 ( any field containing qualitative,categorical information treated  as dimension)
                                 ( any field containing numeric (quantitative) information treated  as measure )
   
Store ,calendar ,customer ,Product , Region  are lookup tables ( or dimension tables)

-- Lookup tables contains Primary keys 

transaction ( made by appending tables transaction -1997 and  transaction -1998 ) and Returns table are data tables ( or fact tables)
      -- fact tables contains measures 
                                     
      
-- Data tables contains Foreign keys 


2. Data modeling implementing Power Pivot
  -- data model contains two types of tables : data tables and lookup tables 
  
  
  
-- one to many relationship only 

-- diagram_view picture shows data relationship among tables


3. DAX(Data Analysis Expressions)

-- A few Dax  functions i have applied in data model :
 
  1. COUNTROWS() :Counts the number of rows in the specified  table, or a table defined by an expression

  2. COUNT() =Counts the number of cells in a column that  contain numbers

  3. COUNTA() = Counts the number of non-empty cells in a column (numerical and non-numerical) 

  4. DISTINCTCOUNT() = Counts the number of different cells in a  column of numbers

  5. IFERROR() = Evaluates an expression and returns a specified value if the expression returns an error, otherwise returns the expression itself

  6. SWITCH() Evaluates an expression against a list of values and returns one of multiple possible result expressions

   
   
  









