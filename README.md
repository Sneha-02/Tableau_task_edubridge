# Tableau_task_edubridge

Steps to be followed are:-
  
1.First open tableau and import the excel dataset.

2.After importing excel file move to sheet 1.

3.Then drag and drop the rows to show the table.

4.After that choose create calculated field by clicking on the analysis from menu bar.

5.A dialogue box will pop up for calculation.

6.The syntax for calculation is :
                           
  LEFT('0000000',( 7 - LEN(STR([Emp id]))))
  +
  STR([Id]) 
7.As we need to make all employee id as a 7-digit number in tableau.
