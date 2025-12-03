<!-- What is a class in object-oriented programming? -->
A class is a blueprint for creating objects (instances). It defines properties (attributes) and behaviors (methods) that the objects created from the class will have.
<!-- What is an object, and how is it related to a class? -->
An object is an instance of a class. It represents a real-world entity with specific attributes and behaviors defined by its class.
<!-- What is the difference between a method and an attribute? -->
A method is a function defined inside a class that defines the behavior of an object. An attribute is a variable that holds data related to the object (state).
<!-- Explain what encapsulation means in OOP. -->
Encapsulation is the concept of bundling the data (attributes) and methods (functions) that operate on the data into a single unit called a class. It helps in hiding the internal details of the object and exposes only necessary parts.
<!-- What is information hiding, and why is it useful? -->
Information hiding is the practice of restricting access to the internal state of an object. This helps in maintaining control over how data is accessed and modified, ensuring that objects are used correctly and preventing misuse.
<!-- What keyword is used in Python to define a class? -->
The keyword class is used to define a class in Python.
<!-- What is the purpose of the __init__ method in Python classes? -->
The __init__ method is the constructor in Python. It is called when an object is instantiated from a class and is used to initialize the object's attributes.
<!-- What is inheritance and why is it useful? -->
Inheritance is the mechanism in OOP where a new class (child class) can inherit the attributes and methods of an existing class (parent class). It promotes code reusability and makes it easier to maintain and extend.
<!-- What is the "base class" (or parent class) in inheritance? -->
The base class (or parent class) is the class that provides the common attributes and methods that can be inherited by other classes.
<!-- What is the "derived class" (or child class) in inheritance? -->
The derived class (or child class) is a class that inherits from another class (parent class) and can extend or modify the behavior and attributes of the parent class.
<!-- Give one advantage of using OOP instead of procedural programming. -->
One advantage is that OOP promotes modularity, reusability, and easier maintenance by organizing code into classes and objects. This allows for more structured and scalable programs.
<!-- What does it mean when we say an object has "state"? -->
An object's "state" refers to the values of its attributes at a given point in time, which define its condition or status.
<!-- What is method overriding? -->
Method overriding occurs when a subclass provides its own implementation of a method that is already defined in its parent class. This allows the subclass to modify or extend the behavior of the inherited method.
<!-- What is the difference between a public attribute and a private attribute? -->
A public attribute can be accessed from outside the class, while a private attribute is meant to be accessed only within the class and is usually denoted with a leading underscore (_).
<!-- Write a Python statement that creates an object of a class named Car. -->
car_instance = Car()



<!-- What is version control and why is it important? -->
Version control is a system that helps manage changes to code or documents over time. It allows developers to track and revert to previous versions of their files, collaborate with others, and avoid losing important changes.
<!-- What is the difference between Git and GitHub? -->
Git is a distributed version control system used for tracking changes in source code. GitHub is a platform that hosts Git repositories and provides features like collaboration, issue tracking, and more.
<!-- Describe the role of the working directory in Git. -->
The working directory is where the files are located in your project. It holds the actual files that you are editing and working on, and these files can be tracked by Git to determine changes.
<!-- Describe the staging area (index) in Git. -->
The staging area (also called the index) is where changes are placed before being committed to the repository. It allows you to review and prepare changes before finalizing them with a commit.
<!-- What does the local repository store? -->
The local repository stores all the commits, branches, and the version history of a project. It is stored on your local machine and is where changes are tracked.
<!-- What does the remote repository store? -->
The remote repository stores the shared version of the project, usually on a server or cloud-based service like GitHub, GitLab, or Bitbucket. It serves as a central hub for collaborating with others.
<!-- What Git command shows the status of your working directory and staging area? -->
git status shows the current status of your working directory and staging area, including untracked, modified, and staged files.
<!-- What Git command moves changes from the working directory to the staging area? -->
git add <file> moves changes from the working directory to the staging area.
<!-- What Git command creates a new commit? -->
git commit -m "message" creates a new commit with the changes in the staging area, using the provided commit message.
<!-- What Git command uploads commits to a remote repository? -->
git push uploads commits from your local repository to a remote repository.
<!-- What Git command shows commits in various branches? -->
git log --all --graph --oneline displays commits from all branches in a graphical format.
<!-- What is a branch in Git? -->
A branch in Git is a separate line of development, allowing you to work on different features or bug fixes without affecting the main codebase.
<!-- Why do developers create branches? -->
Developers create branches to work on new features, fix bugs, or experiment without affecting the main (production) codebase. It helps isolate changes and makes collaboration easier.
<!-- What is a merge conflict? -->
A merge conflict occurs when Git is unable to automatically merge changes from two branches because both branches have changes to the same part of the code.
<!-- When a merge conflict happens, what must the developer do to resolve it? -->
The developer must manually resolve the conflict by editing the conflicting files, deciding which changes to keep, and then committing the resolved files.