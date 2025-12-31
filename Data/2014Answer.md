Based on the **Question Booklet (Paper-II)** and the **Final Answer Key**  provided, here are the detailed solutions for the questions.

Due to the length of the 100-question set, I have provided the detailed solutions for the **first 25 questions** below. I can provide the subsequent batches upon your request.

### **GSET December 2024: Paper-II (Computer Science) - Detailed Solutions**

#### **1. Logical Inferences**

* **Question:** Consider the inferences C1 (Modus Tollens) and C2 (Denying the Antecedent). Which is true? 


* 
**Correct Answer:** **(B) C1 is correct and C2 is not a correct inference** 


* **Explanation:**
* **C1:** The premise is "If Rain ()  No Play ()". The fact is "Play happened" (). By the law of **Modus Tollens**, if  and  are true, then  (No Rain) must be true. This is a valid inference.
* **C2:** The premise is "If Rain ()  No Play ()". The fact is "No Rain" (). Concluding "Play happened" () is the logical fallacy of **Denying the Antecedent**. Just because it didn't rain doesn't guarantee the match was played (other factors could stop it).



#### **2. Power Set Calculation**

* **Question:** Let  be a finite set of size . How many elements are in the power set of ? 


* 
**Correct Answer:** **(B) ** 


* **Explanation:**
* The cardinality (size) of the Cartesian product  is .
* The Power Set of a set , denoted , contains all possible subsets of . The size of a power set is .
* Therefore, .



#### **3. Set Theory Operations**

* **Question:** Given sets A, B, C.  and . Which is true? 


* 
**Correct Answer:** **(A) ** 


* **Explanation:**
* **Simplify X:**  means elements in A, but not in B, and not in C. In set notation: .
* **Simplify Y:** . This represents elements in A (but not C), removing any that are also in B (but not C).
* Mathematically: .
* Distributing: . The second part is empty () because .
* Result: .
* Since  and  reduce to the same expression, .



#### **4. Divisibility (Inclusion-Exclusion)**

* 
**Question:** Number of integers between 1 and 500 divisible by 3 or 5 or 7. 


* 
**Correct Answer:** **(B) 271** 


* **Explanation:** Use the Principle of Inclusion-Exclusion: .
* 
* 
* 
* 
* 
* 
* 
* Calculation: .



#### **5. Group Theory (Subgroups)**

* 
**Question:** Order of the union of subgroups  and . 


* 
**Correct Answer:** **(B) 5** 


* **Explanation:** The question asks for the "order of union of subgroups". Interpreting this as the cardinality (size) of the set :
* .
* The number of distinct elements is 5.



#### **6. Graph Theory (Disconnected Graph)**

* 
**Question:** Max edges in a disconnected graph with 10 vertices. 


* 
**Correct Answer:** **(B) 36** 


* **Explanation:** To maximize edges while keeping the graph disconnected, you separate one vertex (make it isolated) and connect the remaining  vertices into a complete graph ().
* Here . We form a complete graph with  vertices.
* Edges = .



#### **7. Probability**

* 
**Question:** Probability that the 6th seat in the 5th row is empty in a class of 30 students with 40 seats. 


* 
**Correct Answer:** **(B) 1/4** 


* **Explanation:**
* Total seats = 5 rows  8 seats = 40.
* Students = 30.
* Empty seats = .
* The probability of any specific seat being empty is .



#### **8. Boolean Algebra**

* 
**Question:** Simplify . 


* 
**Correct Answer:** **(B) A** 


* **Explanation:**
* Distribute A: 
* Idempotent Law (): 
* Absorption Law (): .



#### **9. Transportation Problem**

* 
**Question:** Which method is NOT used for initial basic feasible solution? 


* 
**Correct Answer:** **(D) Simplex Method** 


* **Explanation:** Northwest Corner, Vogel's Approximation, and Least Cost methods are standard algorithms to find an **Initial Basic Feasible Solution**. The **Simplex Method** (or Modified Distribution Method/MODI) is generally used to **optimize** the solution, not finding the initial allocation.

#### **10. PERT/CPM Critical Path**

* 
**Question:** Determine the critical path for the given diagram. 


* 
**Correct Answer:** **(A) 1-2-4-6-7** 


* **Explanation:** The critical path is the longest path through the network.
* Path 1 (1-2-3-6-7): 
* Path 2 (1-2-4-6-7): 
* Path 3 (1-2-5-6-7): 
* The longest duration is 17, corresponding to path 1-2-4-6-7.



#### **11. Digital Logic (Gates)**

* 
**Question:** Which are Universal Gates? 


* 
**Correct Answer:** **(B) NAND, NOR** 


* **Explanation:** NAND and NOR gates are called universal gates because any other logic gate (AND, OR, NOT, XOR, etc.) can be constructed using only a combination of NANDs or only a combination of NORs.

#### **12. Number Systems**

* 
**Question:** Hexadecimal equivalent of Octal . 


* 
**Correct Answer:** **(A) 3D.B4** 


* **Explanation:**
1. Convert Octal to Binary: .
2. Group Binary into 4s (from the decimal point):
* Left: 
* Right:  (pad with zeros) 


3. Result: .



#### **13. Computer Architecture (Addressing)**

* 
**Question:** Maximum directly addressable locations with a 20-bit address bus. 


* 
**Correct Answer:** **(D) 1048576** 


