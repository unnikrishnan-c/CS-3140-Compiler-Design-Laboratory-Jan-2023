# CS-3140-Compiler-Design-Laboratory-Jan-2023

In this course we will implement  (a) Lexical Analyzer, (b) Syntax and Semantic Analyzer (c) AST printing (d) Code Generation

Assignment1:  Creation of Syntax Tree for Calculator and evaluation of  the Syntax Tree. (Deadline 11:59 pm IST, Thursday Feb 09)

Assignment 2: Extending the language to support global variable declaration with variables of type "integer" and function calls. 
      The global variable declaration if present in the program should come first
      Then expression for calculator should be extended with assignment statements and function calls.
       
       One sample declaration statemtent block  in the source program is given below
       
             begindecl 
                 integer  var1, var2,var3;
             enddecl
       One sample asignment statement sequence is given below.
              
              var1=10;
              
              var2=30;
              
              var3=var1+var2;
              
             
           One sample function call statement is given below
            print(var1, var2, var3);
            
  Error reporting should be added to support: divide by zero error, undeclared variable error etc.
