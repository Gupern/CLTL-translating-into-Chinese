# CLTL-translating-into-Chinese
This project is to translate the book Common Lisp The Language: 2nd edition into Chinese. 
- Please read the file ***About Permission*** firstly.
- 最主要的还是要静下心来，把微信和QQ都删了，宁静致远，这对我这个浮躁的人来说，是最难的。
- 虽然vim8出来了，但是我还是走向了Emacs的阵营。
Contents：
- [ ] Preface SECOND EDITION
- [ ] Acknowledgments SECOND EDITION
- [ ] Acknowledgments FIRST EDITION (1984)
- [x] 1. Introduction
- Editing recently
- [ ] 1.1.  Purpose
- [x] 1.2.  Notational Conventions
- [x] 1.2.1.  Decimal Numbers
- [x] 1.2.2.  Nil, False, and the Empty List
- [ ]   Evaluation, Expansion, and Equivalence
- [ ]   Errors
- [ ]   Descriptions of Functions and Other Entities
- [x]   The Lisp Reader
- [ ]   Overview of Syntax
- [ ] 2. Data Types
- [ ]   Numbers
- [ ]   Integers
- [ ]   Ratios
- [ ]   Floating-Point Numbers
- [ ]   Complex Numbers
- [ ]   Characters
- [ ]   Standard Characters
- [ ]   Line Divisions
- [ ]   Non-standard Characters
- [ ]   Character Attributes
- [ ]   String Characters
- [ ]   Symbols
- [ ]   Lists and Conses
- [ ]   Arrays
- [ ]   Vectors
- [ ]   Strings
- [ ]   Bit-Vectors
- [ ]   Hash Tables
- [ ]   Readtables
- [ ]   Packages
- [ ]   Pathnames
- [ ]   Streams
- [ ]   Random-States
- [ ]   Structures
- [ ]   Functions
- [ ]   Unreadable Data Objects
- [ ]   Overlap, Inclusion, and Disjointness of Types
- [ ] 3. Scope and Extent
- [ ] 4. Type Specifiers
- [ ]   Type Specifier Symbols
- [ ]   Type Specifier Lists
- [ ]   Predicating Type Specifiers
- [ ]   Type Specifiers That Combine
- [ ]   Type Specifiers That Specialize
- [ ]   Type Specifiers That Abbreviate
- [ ]   Defining New Type Specifiers
- [ ]   Type Conversion Function
- [ ]   Determining the Type of an Object
- [ ]   Type Upgrading
- [ ] 5. Program Structure
- [ ]   Forms
- [ ]   Self-Evaluating Forms
- [ ]   Variables
- [ ]   Special Forms
- [ ]   Macros
- [ ]   Function Calls
- [ ]   Functions
- [ ]   Named Functions
- [ ]   Lambda-Expressions
- [ ]   Top-Level Forms
- [ ]   Defining Named Functions
- [ ]   Declaring Global Variables and Named Constants
- [ ]   Control of Time of Evaluation
- [ ] 6. Predicates
- [ ]   Logical Values
- [ ]   Data Type Predicates
- [ ]   General Type Predicates
- [ ]   Specific Data Type Predicates
- [ ]   Equality Predicates
- [ ]   Logical Operators
- [ ] 7. Control Structure
- [ ]   Constants and Variables
- [ ]   Reference
- [ ]   Assignment
- [ ]   Generalized Variables
- [ ]   Function Invocation
- [ ]   Simple Sequencing
- [ ]   Establishing New Variable Bindings
- [ ]   Conditionals
- [ ]   Blocks and Exits
- [ ]   Iteration
- [ ]   Indefinite Iteration
- [ ]   General Iteration
- [ ]   Simple Iteration Constructs
- [ ]   Mapping
- [ ]   The ``Program Feature''
- [ ]   Structure Traversal and Side Effects
- [ ]   Multiple Values
- [ ]   Constructs for Handling Multiple Values
- [ ]   Rules Governing the Passing of Multiple Values
- [ ]   Dynamic Non-Local Exits
- [ ] 8. Macros
- [ ]   Macro Definition
- [ ]   Macro Expansion
- [ ]   Destructuring
- [ ]   Compiler Macros
- [ ]   Environments
- [ ] 9. Declarations
- [ ]   Declaration Syntax
- [ ]   Declaration Specifiers
- [ ]   Type Declaration for Forms
- [ ] 10. Symbols
- [ ]   The Property List
- [ ]   The Print Name
- [ ]   Creating Symbols
- [ ] 11. Packages
- [ ]   Consistency Rules
- [ ]   Package Names
- [ ]   Translating Strings to Symbols
- [ ]   Exporting and Importing Symbols
- [ ]   Name Conflicts
- [ ]   Built-in Packages
- [ ]   Package System Functions and Variables
- [ ]   Modules
- [ ]   An Example
- [ ] 12. Numbers
- [ ]   Precision, Contagion, and Coercion
- [ ]   Predicates on Numbers
- [ ]   Comparisons on Numbers
- [ ]   Arithmetic Operations
- [ ]   Irrational and Transcendental Functions
- [ ]   Exponential and Logarithmic Functions
- [ ]   Trigonometric and Related Functions
- [ ]   Branch Cuts, Principal Values, and Boundary Conditions in the Complex Plane
- [ ]   Type Conversions and Component Extractions on Numbers
- [ ]   Logical Operations on Numbers
- [ ]   Byte Manipulation Functions
- [ ]   Random Numbers
- [ ]   Implementation Parameters
- [ ] 13. Characters
- [ ]   Character Attributes
- [ ]   Predicates on Characters
- [ ]   Character Construction and Selection
- [ ]   Character Conversions
- [ ]   Character Control-Bit Functions
- [ ] 14. Sequences
- [ ]   Simple Sequence Functions
- [ ]   Concatenating, Mapping, and Reducing Sequences
- [ ]   Modifying Sequences
- [ ]   Searching Sequences for Items
- [ ]   Sorting and Merging
- [ ] 15. Lists
- [ ]   Conses
- [ ]   Lists
- [ ]   Alteration of List Structure
- [ ]   Substitution of Expressions
- [ ]   Using Lists as Sets
- [ ]   Association Lists
- [ ] 16. Hash Tables
- [ ]   Hash Table Functions
- [ ]   Primitive Hash Function
- [ ] 17. Arrays
- [ ]   Array Creation
- [ ]   Array Access
- [ ]   Array Information
- [ ]   Functions on Arrays of Bits
- [ ]   Fill Pointers
- [ ]   Changing the Dimensions of an Array
- [ ] 18. Strings
- [ ]   String Access
- [ ]   String Comparison
- [ ]   String Construction and Manipulation
- [ ] 19. Structures
- [ ]   Introduction to Structures
- [ ]   How to Use Defstruct
- [ ]   Using the Automatically Defined Constructor Function
- [ ]   Defstruct Slot-Options
- [ ]   Defstruct Options
- [ ]   By-Position Constructor Functions
- [ ]   Structures of Explicitly Specified Representational Type
- [ ]   Unnamed Structures
- [ ]   Named Structures
- [ ]   Other Aspects of Explicitly Specified Structures
- [ ] 20. The Evaluator
- [ ]   Run-Time Evaluation of Forms
- [ ]   The Top-Level Loop
- [ ] 21. Streams
- [ ]   Standard Streams
- [ ]   Creating New Streams
- [ ]   Operations on Streams
- [ ] 22. Input/Output
- [ ]   Printed Representation of Lisp Objects
- [ ]   What the Read Function Accepts
- [ ]   Parsing of Numbers and Symbols
- [ ]   Macro Characters
- [ ]   Standard Dispatching Macro Character Syntax
- [ ]   The Readtable
- [ ]   What the Print Function Produces
- [ ]   Input Functions
- [ ]   Input from Character Streams
- [ ]   Input from Binary Streams
- [ ]   Output Functions
- [ ]   Output to Character Streams
- [ ]   Output to Binary Streams
- [ ]   Formatted Output to Character Streams
- [ ]   Querying the User
- [ ] 23. File System Interface
- [ ]   File Names
- [ ]   Pathnames
- [ ]   Case Conventions
- [ ]   Structured Directories
- [ ]   Extended Wildcards
- [ ]   Logical Pathnames
- [ ]   Syntax of Logical Pathname Namestrings
- [ ]   Parsing of Logical Pathname Namestrings
- [ ]   Using Logical Pathnames
- [ ]   Examples of the Use of Logical Pathnames
- [ ]   Discussion of Logical Pathnames
- [ ]   Pathname Functions
- [ ]   Opening and Closing Files
- [ ]   Renaming, Deleting, and Other File Operations
- [ ]   Loading Files
- [ ]   Accessing Directories
- [ ] 24. Errors
- [ ]   General Error-Signaling Functions
- [ ]   Specialized Error-Signaling Forms and Macros
- [ ]   Special Forms for Exhaustive Case Analysis
- [ ] 25. Miscellaneous Features
- [ ]   The Compiler
- [ ]   Compiler Diagnostics
- [ ]   Compiled Functions
- [ ]   Compilation Environment
- [ ]   Similarity of Constants
- [ ]   Documentation
- [ ]   Debugging Tools
- [ ]   Environment Inquiries
- [ ]   Time Functions
- [ ]   Other Environment Inquiries
- [ ]   Identity Function
- [ ] 26. Loop
- [ ]   Introduction
- [ ]   How the Loop Facility Works
- [ ]   Parsing Loop Clauses
- [ ]   Order of Execution
- [ ]   Kinds of Loop Clauses
- [ ]   Loop Syntax
- [ ]   User Extensibility
- [ ]   Loop Constructs
- [ ]   Iteration Control
- [ ]   End-Test Control
- [ ]   Value Accumulation
- [ ]   Variable Initializations
- [ ]   Conditional Execution
- [ ]   Unconditional Execution
- [ ]   Miscellaneous Features
- [ ]   Data Types
- [ ]   Destructuring
- [ ] 27. Pretty Printing
- [ ]   Introduction
- [ ]   Pretty Printing Control Variables
- [ ]   Dynamic Control of the Arrangement of Output
- [ ]   Format Directive Interface
- [ ]   Compiling Format Control Strings
- [ ]   Pretty Printing Dispatch Tables
- [ ] 28. Common Lisp Object System
- [ ]   Programmer Interface Concepts
- [ ]   Error Terminology
- [ ]   Classes
- [ ]   Defining Classes
- [ ]   Creating Instances of Classes
- [ ]   Slots
- [ ]   Accessing Slots
- [ ]   Inheritance
- [ ]   Inheritance of Methods
- [ ]   Inheritance of Slots and Slot Options
- [ ]   Inheritance of Class Options
- [ ]   Examples
- [ ]   Integrating Types and Classes
- [ ]   Determining the Class Precedence List
- [ ]   Topological Sorting
- [ ]   Examples
- [ ]   Generic Functions and Methods
- [ ]   Introduction to Generic Functions
- [ ]   Introduction to Methods
- [ ]   Agreement on Parameter Specializers and Qualifiers
- [ ]   Congruent Lambda-Lists for All Methods of a Generic Function
- [ ]   Keyword Arguments in Generic Functions and Methods
- [ ]   Method Selection and Combination
- [ ]   Determining the Effective Method
- [ ]   Standard Method Combination
- [ ]   Declarative Method Combination
- [ ]   Built-in Method Combination Types
- [ ]   Meta-objects
- [ ]   Metaclasses
- [ ]   Standard Metaclasses
- [ ]   Standard Meta-objects
- [ ]   Object Creation and Initialization
- [ ]   Initialization Arguments
- [ ]   Declaring the Validity of Initialization Arguments
- [ ]   Defaulting of Initialization Arguments
- [ ]   Rules for Initialization Arguments
- [ ]   Shared-Initialize
- [ ]   Initialize-Instance
- [ ]   Definitions of Make-Instance and Initialize-Instance
- [ ]   Redefining Classes
- [ ]   Modifying the Structure of Instances
- [ ]   Initializing Newly Added Local Slots
- [ ]   Customizing Class Redefinition
- [ ]   Extensions
- [ ]   Changing the Class of an Instance
- [ ]   Modifying the Structure of an Instance
- [ ]   Initializing Newly Added Local Slots
- [ ]   Customizing the Change of Class of an Instance
- [ ]   Reinitializing an Instance
- [ ]   Customizing Reinitialization
- [ ]   Functions in the Programmer Interface
- [ ] 29. Conditions
- [ ]   Introduction
- [ ]   Changes in Terminology
- [ ]   Survey of Concepts
- [ ]   Signaling Errors
- [ ]   Trapping Errors
- [ ]   Handling Conditions
- [ ]   Object-Oriented Basis of Condition Handling
- [ ]   Restarts
- [ ]   Anonymous Restarts
- [ ]   Named Restarts
- [ ]   Restart Functions
- [ ]   Comparison of Restarts and Catch/Throw
- [ ]   Generalized Restarts
- [ ]   Interactive Condition Handling
- [ ]   Serious Conditions
- [ ]   Non-Serious Conditions
- [ ]   Condition Types
- [ ]   Signaling Conditions
- [ ]   Resignaling Conditions
- [ ]   Condition Handlers
- [ ]   Printing Conditions
- [ ]   Program Interface to the Condition System
- [ ]   Signaling Conditions
- [ ]   Assertions
- [ ]   Exhaustive Case Analysis
- [ ]   Handling Conditions
- [ ]   Defining Conditions
- [ ]   Creating Conditions
- [ ]   Establishing Restarts
- [ ]   Finding and Manipulating Restarts
- [ ]   Warnings
- [ ]   Restart Functions
- [ ]   Debugging Utilities
- [ ]   Predefined Condition Types
- [ ] A. Series
- [ ]   Introduction
- [ ]   Series Functions
- [ ]   Scanners
- [ ]   Mapping
- [ ]   Truncation and Other Simple Transducers
- [ ]   Conditional and Other Complex Transducers
- [ ]   Collectors
- [ ]   Alteration of Series
- [ ]   Optimization
- [ ]   Basic Restrictions
- [ ]   Constraint Cycles
- [ ]   Defining New Series Functions
- [ ]   Declarations
- [ ]   Primitives
- [ ] B. Generators and Gatherers
- [ ]   Introduction
- [ ]   Generators
- [ ]   Gatherers
- [ ]   Discussion
- [ ] C. Backquote
- [ ]   References
- [ ]   Index
- [ ]   About this document ...