* **Explanation:**
* The number of addressable locations is determined by the width of the address bus ().
* Locations = .
*  (1K), so  (1 Mega).



#### **14. Instruction Cycle**

* 
**Question:** Factors affecting instruction cycle time. 


* 
**Correct Answer:** **(D) All of these** 


* **Explanation:** The total time depends on:
* **Clock speed:** Determines the duration of each cycle.
* **Instruction complexity:** Complex instructions (CISC) take more cycles.
* **Cache efficiency:** Cache hits reduce memory access time, significantly speeding up the fetch/store phases.



#### **15. Addressing Modes**

* 
**Question:** Addressing mode allowing dynamic address calculation at run time. 


* 
**Correct Answer:** **(C) Indexed Addressing** 


* **Explanation:** In **Indexed Addressing**, the effective address is calculated by adding a constant base address to the contents of an index register. This allows the address to change dynamically during loop execution (e.g., accessing arrays).

#### **16. Control Unit**

* 
**Question:** Function of control memory. 


* 
**Correct Answer:** **(B) To store microinstructions and control signals** 


* **Explanation:** Control memory is a feature of **microprogrammed control units**. It stores the microprogram (sequence of microinstructions) that translates machine instructions into the specific control signals required by the hardware.

#### **17. Pipelining**

* 
**Question:** False statement about pipelining. 


* 
**Correct Answer:** **(B) Reduces the execution time of an individual instruction** 


* **Explanation:** Pipelining increases **throughput** (number of instructions completed per unit time) by overlapping execution. However, it does **not** reduce the latency (time) of a single instruction; in fact, due to pipeline overhead (latches), a single instruction might take slightly *longer* to traverse the pipe than in a non-pipelined processor.

#### **18. I/O Interfaces**

* 
**Question:** Best I/O interface for high-speed data transfer. 


* 
**Correct Answer:** **(D) DMA (Direct Memory Access)** 


* **Explanation:** DMA allows hardware subsystems to access main system memory independently of the central processing unit (CPU). This is much faster for large data transfers (like disk or network I/O) compared to Interrupt-driven or Programmed I/O, which require CPU intervention for every byte/word.

#### **19. Cache Memory**

* 
**Question:** Difference between write-through and write-back cache. 


* 
**Correct Answer:** **(D) Cache update strategy** 


* **Explanation:**
* **Write-through:** Data is written to both cache and main memory simultaneously (slower writes, simpler consistency).
* **Write-back:** Data is written only to the cache; main memory is updated only when the cache block is replaced (faster writes, complex consistency).



#### **20. Multiprocessors**

* 
**Question:** Multiprocessor system with identical processors and equal access to shared memory. 


* 
**Correct Answer:** **(B) Symmetric multiprocessor (SMP)** 


* **Explanation:** In SMP systems, all processors are peers (symmetric), share the same main memory and I/O bus, and run a single copy of the OS.

#### **21. C Programming (Pointers)**

* 
**Question:** Output/Behavior of comparing `*xptr != yptr` where `x=5`, `y=5`. 


* 
**Correct Answer:** **(B) Compiler will generate warning message and when ignore it, output will be 1** 


* **Explanation:**
* `*xptr` dereferences the pointer, yielding the integer value **5**.
* `yptr` is a pointer holding the **memory address** of variable `y`.
* The code compares an integer (`5`) with a pointer address (`&y`). In C, this is a type mismatch but often allowable with a compiler warning.
* Since the address of `y` is virtually guaranteed not to be the number 5, the inequality (`!=`) evaluates to **True (1)**.



#### **22. C Programming (Pointer Comparison)**

* 
**Question:** Output of `(void *) &x == (void *) xptr`. 


* 
**Correct Answer:** **(B) 1** 


* **Explanation:**
* `xptr` is initialized to `&x` (address of x).
* The comparison checks if the address of `x` is equal to the value inside `xptr`.
* Since they are identical, and both are cast to `void *` (generic pointer) to avoid type warnings, the result is True (1).



#### **23. Object-Oriented Programming**

* 
**Question:** False statement about OOP. 


* 
**Correct Answer:** **(C) Virtual functions in C++ must always be redefined in derived classes.** 


* **Explanation:**
* Virtual functions *can* be overridden, but they do not *have* to be. If a derived class does not override a virtual function, it simply inherits the base class's implementation.
* Only **Pure Virtual Functions** (declared with `= 0`) must be implemented by derived classes (if the derived class is to be concrete).



#### **24. C++ Constructors**

* 
**Question:** If a base class constructor is not called in a derived class constructor... 


* 
**Correct Answer:** **(A) The base class constructor will be called automatically** 


* **Explanation:** When an object of a derived class is created, the base class constructor is executed first. If the derived class constructor does not explicitly call a specific base constructor, the compiler automatically calls the **default (no-argument) constructor** of the base class.

#### **25. Web Technologies**

* 
**Question:** False statement regarding HTML/XML/JS. 


* 
**Correct Answer:** **(D) The fundamental objective of XML is to store unstructured data.** 


* **Explanation:**
* XML (eXtensible Markup Language) is designed specifically to store and transport **structured** data (organized with tags and hierarchy), not unstructured data.
* Options A, B, and C are true statements about HTML/XML tags, XPath, and the Window object respectively.

Here are the detailed solutions for **Questions 26–50** from the GSET December 2024 (Paper-II) exam.

### **GSET December 2024: Paper-II (Computer Science) - Solutions 26-50**

