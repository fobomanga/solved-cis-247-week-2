Download Link: https://assignmentchef.com/product/solved-cis-247-week-2
<br>
We begin our investigation of object-oriented programming by creating an object-oriented program with a class called Employee. You will create two objects based on the Employee class, along with a class that contains the main method. The attributes, constructors, and methods for this class must satisfy the requirements in Steps 1 through 3. After you create the objects, you will prompt the user for information and then display it.




STEP 1: Understand the UML Class Diagram

Use the following UML diagram to build the class. The first section specifies the attributes. The second section specifies the behaviors, and the first character specifies the access modifier value, where:

<ul>

 <li>“-” means that the class member is private, and</li>

 <li>“+” means that the class member is public.</li>

</ul>










STEP 2: Code the Employee Class

<ol>

 <li>Create a new project called “CIS247B_Week2Lab_YourName”.</li>

 <li>Using the provided Class Diagram from Step 1, code the Employee class in the new project (i.e., “Realize the UML Class diagrams”).</li>

 <li>The default constructor should set the attributes as follows: firstName = “not given”, lastName = “not given”, gender = “U” (for unknown), dependents = 0, and annualSalary = 20,000.</li>

 <li>The multi-arg constructor should initialize all of the attributes using values passed in using its parameter list.</li>

 <li>As shown in the Class diagram, each attribute should have a “getter” to retrieve the stored attribute value, and a “setter” that modifies the value.</li>

 <li>The calculatePay( ) method of the Employee class should return the value of annual salary divided by 52 (return annualSalary / 52;).</li>

 <li>The displayEmployee() method should display all the attributes of the Employee object in a well-formatted string with logical labels applied to each attribute. Don’t forget to call calculatePay from within the displayEmployee method in order to display the Employee’s weekly pay as well!</li>

</ol>

STEP 3: Code the Main Program

In the Main class, create code statements that perform the following operations. Be sure you follow proper commenting and programming styles (header, indentation, line spacing, etc.).

<ol>

 <li>Create an Employee object using the default constructor.</li>

 <li>Prompt for and then set the first name, last name, gender, dependents, and annual salary. <strong>(Remember that you have to convert gender, dependents, and annual salary from strings to the appropriate data type.)</strong></li>

 <li>Using your code from last week, display a divider that contains the string “Employee Information”</li>

 <li>Format the currency using the following formatting services:</li>

 <li>Display the Employee information.</li>

 <li>Create a second Employee object using the multi-argument constructor, setting each of the attributes with appropriate valid values.</li>

 <li>Using your code from last week, display a divider that contains the string “Employee Information”.</li>

 <li>Display the Employee information for the second Employee object.</li>

</ol>













Sample Screenshot