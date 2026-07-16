  <pre>
Chapter 2: Setting Out to C++
  ABOUT: In this chapter, I built my first understanding of how a C++ program is organized from
  start to finish. I learned the purpose of preprocessor directives, especially `#include`, 
  and explored how the `main()` function serves as the entry point of every C++ program.
  I also practiced using `cin`, `cout`, `endl`, and `main()` to create simple 
  interactive programs, while becoming familiar with the basic structure and execution flow 
  of C++ code.

NOTES:
  *   cout :  facility to produce character output.
  *   The source code includes several comments to the reader; these lines begin with //,
      and the compiler ignores them.
      C++ also recognizes C comments, which are enclosed between /* and */ symbols:
  *   C++ is case sensitive;
  *   " using unknown identifiers " means that your program is referring to a name 
       that the compiler doesn't recognize because it hasn't been declared or defined.
  *   #include <iostream> // a PREPROCESSOR directive
      Preprocessor is a program that processes a source file before the
      main compilation takes place. This directive causes the preprocessor to add the 
      contents of the iostream file to your program.
      preprocessor action: adding or replacing text in the source code before it’s compiled.

    About the Iostream: preprocessor action: adding or replacing text in the source code
                        before it’s compiled.
                        Programs that use cin and cout for input and output must include the
                        iostream file.
  *   iostream and for example math.h is called include files (because they are included in
      other files) or header files (because they are included at the beginning of a file).
      header files (because they are included at the beginning of a file).
  *   Using namespace std;
      namespaces is a using directive. 
      Namespace is named space where (container) that organizes identifiers such as functions,
      classes, variables, and objects. It prevents naming conflicts by allowing different 
      namespaces to contain identifiers with the same name. For example, std::cout means that
      cout belongs to the std namespace. Writing using namespace std; tells the compiler 
      to look in the std namespace automatically, so you can write cout instead of std::cout.
      Namespaces make it possible for different libraries or programmers to use the same 
      function or variable names without causing conflicts.
  *   This using directive makes all the names in the std namespace available.
  *   There is 2 ways of using it:
                          using std::cout; // make cout available
                          using std::endl; // make endl available
                          OR:
                          using namespace std; // lazy approach, all names available
  *   C++ programs fundamental structure:
         int main()
       {
          statements
          return 0;
        }
          *   The function header is the first line of a function. It tells the compiler the 
               function's return type, name, and parameters.
          *   int – The return type of the function. It tells the compiler that the function will
              return an integer value.
              main – The name of the function. It is the entry point of every C++ program.
              When a program starts, execution always begins with main(), regardless of where
              it is located in the source file.
          *   () – The parameter list. It specifies what arguments the function receives. 
              In this example, main() does not receive any parameters.
          *   { } – The function body. It contains the statements that are executed when the 
              function is called.
          *   Statement – A single instruction that tells the computer to perform an action. 
              Most C++ statements end with a semicolon (;).
          *   the main() function takes no information, or in the usual terminology,
              main() takes no arguments. argument is the term computer
              buffs use to refer to information passed from one function to anoter
  *   return 0; – The return statement. It ends the main() function and returns the value 0 to the operating system.
      A return value of 0 usually indicates that the program finished successfully without
      errors.
  *   Using the keyword void in the parentheses is an explicit way of saying that the function
      takes no arguments. 
  *  void main()
     void return type means the function doesn’t return a value.
  *   
    
       

ADVICE:
        You should use comments to document your programs. The more complex the program, 
        the more valuable comments are. Not only do they help others to understand what
        you have done, but also they help you understand what you’ve done, especially if you
        haven’t looked at the program for a while.
    
    
</pre>