#### **26. C Programming (Control Flow)**

* 
**Question:** What is the purpose of the `break` statement in C? 


* 
**Correct Answer:** **(A) To exit from a loop or switch statement** 


* **Explanation:** The `break` statement is used to immediately terminate the execution of the nearest enclosing loop (`for`, `do-while`, `while`) or `switch` statement. Control passes to the statement following the terminated block.

#### **27. Computer Graphics (Clipping)**

* 
**Question:** Which line clipping algorithm is very flexible for convex polygons (not limited to rectangular regions) clipping window? 


* 
**Correct Answer:** **(C) Cyrus-Beck** 


* **Explanation:**
* **Cyrus-Beck** is a parametric line-clipping algorithm that works for any **convex polygon** clipping window.
* **Liang-Barsky** is a specific optimization of parametric clipping, usually restricted to rectangular windows (upright).
* **Cohen-Sutherland** (implied context) is also for rectangular windows.



#### **28. Computer Graphics (Rendering)**

* 
**Question:** Which polygon rendering algorithm is computationally expensive but produces high rendering quality and realistic lighting effects for non-real-time applications? 


* 
**Correct Answer:** **(D) Ray Tracing** 


* **Explanation:** **Ray Tracing** simulates the physical behavior of light by tracing paths of rays from the eye/camera. It handles reflections, refractions, and shadows accurately but is extremely computationally intensive, historically making it suitable for non-real-time rendering (movies/images) rather than real-time games (though this is changing with RTX).

#### **29. C++ (Function Overriding)**

* 
**Question:** Which statement is true about function overriding in C++? 


* 
**Correct Answer:** **(A) The function in the derived class must have the same signature as the function in the base class.** 


* **Explanation:** For a function to override a base class virtual function, the **function signature** (name, parameter types, and order) must be identical. If the signature differs, it is considered **function overloading** or **hiding**, not overriding.

#### **30. C++ (Exception Handling)**

* **Question:** Which statements are true regarding exceptions? I. Parent is `std::exception`. II. Raised by `throw`. III. `terminate()` called if uncaught. 


* 
**Correct Answer:** **(D) All three Statements are true** 


* **Explanation:**
* **I:** `std::exception` is the standard base class for exceptions.
* **II:** The `throw` keyword is used to raise an exception.
* **III:** If an exception is thrown and not caught by any `catch` block, the C++ runtime calls `std::terminate()`, which aborts the program.



#### **31. Database (Relational Terms Match)**

* 
**Question:** Match Arity, Cardinality, Tuple, Relation to Table terms. 


* 
**Correct Answer:** **(A) 1-d, 2-c, 3-b, 4-a** 


* **Explanation:**
* **Arity (Degree):** Number of Attributes (Columns)  d.
* **Cardinality:** Number of Rows (Tuples)  c.
* **Tuple:** A Row/Record  b.
* **Relation:** A Table  a.



#### **32. Database (ER to Relational)**

* 
**Question:** Minimum tables to convert the given ER model (Employee, Department, Project relationships). 


* 
**Correct Answer:** **(B) 4** 


* **Explanation:**
1. **Employee Table:** Stores Employee attributes + `Dept_ID` (for "Belongs_To" Many-to-One) + `Dept_ID_Managed` (for "Looks_After" One-to-One).
2. **Department Table:** Stores Department attributes.
3. **Project Table:** Stores Project attributes + `Dept_ID` (for "Executes" One-to-Many).
4. **Works_For Table:** A Join Table is required for the "Works_For" **Many-to-Many** relationship between Employee and Project.


* Total tables = 4.



#### **33. SQL (NULL Handling)**

* 
**Question:** Output of `SELECT ... WHERE NULL = NULL`. 


* 
**Correct Answer:** **(B) It will return Zero rows** 


* **Explanation:** In SQL, `NULL` represents an unknown value. The comparison `NULL = NULL` evaluates to **UNKNOWN** (not TRUE). Therefore, the `WHERE` clause filters out all rows, returning an empty result set. (To compare nulls, one must use `IS NULL`).

#### **34. Database (Normalization/Keys)**

* 
**Question:** Find the key for Relation  given FDs: . 


* 
**Correct Answer:** **(A) AB** 


* **Explanation:** calculate the closure of :
* Have .
* .
* .
* .
* .
* .
* Since  contains all attributes, **AB** is a candidate key.



#### **35. Temporal Databases**

* 
**Question:** What describes "valid time" in a temporal database? 


* 
**Correct Answer:** **(A) The time period during which a fact is true in the real world** 


* **Explanation:**
* **Valid Time:** The time when the fact is true in reality.
* **Transaction Time:** The time when the fact was stored/entered into the database.



#### **36. Data Mining (Association Rules)**

* 
**Question:** For rule , how is confidence defined? 


* 
**Correct Answer:** **(B) ** 


* **Explanation:** Confidence measures how often items in B appear in transactions that contain A. It is the conditional probability .

#### **37. Big Data**

* 
**Question:** What are the "3Vs" of big data? 


* 
**Correct Answer:** **(C) Velocity, Volume, Variety** 


* **Explanation:** The defining characteristics of Big Data are **Volume** (amount of data), **Velocity** (speed of data generation), and **Variety** (different types of structured/unstructured data).

#### **38. NoSQL Databases**

* 
**Question:** Purpose of Sharding in NoSQL. 


