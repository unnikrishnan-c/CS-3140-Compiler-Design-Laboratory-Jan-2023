# CS-3140-Compiler-Design-Laboratory-2024

In this course we will implement  (a) Lexical Analyzer, (b) Syntax and Semantic Analyzer (c) AST printing (d) Code Generation

**Evaluation Policy**
 - Viva: 15%
 - Test1: 15%
 - Test2 (Part of Project): 20%
 - Continous Evaluation: 30%
 - End Term Exam: 20%



**Assignment 1**
   
    Creation and evaluation syntax tree using Lex and YACC. 

**Assignment 2**

Extending the language to support global variable declaration with variables of type "integer", assignment statements, and function calls. 
      The global variable declaration if present in the program should come first.
      The expression for calculator should be extended with assignment statements and function calls.
       
       One sample declaration statemtent block  in the source program is given below
       
             begindecl 
                 integer  var1, var2,var3;
             enddecl

       One sample asignment statement sequence is given below.
              
              var1=10;

**Assignment 3**
  
   Extend Assignment two have  support for 
  - (a) One Dimensional Array, (b) if-then-else, (c) for loop
  - Print symbol table and AST( Abstract Syntax Tree)
  - One Sample program given below


**Sample Program for Assignment 3**


![Screenshot from 2024-02-27 23-10-09](https://github.com/unnikrishnan-c/CS-3140-Compiler-Design-Laboratory-Jan-2023/assets/63437154/d9662c0f-9a79-45ae-a9cd-585f476340f0)


**How to Make Sure Your Assignment Builds**

Follow these commands. Make sure to replace 112xxxxxx-CS3140 with your repo slug (that you've shared with us) and assignment-2 with the appropriate tag for the assignment you are checking.

```bash
# === Step 1: Take a temporary clone ===
cd /tmp
git clone git@gitlab.com:112101045/112xxxxxx-CS3140.git
cd 112xxxxxx-CS3140

# === Step 2: Switch to the tag ========
git checkout assignment-2

# Make sure your program isn't built yet
file bin/compiler # Should give a "No such file or directory" error

# === Step 3: Try building ==============
cd compiler
make clean
make

# Make sure the file has been built
file bin/compiler # Make sure the output of this command says it's a valid executable file

# Now you can remove the temporary clone (i.e., /tmp/112xxxxxx-CS3140)
```
    
**Teaching Assistants**
   
   - Kevin Jude Concessao
   - Nandakumar E
   - Thania Kumar
        
