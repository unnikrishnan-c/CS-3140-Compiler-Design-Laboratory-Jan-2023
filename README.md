# CS-3140-Compiler-Design-Laboratory-2024

**Evaluation Policy**
 - Viva: 15%
 - Test1: 15%
 - Test2 (Part of Project): 20%
 - Continous Evaluation: 30%
 - End Term Exam: 20%

In this course we will implement  (a) Lexical Analyzer, (b) Syntax and Semantic Analyzer (c) AST printing (d) Code Generation

Assignment1:  Creation and evaluation syntax tree using Lex and YACC. (Deadline 11:59 pm IST)

Assignment2: Extending the language to support global variable declaration with variables of type "integer", assignment statements, and function calls. 
      The global variable declaration if present in the program should come first.
      The expression for calculator should be extended with assignment statements and function calls.
       
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