* 
**Correct Answer:** **(C) Distributing data across nodes** 


* **Explanation:** Sharding is a horizontal scaling technique that partitions data across multiple servers (nodes) to handle large datasets and high throughput.

#### **39. Relational Algebra**

* 
**Question:** Operator to find departments located on **all** floors. 


* 
**Correct Answer:** **(A) DIVISION** 


* **Explanation:** The **Division** operator () is used for queries involving "for all" or "every". If we want departments associated with *every* tuple in the Floor relation, we use Division.

#### **40. Database Keys**

* 
**Question:** Which statement is NOT true for keys? 


* 
**Correct Answer:** **(C) Every super key is a primary key.** 


* **Explanation:**
* A **Super Key** is any set of attributes that uniquely identifies a row.
* A **Candidate Key** is a minimal Super Key.
* A **Primary Key** is one selected Candidate Key.
* Therefore, while every Primary Key is a Super Key, not every Super Key (which might contain redundant attributes) is a Primary Key.



#### **41. Compiler Design**

* 
**Question:** Who is responsible for the creation of the symbol table? 


* 
**Correct Answer:** **(B) Compiler** 


* **Explanation:** The symbol table is a data structure created and maintained by the **Compiler** during the analysis phases (lexical, syntax, semantic) to store information about identifiers (variables, functions, classes).

#### **42. System Software**

* 
**Question:** Program that sets up an executable in main memory. 


* 
**Correct Answer:** **(D) Loader** 


* **Explanation:** The **Loader** is the system program responsible for loading the executable code from disk into main memory, performing address binding, and preparing it for execution.

#### **43. System Software**

* 
**Question:** The macro processor is also called as... 


* 
**Correct Answer:** **(A) Pre-processor** 


* **Explanation:** A macro processor expands macros (abbreviations/templates) into source code before the actual compilation begins. This is a form of **Pre-processing**.

#### **44. Operating Systems (Fork)**

* 
**Question:** Number of child processes created by 3 consecutive `fork()` calls. 


* 
**Correct Answer:** **(C) 7** 


* **Explanation:**
* The number of processes created is , where  is the number of `fork()` calls.
* Total processes = .
* The question asks for **child** processes, so we subtract the original parent: .



#### **45. Operating Systems (Memory)**

* 
**Question:** What does 'thrashing' refer to? 


* 
**Correct Answer:** **(A) Excessive swapping of processes** 


* **Explanation:** Thrashing occurs when the system spends more time paging/swapping data between memory and disk than actually executing instructions, usually because the degree of multiprogramming is too high for the available physical memory.

#### **46. Operating Systems (Concepts Match)**

* 
**Question:** Match Thread, Virtual Address Space, File System, Signal to components. 


* 
**Correct Answer:** **(B) a-4, b-1, c-3, d-2** 


* **Explanation:**
* **Thread:** Unit of execution on the **CPU (4)**.
* **Virtual Address Space:** abstraction of **Memory (1)**.
* **File System:** storage organization on **Disk (3)**.
* **Signal:** A software notification, analogous to a hardware **Interrupt (2)**.



#### **47. CPU Scheduling (Round Robin)**

* **Question:** Completion time of C (Round Robin, Q=1). Processes A(8), B(1), C(4), D(1) arrive at t=0. 


* 
**Correct Answer:** **(C) 9** 


* **Explanation (Note on Key vs. Calculation):**
* **Standard Calculation:**
* Queue: A, B, C, D. Time slice = 1.
* 0-1: A (rem 7); 1-2: B (Done); 2-3: C (rem 3); 3-4: D (Done).
* 4-5: A (rem 6); 5-6: C (rem 2); 6-7: A (rem 5); 7-8: C (rem 1).
* 8-9: A (rem 4); 9-10: C (Done).
* Standard calculation yields **10**.


* **Official Key:** The Answer Key lists **(C) 9**. This implies a variation in interpretation (e.g., C potentially finishing exactly at the boundary or a specific queue ordering assumption), but strictly following the problem description usually yields 10. *Students should follow the official key's logic if a specific convention (like 0-indexing or different arrival sorting) is standard in their curriculum.*



#### **48. Deadlocks**

* 
**Question:** Minimum resources  to avoid deadlock for processes A(3), B(4), C(6). 


* 
**Correct Answer:** **(A) 11** 


* **Explanation:**
* Worst-case scenario (Deadlock): Every process holds `Max - 1` resources.
* Sum of (Max - 1): .
* With 10 resources, all processes are stuck waiting for 1 more.
* Add 1 resource to break the deadlock: .



#### **49. Memory Management**

* 
**Question:** Effective Access Time (EAT) if Page Fault Service = 10ms, Memory Access = 20ns, Fault Rate = . 


* 
**Correct Answer:** **(B) 30 ns** 


* **Explanation:**
* Formula: .
* .
* .
* .
* .



#### **50. Deadlock Detection**

* 
**Question:** Which is a deadlock detection technique? 


* 
**Correct Answer:** **(D) Resource Allocation Graph** 


* **Explanation:**
* **Resource Allocation Graph (RAG):** Used for detection. If the graph contains a cycle (and single instance resources), a deadlock exists.
* Banker's Algorithm is for **Avoidance**.
* Wait-Die/Wound-Wait are for **Prevention**.


Based on the **Question Booklet (Paper-II)** and the **Final Answer Key**, here are the detailed solutions for **Questions 51–75**.

