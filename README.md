# SpreadSheet_Assignment
This Project was completed by Andrew Dibble, Minh Trung Le, and Varun Parbhakar

This application is an implementation of Microsoft Excel with limited features. With the
Spreadsheet app you can perform multiple basic mathematical functions such as +, –, /,*. The
Spreadsheet is made up of a collection of cells that can be used to put in values.

Each cell featured in the Spreadsheet app can hold a literal value as well as a reference to another
cell such as A2 can hold an expression like literal like 5+75 but it can also
hold a reference like A3 + 1. With a combination of different expressions, you can perform
numerous operations without entering the same cell twice.

You can create a spreadsheet from scrath or read from a .txt file. Additionally, you can save the spreadsheet to a .csv file.

Data Structures used:

Implemented a Graph data structure using two LinkedLists: dependsOn and feedsInto

  Every cell in the spreadsheet has these two LinkedLists that contain other cells in
  the spreadsheet
  
      depeondsOn contains the cells that this cell relies on to calculate the value
      
      feedsInto contains the cells that rely on this cell to calculate their values
      
Implemented a Binary Tree to calculate the expressions of each cell.

Implemented a Stack to retrieve and parse the string formula into a calculable postfix
expression.

Implemented a Queue to be used in the topological sort algorithm

Implemented an array to read a spreadsheet from a file and to handle the input, also
  implemented the spreadsheet as a two dimensional array of cells
  
Famous Algorithms: Topological sort to figure out which cell to evaluate first based on the dependencies of each

Other algorithms:
  input validation
  used binary trees and stacks to calculate expressions entered by user
