Throughout my time at Southern New Hampshire University, I have been able to hone my skills as a developer in many different ways. I have utilized multiple programming languages like Java, Python, and C++. I have utilized my collaboration skills when solving tough problems with both classmates and professors. I gained experience in communicating with stakeholders in a non-technical way and generated reports to show the impact of software and data. I have tackled data structures and algorithms in class and spent many hours on Leetcode, honing my skills. I was able to learn about both SQL and NoSQL databases and how to connect them with my own software solutions. I uncovered the mysteries behind software security and how I can develop code to keep sensitive information safe. I was also able to utilize large libraries such as OpenGL to create 3D environments. I have also learned about web development and how to utilize the MEAN stack to create and update web applications. The culmination of this knowledge has prepared me to start my career as a software developer.

This portfolio represents some of the most important knowledge I obtained at Southern New Hampshire University. Throughout this portfolio, I will be modifying a personal project to meet standards and desired outcomes. All enhancements are based on a tee-time reservation system that runs in the terminal. In my first enhancement, I will be migrating this project from Java to Python. In my second enhancement, I will take the newly written Python code, and add an algorithm that allows the user to search for members in the database. In the final enchantment, I will be integrating a MongoDB database so the program will be far more usable and functional. The course outcomes for this portfolio are as follows:

1.	Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science.  
2.	Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.  
3.	Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices.  
4.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
5.	Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.  


Below is a video of my code review of this project and how I will be improving upon it. 

**[CODE REVIEW](https://youtu.be/-gkOnbEaWbU)**

**ENHANCEMENT ONE**
 
The artifact that I chose for this enhancement is a tee time reservation system. It was created as a personal project to improve my Java skills about one year ago. I wanted to include this artifact in my portfolio because it was something that I built on my own. This not only shows my motivation to build software but also shows an understanding of Java. The artifact was improved by moving it from Java to Python. I know of many companies that are moving from one language to another, so this was a great way to showcase my ability to do just that. The course outcomes that I met for this artifact are below.

**Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.**

I believe that I have effectively met this course outcome. I have vastly improved the readability and comments in my code. This along with my recorded code review have showcased my skills in communicating and delivering professional quality communication to potential developers who would be looking at this code.

**Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science.**

I believe this artifact also meets this course outcome. By creating code that is readable and maintainable, I have opened the door for other developers to collaborate with me. I also believe writing clean code that is orthogonal will really help decision makers in the field of computer science as when one part of the program needs to be changed, it can be done easily and effectively. 
I learned a lot while developing this application. The differences in Python and Java are immense and it was far more challenging than I originally expected. I ran into issues with objects not working how I wanted them to in the menus, but I was able to overcome my struggles and get my program running exactly how it should work. 

I have included images of my program running in both Python and Java below. The link to the branch of this repository is [HERE](https://github.com/mvelezz/CS499/tree/branch1)

**JAVA**

![image](https://github.com/mvelezz/TeeTimeReservation/assets/130081489/c4171d4c-8332-44f6-823c-1569e8ce448c)

**PYTHON**

![Screenshot 2024-11-28 110455](https://github.com/user-attachments/assets/73fbf1df-11ef-40b4-8797-14d793226cc3)
![Screenshot 2024-11-28 110521](https://github.com/user-attachments/assets/94f0dc54-b82b-4192-a506-6e3d2c9cd39b)

**ENHANCEMENT TWO**

The artifact is a continuation of my previous artifact. In artifact one, I was able to convert my tee time reservation system from Java into Python. The program maintained its ability to book tee times, add members, and view all members in the database. I selected this item as I wanted this ePortfolio to be one big overhaul of a project. I knew that a huge improvement to my artifact would be allowing users to search for specific members with their member number. This would ensure as the database got larger, the user did not have to print and search through all existing members. I was able to create an algorithm to store member numbers in an array, sort the array, and then perform binary search on that array based on the member number the user was searching for. This value was then used to locate the member with that member number and print out their information. This took more resources than I originally thought. Adding an extra data structure and adding each member to it made space complexity O(n) where n is the number of member numbers added to the system. The time complexity would be O(n logn) as we have to sort the list to use binary search.

I believe I met both course outcomes below.

**Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices.**

Creating an algorithm to find a member by their member number meets this course outcome. I evaluated the algorithm for both time and space complexity and concluded that this was a solid solution for my problem.

**Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.**

This artifact has shown my ability to assess a situation, implement an algorithmic solution, and deliver value through implementing a feature to improve the software as a whole.

I learned quite a lot from implementing this artifact. I had never had to use binary search on a list that contained objects. I am sure there is a way to directly implement a search algorithm that will take a property of an object in as a parameter. I did like the solution that I came up with by adding all member numbers to a separate list and then performing the search on that list. The only assumption is that both the original list with members and the member number list need to be in numerical order for this implementation to work. If I choose to port this to a desktop application, I will have to figure out a better solution. 

I have included an image of the program utilizing this feature below. A link to the branch of this repository can be found [HERE](https://github.com/mvelezz/CS499/tree/branch_2) 

![image](https://github.com/user-attachments/assets/ab6e0913-3b79-41f6-a8b9-196a5c29e5a2)

**ENHANCEMENT THREE**

This artifact is the final iteration of the previous two artifacts. This enhancement will take the application to a whole new level. I have added a MongoDB database and can now store users without having to create them each time the application is launched. It will now be much easier and more usable than ever before. You can still add users, but they will be added directly into the MongoDB database hosted on MongoDB Atlas. I had to change my search algorithm as well to use a query to access the database and return the desired user. This is also far more secure than the original text file that was built with the Java application.

There is one main course outcome that I met with this enhancement. It is as follows:

**Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.**

I believe migrating the entire database to a MongoDB database shows a significant improvement to the design of this code. There is only one person with access to this database now, which is great. There is also protection when connecting to the MongoDB database, requiring the username and password to be parsed in a specific way in order to gain access. 

I learned a lot of valuable skills while doing this enhancement. Figuring out where to host the database and how to host the database was a daunting task. However, I was able to overcome many challenges along the way. I could not connect to the database at first, but I learned the username and password variables needed to be put through a specific function to connect to the database. I also had to completely rework how tee times were booked and how users could add new members to the database. This was far more challenging than I anticipated, but I am incredibly satisfied with the result. 

I have included an image of the program utilizing the database and a link to the branch of this repository can be found [HERE](https://github.com/mvelezz/CS499/tree/main/FINAL)

![Screenshot 2024-12-10 080712](https://github.com/user-attachments/assets/8d511db6-505b-42e8-ab5c-0f47041300d0)