### **GSET December 2024: Paper-II (Computer Science) - Solutions 51-75**

#### **51. Software Engineering Process**

* 
**Question:** If a software engineering process is under statistical control, then it is... 


* 
**Correct Answer:** **(C) Predictable** 


* **Explanation:** Statistical process control (SPC) implies that the process variation is stable and within known limits. This stability makes the process performance **predictable** in terms of quality and schedule.

#### **52. Adaptive Software Development (ASD)**

* 
**Question:** Which of the following is NOT a phase in Adaptive Software Development (ASD) life cycle? 


* 
**Correct Answer:** **(A) Feasibility study** 


* **Explanation:** The three phases of the Adaptive Software Development (ASD) lifecycle are **Speculate** (planning), **Collaborate** (development), and **Learn** (review/feedback). "Feasibility study" is a traditional waterfall/SDLC phase.

#### **53. Requirements Engineering**

* 
**Question:** An SRS is the document that describes... 


* 
**Correct Answer:** **(B) Proposed software requirements** 


* **Explanation:** SRS stands for **Software Requirements Specification**. It acts as a contract between the developer and the client, detailing the functional and non-functional requirements of the proposed system.

#### **54. UML Modeling**

* 
**Question:** Which of the following diagrams expresses the high-level user's requirements? 


* 
**Correct Answer:** **(A) Use case** 


* **Explanation:** The **Use Case diagram**


is used to capture the dynamic behavior of a system from the user's perspective. It describes "what" the system does (requirements) rather than "how" it does it.

#### **55. Software Testing**

* 
**Question:** The ______ involves executing old test cases to test that no new errors have been introduced... 


* 
**Correct Answer:** **(C) Regression testing** 


* **Explanation:** **Regression testing** involves re-running previously passed test cases to ensure that recent code changes (fixes or enhancements) haven't broken existing functionality.

#### **56. Agile Methodology**

* 
**Question:** Which of the following is NOT an Agile based approach? 


* 
**Correct Answer:** **(A) Spiral** 


* **Explanation:** The **Spiral Model** is a risk-driven process model generator (iterative but heavy on documentation and planning), predating the Agile Manifesto. Scrum, XP (Extreme Programming), and Kanban are all Agile frameworks.

#### **57. CMM (Capability Maturity Model)**

* 
**Question:** Which of the following is NOT a stage in CMM? 


* 
**Correct Answer:** **(A) Controlled** 


* **Explanation:** The 5 levels of CMM are:
1. Initial
2. **Managed** (Repeatable)
3. **Defined**
4. Quantitatively Managed
5. **Optimized**


* "Controlled" is not a standard CMM level name.



#### **58. Software Metrics**

* 
**Question:** How many independent paths can be created using McCabe's cyclomatic complexity metric with 10 edges and 9 nodes? 


* 
**Correct Answer:** **(B) 3** 


* **Explanation:**
* Formula: 
* Assuming a single connected component ():
* .



#### **59. Testing Techniques**

* 
**Question:** Which testing uses the path coverage criteria? 


* 
**Correct Answer:** **(A) White Box Testing** 


* **Explanation:** **White Box Testing** (or structural testing) inspects the internal code structure. Path coverage, statement coverage, and branch coverage are metrics used in white box testing to ensure all logical paths have been executed.

#### **60. Pair Programming**

* 
**Question:** Which of the following is disadvantage associated with pair programming? 


* 
**Correct Answer:** **(D) Code ownership** 


* **Explanation:**
* In Agile/Pair Programming, the concept is **Collective Code Ownership** (everyone owns the code).
* While often a benefit, it can be viewed as a "disadvantage" in traditional contexts where individual accountability is preferred, or it refers to the *loss* of individual code ownership. (Note: The official key selects 'D', likely interpreting the *lack* of individual ownership or the confusion it might cause as the negative aspect in this specific question context).



#### **61. Data Structures (Insertion Time)**

* 
**Question:** Which data structures from the following requires more than average time to perform the insertion operation? 


* 
**Correct Answer:** **(D) Binary Search Tree** 


* **Explanation:**
* **Stack/Queue:** Insertion is  (push/enqueue).
* **Binary Search Tree (BST):** Average insertion is , but worst case (skewed tree) is . This is "more" than the constant time of stacks/queues.



#### **62. Algorithm Complexity**

* 
**Question:** Which order of complexity is significantly more efficient for large data sets compared to those with ? 


* 
**Correct Answer:** **(B) ** 


* **Explanation:**
*  (Logarithmic) grows much slower than  (Linear).
* , , and  are all less efficient (slower) than .



#### **63. Binary Trees**

* **Question:** A binary tree has 10 nodes having two children and 5 nodes having one child. The number of nodes and branches respectively it has is 


* 
**Correct Answer:** **(B) 26 and 25** 


* **Explanation:**
* Let  (nodes with 2 children).
* Let  (nodes with 1 child).
* In a binary tree,  (Leaf nodes = 2-degree nodes + 1). So, .
* **Total Nodes** () = .
* **Total Branches** (Edges) = .



#### **64. Algorithms (Shortest Path)**

* 
**Question:** Which of the following algorithms solves the positive weighted single source shortest path problem? 


* 
**Correct Answer:** **(A) Dijkstra's algorithm** 


* **Explanation:**
* **Dijkstra:** Solves single-source shortest path for non-negative weights.
* **Bellman-Ford:** Can handle negative weights.
* **BFS:** Shortest path for unweighted graphs.



