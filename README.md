Download Link: https://assignmentchef.com/product/solved-cse240-homework9-create-nontechnical-and-technical-child-classes-of-employee-class
<br>
You are given a partially completed project containing:

<ul>

 <li><u>header files:</u>h employee.h nontechnical.h technical.h</li>

 <li><u>C++ files:</u></li>

</ul>

Container.cpp employee.cpp nontechnical.cpp technical.cpp hw9.cpp

The diagram shows the inheritance and relationships between the classes and the linked list formed.

Employee class is defined in employee.h and member functions are defined in employee.cpp.

<strong>Q1: Create Nontechnical and Technical child classes of Employee class (Inheritance) (10 points) </strong>

Files: nontechnical.h , technical.h

<strong>Q2: Define displayEmployee() for child classes (Polymorphism) (10 points) </strong>

Files: nontechnical.cpp , technical.cpp

<h1>Q3: Add Friend function changeSalary() (5 points)</h1>

Q3.a in employee.h

Q3.b in hw9.cpp

Q3.c in hw9.cpp. Case ‘c’ of executeAction( )

<strong>Q4 – Q7</strong> are used to implement a menu-driven program. Its implementation is in hw9.cpp. The menu gives the following options to user:

<ol>

 <li>Add a new employee to the list. You do not need to check if the employee exists in the list because that is already implemented in executeAction(). You may add the new employee to head or tail of the list. (sample solution adds it to the tail)</li>

 <li>Display the list of employees along with their details (name, salary, type).</li>

 <li>Change the salary of an employee. This option uses the friend function to access private data member ‘salary’ of the employee and change it to the one entered by the user.</li>

</ol>

You need to implement save() that writes the list of books to a file ‘list.txt’ while exiting the program and load() that reads the file to form the list at the beginning of the program. During first execution of the program, there will be no ‘list.txt’, so load() would not form a list. Once list.txt is saved, load() can read it the next time you run the program. You may remove the list.txt from your project directory if you do not want to load that list (maybe while testing your code).

The following is one way to store the list in list.txt file. The format here is:

&lt;no. of employees&gt;

&lt;Employee1 name&gt;

&lt;Employee1 salary &gt;

&lt;Employee1 type&gt;

&lt;Employee2 name&gt;

&lt;Employee2 salary &gt; &lt;Employee2 type&gt; and so on..

You may store it in another format if you wish. Notice that the ‘3’ at the beginning is the number of employees stored in the file.

<strong>Expected output: <u>addEmployee():</u> </strong>

<strong><u>displayList():</u> </strong>

<strong><u>changeSalary():</u> </strong>

Verify by using option d.