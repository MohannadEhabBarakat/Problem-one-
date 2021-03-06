# Card reader

## Problem description 
Consider you have an embedded application to be deployed on a set of card readers for a classroom seats management and attendance system. An institute deploys this application on a set of precisely 8 classrooms, with each classroom having precisely 256 available seats. Seats are pre-assigned to students, whereby  the same seat will be occupied by the same student in all classrooms; i.e. no two students can have the same seat number ever. The seat number of the student will be hardwired on his card. Each student will stamp upon entering and upon leaving a specific class. A student cannot exist in two classes at any point in time. The whole idea is to be able to know how many students are there in any particular class, inquire about a specific student location in any class at any point of time, and to be able also to inquire on the availability of a specific student at any point in time. The maximum number of students that can go to any class is 256, and students are numbered from 0 to 255.  
Implement the needed C++ classes that model this problem.  Your code will be used in an embedded application (card reader) where storage constraints applies, and thus they should be optimum from the storage point of view, while being as efficient as possible during execution. Also you cannot assume the existence of the STL or STD in the target embedded deployment environment.  
Your class should provide all the needed constructors and destructor, in addition to implementing the following methods: 1. Allow class users to reserve and avail classroom seats. 2. Implement a method that checks if a specific seat is occupied in any particular class. 3. Implement a method that returns the number of available seats in a specific class at any point in time. 4. Inquire about the location of the student.  
Apply all validations that you see viable, and again, your class should be self contained and should not use the C++ STL or STD libraries, but should be based on built-in C++ types.  
Note: you can consider that all the eight card readers are synchronized 

## To compute & excute 
please run the commaned in file "run.txt" in the shiel. 

*note: this works only on linux*