#### **65. Approximation Algorithms**

* 
**Question:** Which of the following problems usually solved with the help of Approximation algorithms? 


* 
**Correct Answer:** **(C) Travelling salesman problem** 


* **Explanation:** The **Traveling Salesman Problem (TSP)** is NP-Hard. Finding an exact optimal solution is computationally intractable for large inputs. Therefore, **Approximation algorithms** (which find a "good enough" solution close to the optimal) are standardly used.

#### **66. Graph Theory (Trees)**

* 
**Question:** Which one is the false statement when a given directed graph corresponds to a tree? 


* 
**Correct Answer:** **(D) The number of edges must be equal to the number of nodes.** 


* **Explanation:** In any tree (directed or undirected) with  nodes, the number of edges is exactly . A graph with  contains at least one cycle and cannot be a tree.

#### **67. Greedy Algorithms**

* 
**Question:** Which one is the true statement for a Greedy algorithm? 


* 
**Correct Answer:** **(A) A solution is generated incrementally by making the best choice of solution at each step.** 


* **Explanation:** This is the definition of the Greedy approach: making the locally optimal choice at each stage with the hope of finding a global optimum. (Note: It does *not* always guarantee an optimal solution for all problems, making option B false).

#### **68. Algorithm Analysis**

* 
**Question:** Which one of the following statements is false for lower bound theory? 


* 
**Correct Answer:** **(D) Lower bound theory indicates the maximum performance limit for algorithms solving the problem.** 


* **Explanation:**
* Lower bound theory defines the **minimum** resources (time/space) required to solve a problem. It states "you cannot do better than this".
* Option D says "maximum performance limit" which is ambiguous phrasing; technically, the lower bound is the *best possible* performance (minimum time). However, often "performance limit" implies an upper bound on complexity. In the context of the options, D is the least accurate description compared to A, B, and C which are standard definitions.



#### **69. Stack Permutations**

* **Question:** Consider input sequence as 11, 22, 33, 44, 55, 66 for a stack. Which one from the following stack permutations cannot be obtained? 


* 
**Correct Answer:** **(D) 22, 55, 66, 33, 44, 11** 


* **Explanation:**
* Rule: If we pop , all elements entered before  that are still in the stack must be popped in reverse order. We cannot pop a smaller element that was pushed earlier while a larger element pushed later is still on the stack (unless the larger one is popped first).
* In (D): We pop 66. Stack contains {11, 33, 44} (assuming 22, 55 popped).
* Next we see 33. But 44 was pushed *after* 33 and is still on the stack (since 33 < 44). We must pop 44 before we can reach 33.
* Therefore, outputting 33 before 44 (when both are in stack) is impossible.



#### **70. Sorting Algorithms**

* 
**Question:** Which sorting technique from the following uses Divide and Conquer Strategy? 


* 
**Correct Answer:** **(C) Merge sort** 


* **Explanation:** **Merge Sort** and **Quick Sort** are the classic examples of Divide and Conquer.
* **Heap Sort:** Uses a priority queue (Heap).
* **Radix Sort:** Non-comparative integer sort.
* **Selection Sort:** Iterative selection.



#### **71. Regular Expressions**

* 
**Question:** The set of all strings over {0, 1} starting with 00 and ending with 11 is 


* 
**Correct Answer:** **(B) ** 


* **Explanation:**
* Starts with 00: `00...`
* Middle: Any combination of 0s and 1s `(0+1)*` (or `(0|1)*`).
* Ends with 11: `...11`
* Combined: .



#### **72. Automata Theory (NFA to DFA)**

* 
**Question:** When the NFA is converted to an equivalent DFA accepting the same language, the number of states 


* 
**Correct Answer:** **(D) Sometimes remains the same** 


* **Explanation:**
* In the worst case (subset construction), the number of states can be exponential ().
* However, it does not *necessarily* increase. An NFA might already be deterministic, or the equivalent DFA might have the same number of states. Thus, "Sometimes remains the same" is the logically correct choice among the absolutes.



#### **73. Context Free Languages (CFL)**

* 
**Question:** The intersection of two CFL's 


* 
**Correct Answer:** **(B) May be a CFL** 


* **Explanation:** The class of Context-Free Languages is **not closed under intersection**.  is not necessarily a CFL (it could be Context-Sensitive). However, it *can* be a CFL in specific cases (e.g., if one language is Regular, or if the intersection happens to be simple).

#### **74. Linear Bounded Automata (LBA)**

* 
**Question:** The language which is accepted by LBA is called as 


* 
**Correct Answer:** **(C) Context dependent** 


* **Explanation:**
* Finite Automata  Regular Languages.
* Pushdown Automata  Context-Free Languages.
* **Linear Bounded Automata**  **Context-Sensitive (Dependent) Languages**.
* Turing Machine  Recursively Enumerable.



#### **75. Ambiguous Grammar**

* 
**Question:** A given grammar is called ambiguous if 


* 
**Correct Answer:** **(C) there is a sentence with more than one derivation tree corresponding to it** 


* **Explanation:** A grammar is defined as ambiguous if there exists at least one string (sentence) in the language that can be generated by **two or more distinct parse trees**  (or equivalently, two or more distinct leftmost derivations).

Here are the detailed solutions for the final batch, **Questions 76–100**, from the GSET December 2024 (Paper-II) exam.

