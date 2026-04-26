Chapter 1: Getting Started with C++

ABOUT: The Creation of C++ Chapter 1 relates how Bjarne Stroustrup created the C++ programming
       language by adding object-oriented programming. 
       After reading this chapter, I have a unerstanding about how and why C++ was created,
       as well as object-oriented languages.
       I have learned about the ANSI/ISO and STL work to develop a C++ standard. 
       This chapter discusses the mechanics of creating a C++ program,
       outlining the approach for several current C++ compilers.
NOTES
     * The C++ language blends the C language with support for object-oriented programming and
       for generic programming.
     * C++ joins three separate programming categories:
                1. The procedural language, represented by C
                2. The object-oriented language, represented by the class enhancements
                C++ adds to C
                3. Generic programming, supported by C++ templates.
      * An operating system is a set of programs that manages a computer’s resources and handles 
        its interactions with users.
      * C was created in the early 1970s by Dennis Ritchie of Bell Laboratories. 
        They were working on a project to develop the Unix operating system
      * Assembly language is a low-level, processor-specific programming language that uses 
        human-readable mnemonics to represent the exact binary instructions and hardware operations
        executed by a computer's CPU.
      * low-level language—that is, it works directly with the hardware
      * high-level language, which is oriented toward problem-solving instead of toward 
        specific hardware. Special programs called compilers translate a high-level language
        into the internal language of a particular computer.
      * Data + Algorithms = Program
      * Data is the information a program uses and processes.
      * Algorithms are methods the program uses.
      * The Procedural Mindset C is a procedural language, meaning it emphasizes 
        the algorithm side of programming. Procedural programming consists of figuring out 
        the actions a computer should take and then using the programming language to
        implement those actions.
      * Earlier procedural languages ran into organizational problems as programs
        grew larger, often leading to tangled routing called “spaghetti programming.”
      * Spaghetti Programming: A disorganized and tangled coding style where the flow of 
        execution is cluttered by excessive branching, making it difficult to follow or
        maintain.
      * To fix this, computer scientists developed structured programming.
        The idea is branching to a small set of well-behaved constructions
      * The idea of top-down design is to break a large program into smaller, 
        more manageable tasks. If a task is still too broad,
        you divide it again until the program is compartmentalized into small,
        easily programmed modules.
Although structured programming improved clarity, large-scale projects remained a challenge.
While procedural programming emphasizes algorithms, OOP emphasizes the data. 
OOP attempts to fit the language to the problem by designing data forms that correspond to
the essential features of a problem.
      * Class is a specification describing a new data form. It defines what data represents
        an object and the operations that can be performed on it.
      * Object is a particular data structure constructed according to that class plan.
      * The process of moving from a lower level of organization, such as classes, 
        to a higher level, such as program design, is called bottom-up programming.
      * Polymorphism lets us create multiple definitions for operators and functions,
        using the context to determine which is used.
      * Inheritance lets us derive new classes from old ones, making it easier 
        to expand on existing code.
      * generic programming provides tools for common tasks, 
        like sorting data or merging lists.
      * Libraries are collections of programming modules (proven solutions) 
        that you can call up to save time and effort.
      * If you can recompile a program on a different platform without making changes 
        and it runs without a hitch, the program is considered portable.
      * The STL (Standard Template Library) is a powerful collection of generic
        C++ templates that provides ready-to-use data structures like vectors and lists, 
        along with algorithms for tasks such as searching and sorting.
The Mechanics of Creating a Program
The Three-Step Transformation
Source Code: You write your program in a text editor and save it.
             This is your human-readable instruction set.
Object Code: You run a compiler to translate source code into machine language 
            (internal computer language). This result is called object code.
Executable Code: A linker combines your object code with library functions 
                (like those for math or screen output) and startup code to create the final
                 runtime version.
      * The file containing this final product is called the executable code.
      * In naming a source file, you must use the proper suffix to identify the file as
        a C++ file. This not only tells you that the file is C++ source code, 
        it tells the compiler that, too.
      * Unix is case sensitive.
      * Integrated development environments (IDEs) let you manage all steps of program 
        development, including editing, from one master program.
      * g++ is a specialized command-line tool used in Unix-like environments to compile and
        link C++ source code into an executable file.
      * Compile typically means compile the code in the file that is currently open.
      
        

INTERESTING LINK:  Bjarne Stroustrup’s Home Page: www.research.att.com/~bs 
                   (A must-have bookmark for any C++ developer).   
FUN FACT:  The name C++ comes from the C increment operator ++, which adds one to a variable. 
           This suggests that C++ is an "augmented" or incremented version of C.
FUN FACT:  valid C program is a valid C++ program, too
FUN FACT:  C++’s OOP aspect was inspired by a computer simulation language called Simula67
           Developed in the 1960s, Simula67 was the first object-oriented programming 
           language, introducing the revolutionary idea of using "objects" and "classes" 
           to simulate real-world systems.   
FUN FACT:  Unix was intended to work on a variety of computer types.
FUN FACT:  An IDE (like VS Studio) is a complete workspace that includes a text editor,
           debugger, and project manager, whereas g++ is strictly the compiler tool itself
           used via the command line.
           
