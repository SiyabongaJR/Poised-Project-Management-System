# Capstone-Project-4

**Poised Project management System**

**Project Details**

This was the forth **Capstone** project from my **HyperionDev Software Engineering Bootcamp**. It was to fullfil the first **Capstone project** on the second level of the Bootcamp.
The project was to use Java OOP to design a project management system for a small Structural engineering firm. The program is used to help keep track of all the companie's projects and edit details about them if need be.

**Functionality**

The UML diagram in the files in this repo shows an overview of the complete program functionality. There are two classes that are used to create the details of the project (ProjectDetails class) and the details for the people working on the project (PersonDetails class). Then there is the implementation class (PoisedProject class) which has a menu to be presented to the user. The menu presents the user with 4 main options, 


As the user first uses the system, The PoisedProject class is called in the main then they are asked to input the all the project details for the project they want. After they do so, they are presented with the details of the project they just created.
Then they are presented with the menu with the following options

* The first option: Change the due date of the project
* The second option: Change the total amount paid to date
* The third option: update the details of the contractor
* The fourth option: finalize the project
* The fifth option:  exit

**Depending on the menu option the user selects, different classes and methods get called**

* If the first option is chosen, the user will edit the due date then that will be updated on the ProjectDetails class, then the user will be presented with their changes by calling the ProjectDetailsDisplay() method in the ProjectDetails class.

* If the user chooses the second option, which is to change the total amount paid, that detail gets updated in the ProjectDetails class, then the user will be presented with their changes.

* If the third option is chosen, The user is presented with input options to edit the contact details and physical address of the contractor, then the details are updated on the ProjectMember class, then the user is presented with details, by calling the personDetailsDisplay() method in the ProjectMember class.

* If the fourth option is chosen, the project is finalized If the client has paid all their fees, but an invoice is generated if the client still has money owed to the firm. The invoice will show all the client details and contact info on it.

**Usefulness of the project**

Given that this was the first phase of a continuous project. The UML in the repo files Shows the end goal of the project. But as it is, it does cover basic project management tasks for the structural engineering firm.

**How Can I use it**

* To use the code, clone this repo.  You need to have a Java DEvelopment kit, download it at the following link: https://www.educba.com/install-jdk/

* And have a Java IDE, download at the following link : https://www.eclipse.org/downloads/packages/installer


**Contributors**

I am the sole contributor and I maintain the code.