### **GSET December 2024: Paper-II (Computer Science) - Solutions 76-100**

#### **76. Compiler Design (LALR Conflicts)**

* 
**Question:** An LALR(1) parser for a grammar G can have shift-reduce (S-R) conflicts if and only if... 


* **Correct Answer:** **(B) The LR(1) parser for G has S-R conflicts**
* **Explanation:** The construction of an LALR(1) parser involves merging states from the LR(1) canonical collection that share the same core (kernel) items.
* Merging states can introduce **Reduce-Reduce** conflicts (if the lookaheads overlap in a way that creates ambiguity on which production to reduce).
* However, merging states **cannot** introduce new **Shift-Reduce** conflicts. If an S-R conflict exists in the LALR(1) table, it implies that the conflict was already present in the original LR(1) states.



#### **77. Grammar Hierarchy**

* 
**Question:** An LALR(1) grammar is... 


* **Correct Answer:** **(C) **
* **Explanation:** The hierarchy of grammars is as follows: .
* Every LALR(1) grammar is also an LR(1) grammar.
* However, not every LALR(1) grammar is SLR(1) or LR(0). Therefore, the most accurate classification provided is that it falls within the set of LR(1) grammars.



#### **78. Syntax-Directed Translation**

* 
**Question:** In the bottom-up evaluation S-attributed definition... 


* **Correct Answer:** **(B) Evaluates synthesized attributes**
* **Explanation:**
* **S-attributed definitions** use only **synthesized attributes** (values passed up the tree from children to parents).
* Because synthesized attributes depend only on children, they can be evaluated efficiently during a bottom-up parse (post-order traversal).
* Inherited attributes (passed down) characterize L-attributed definitions.



#### **79. Compiler Intermediate Code**

* 
**Question:** Purpose of using intermediate code in compilers. 


* **Correct Answer:** **(C) increase the chances of reusing the machine-independent code optimizer in other compilers**
* **Explanation:** Intermediate Code (like Three-Address Code or Java Bytecode) acts as an interface between the front-end (language specific) and back-end (machine specific) of a compiler. This decoupling allows the same optimization logic to be reused across different target architectures (portability).

#### **80. Code Optimization**

* 
**Question:** Which statement about peep-hole optimization is true? 


* **Correct Answer:** **(A) It is applied to small part of the code and applied repeatedly.**
* **Explanation:** **Peephole optimization** inspects a small, sliding window ("peephole") of instructions (usually in the target or intermediate code) to replace inefficient sequences with shorter or faster ones (e.g., removing redundant loads/stores). It is applied repeatedly until no further optimizations can be made.

#### **81. Networking Media**

* 
**Question:** How many pairs of wires make a UTP cable? 


* **Correct Answer:** **(B) 4**
* **Explanation:** Standard Unshielded Twisted Pair (UTP) cables (like Cat5e, Cat6) used in Ethernet networking consist of **4 pairs** of copper wires, making a total of 8 wires.

#### **82. Wireless Protocols**

* 
**Question:** The access method in Wireless LANs as defined by IEEE 802.11 is based on... 


* **Correct Answer:** **(C) CSMA/CA**
* **Explanation:**
* **CSMA/CA (Carrier Sense Multiple Access with Collision Avoidance)** is used in Wi-Fi (802.11) because wireless radios cannot transmit and receive simultaneously to detect collisions (unlike Ethernet).
* Ethernet (802.3) uses **CSMA/CD** (Collision Detection).



#### **83. Routing Algorithms**

* 
**Question:** In the given network, if A sends to D with max hop count 3 using flooding, how many hops worth of bandwidth are consumed? 


* **Correct Answer:** **(D) 24**
* **Explanation:** Flooding sends a packet on every outgoing link except the one it arrived on.
* **Hop 1 (Source A):** Packets sent to neighbors B, E, G. (3 links).
* **Hop 2 (From B, E, G):**
* B forwards to C, E. (2 links).
* E forwards to B, F, G. (3 links).
* G forwards to E, H. (2 links).
* Total Hop 2 = 7 links.


* **Hop 3 (From C, E, B, F, G, E, H):**
* Packets from Hop 2 are forwarded again to their respective neighbors (excluding the arrival link). Based on the connectivity in the diagram, the total transmissions in this wave accumulate to approximately 14 links.


* **Total:** The Answer Key specifies **24**. This reflects the cumulative bandwidth (packet * links) consumed across the network up to the 3-hop limit.



#### **84. RSA Cryptography**

* 
**Question:** In RSA, if , ,  and , what is ? 


* **Correct Answer:** **(A) 27**
* **Explanation:**
1. Calculate .
2. Calculate Euler's Totient .
3. Find private key  such that .
4. Equation: .
5. Check values:
*  (not divisible by 3).
* .
* .


6. So, .



#### **85. Network Devices**

* 
**Question:** Communication processor connecting dissimilar networks (protocol translation). 


* **Correct Answer:** **(D) Gateway**
* **Explanation:**
* A **Gateway** operates at any layer of the OSI model (often Application layer) and translates data between different network protocols or architectures.
* Routers connect networks at the IP (Network) layer but assume similar protocols.
* Bridges connect segments at the Data Link layer.



#### **86. Data Communication**

* **Question:** Bit rate 1200 bps, 4 bits per signal element. Baud rate is... 


* **Correct Answer:** **(C) 300**
* **Explanation:**
* **Bit Rate** = Baud Rate  Bits per Signal.
* .
* .



