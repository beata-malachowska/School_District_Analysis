# School_District_Analysis.
### Analysis of the schools data (funding, size, location) and students school results of math and reading class. Analysis was performed in two variants: with and without students test results from 9th from Thomas High School grade as it was suspected as not being true. 
## Results:
A. Top 5 High Performing Schools were as follow: 
      1. Cabrera High School
      2. Thomas High School
      3. Griffin High School
      4. Wilson High School
      5. Pena High School      
          
B. Top 5 Low Performing Schools were as follow: 
      1. Rodriguez High School	
      2. Figueroa High School
      3. Huang High School
      4. Hernandez High School
      5. Johnson High School
      
      For THS average Average Math Score, Average Reading Score	%, Passing Math	%, Passing Reading	%, Overall Passing changed from: 
      83.418349	83.848930	93.272171	97.308869	90.948012	 to 83.350937	83.896082	93.185690	97.018739	90.630324. 
      
C. Math and Reading Scores by Grade 
          Original math scores: 
                                  9th  10th  11th  12th
          Bailey High School     77.1  77.0  77.5  76.5
          Cabrera High School    83.1  83.2  82.8  83.3
          Figueroa High School   76.4  76.5  76.9  77.2
          Ford High School       77.4  77.7  76.9  76.2
          Griffin High School    82.0  84.2  83.8  83.4
          Hernandez High School  77.4  77.3  77.1  77.2
          Holden High School     83.8  83.4  85.0  82.9
          Huang High School      77.0  75.9  76.4  77.2
          Johnson High School    77.2  76.7  77.5  76.9
          Pena High School       83.6  83.4  84.3  84.1
          Rodriguez High School  76.9  76.6  76.4  77.7
          Shelton High School    83.4  82.9  83.4  83.8
          Thomas High School     83.6  83.1  83.5  83.5
          Wilson High School     83.1  83.7  83.2  83.0
          Wright High School     83.3  84.0  83.8  83.6

          After change:
          Thomas High School      nan  83.1  83.5  83.5
          
          Original reading scores: 
                                       9th  10th  11th  12th
          Bailey High School     81.3  80.9  80.9  80.9
          Cabrera High School    83.7  84.3  83.8  84.3
          Figueroa High School   81.2  81.4  80.6  81.4
          Ford High School       80.6  81.3  80.4  80.7
          Griffin High School    83.4  83.7  84.3  84.0
          Hernandez High School  80.9  80.7  81.4  80.9
          Holden High School     83.7  83.3  83.8  84.7
          Huang High School      81.3  81.5  81.4  80.3
          Johnson High School    81.3  80.8  80.6  81.2
          Pena High School       83.8  83.6  84.3  84.6
          Rodriguez High School  81.0  80.6  80.9  80.4
          Shelton High School    84.1  83.4  84.4  82.8
          Thomas High School     83.7  84.3  83.6  83.8
          Wilson High School     83.9  84.0  83.8  84.3
          Wright High School     83.8  83.8  84.2  84.1
          
          After change:
          Thomas High School           NaN  84.254157  83.585542  83.831361

D. Scores by School Spending

          
              Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
              Spending Ranges (Per Student)					
              <$586	83.5	83.9	93	97	90
              $586-630	81.9	83.2	87	93	81
              $631-645	78.5	81.6	73	84	63
              $646-675	77.0	81.0	66	81	54

                
           After change 3 row was change to: 
              $631-645	78.5	81.6	73	84	63
                
                
E. Scores by School Size
          
            Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
            School Size					
            Small (<1000)	83.8	83.9	94	96	90
            Medium (1000-1999)	83.4	83.9	94	97	91
            Large (2000-5000)	77.7	81.3	70	83	58
            
            Those results were not affected by deleting suspicious data.
          
F. Scores by School Type

            Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
            School Type					
            Charter	83.5	83.9	94	97	90
            District	77.0	81.0	67	81	54
        
           Those results were not affected by deleting suspicious data.
## Summary
   After deleting some test results readind and math scores were not calculated for 9th for THS and this affected the results (For THS average Average Math Score, Average Reading Score	%, Passing Math	%, Passing Reading	%, Overall Passing changed from: 83.418349	83.848930	93.272171	97.308869	90.948012	 to 83.350937	83.896082	93.185690	97.018739	90.630324). In the results of Scores by School Spending analysis third bin ($631-645) was affected. 