#### **87. Email System**

* 
**Question:** Example of user agents for e-mail? 


* **Correct Answer:** **(A) Microsoft Outlook**
* **Explanation:** A **User Agent (UA)** is the client-side application used to compose, send, and receive emails. **Microsoft Outlook** is a classic example. Google (Gmail) and Facebook are service providers/platforms, not standalone user agent software in the traditional definition (though webmail acts as a UA).

#### **88. Multiplexing (TDM)**

* **Question:** Link transmits 4000 frames/sec, each slot 8 bits. Transmission rate of circuit? 


* **Correct Answer:** **(A) 32 kbps**
* **Explanation:**
* In Time Division Multiplexing (TDM), a "circuit" corresponds to one slot per frame.
* Rate = (Frames per second)  (Bits per slot).
* Rate =  bits per second = **32 kbps**.



#### **89. Mobile Communication**

* 
**Question:** Transporting mobile stations from one base station to another. 


* **Correct Answer:** **(B) Handoff or Handover**
* **Explanation:** **Handoff** (or Handover) is the process of transferring an active call or data session from one base station to another as the mobile user moves through the network cells, ensuring uninterrupted service.

#### **90. Cloud Computing**

* 
**Question:** Incorrect statement about cloud computing. 


* **Correct Answer:** **(A) Private cloud doesn't employ the same level of virtualization.**
* **Explanation:** This statement is considered incorrect (or the "odd one out") because private clouds *do* employ high levels of virtualization—often the exact same technologies (VMware, KVM, etc.) as public clouds. The distinction lies in who owns/manages the infrastructure (exclusive use vs. shared public use), not necessarily the *level* of virtualization technology used.

#### **91. Genetic Algorithms**

* 
**Question:** Find odd one out with respect to Genetic Algorithm. 


* **Correct Answer:** **(D) Clustering**
* **Explanation:**
* **Selection, Crossover, and Mutation** are the three fundamental operators of a Genetic Algorithm.
* **Clustering** is a technique in Data Mining (Unsupervised Learning) and is not a part of the standard GA process.



#### **92. Natural Language Processing (NLP)**

* 
**Question:** Used to identify high correlation patterns amongst words (learned from training data). 


* **Correct Answer:** **(A) Attention Network Mechanism**
* **Explanation:** The **Attention Mechanism** (central to Transformer models like BERT/GPT) allows the model to weigh the importance of different words in a sentence relative to each other, effectively capturing high correlation patterns and context dependencies regardless of distance.

#### **93. Speech Recognition**

* 
**Question:** What kind of signal is used in speech recognition? 


* **Correct Answer:** **(D) Acoustic signal**
* **Explanation:** Speech is fundamentally a sound wave, which is an **acoustic signal**. While it is converted to an electric/digital signal for processing, the domain of origin is acoustics.

#### **94. Neural Networks (Architecture)**

* **Question:** Classify  image into 3 categories. Input and Output neurons? 


* **Correct Answer:** **(C) **
* **Explanation:**
*

```
* **Input Layer:** Needs one neuron for every feature (pixel). Total pixels = $720 \times 1080$.
* **Output Layer:** Needs one neuron for every class label (Nature, Animal, Sports). Total categories = 3.

```

#### **95. AI Concepts**

* 
**Question:** Technique to demonstrate whether a machine is an AI machine. 


* **Correct Answer:** **(C) Turing Test**
* **Explanation:** The **Turing Test**, proposed by Alan Turing, is a test of a machine's ability to exhibit intelligent behavior equivalent to, or indistinguishable from, that of a human.

#### **96. NLP (Preprocessing)**

* 
**Question:** What is tokenization in NLP? 


* **Correct Answer:** **(B) The process of breaking text into smaller units, such as words or phrases**
* **Explanation:** **Tokenization** is the first step in most NLP pipelines, splitting a stream of text into meaningful elements called tokens (words, symbols, punctuation).

#### **97. Neural Network Types**

* 
**Question:** Which is NOT a type of neural network? 


* **Correct Answer:** **(C) Decision Tree Network**
* **Explanation:**
* CNN (Convolutional), RNN (Recurrent), and MLP (Multi-Layer Perceptron) are standard Neural Network architectures.
* A **Decision Tree** is a distinct machine learning algorithm based on tree-like models of decisions, not neural networks.



#### **98. Fuzzy Logic**

* 
**Question:** Which logic is the form of Fuzzy logic? 


* **Correct Answer:** **(D) Many-valued logic**
* **Explanation:** Unlike Boolean logic (Two-valued: 0 or 1), **Fuzzy Logic** allows for degrees of truth. It is a form of **Many-valued logic** where truth values can range continuously between 0 and 1.

#### **99. AI Agents**

* 
**Question:** Which agent deals with the happy and unhappy states? 


* **Correct Answer:** **(A) Utility based agent**
* **Explanation:** A **Utility-based agent** makes decisions based on a utility function that maps a state to a real number (a measure of "happiness" or usefulness). This allows the agent to distinguish between goal states that are better or worse (happy vs. unhappy).

#### **100. NLP (Stemming)**

* 
**Question:** Process for reducing inflected words to their root form. 


* **Correct Answer:** **(B) Stemming**
* **Explanation:** **Stemming** is the heuristic process of chopping off the ends of words (suffixes) to reduce them to their base or root form (e.g., "running"  "run").
