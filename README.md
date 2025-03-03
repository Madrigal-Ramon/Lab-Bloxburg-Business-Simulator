# Lab-Bloxburg-Business-Simulator

How this code is used ---
  To start out this code is structured by two main classes Business and BloxburgGame. The business class hold the attributes like name, owner, employees and funds. It also       contains the methods for pay taxes, employee hire, and pay salaries. Finally, for the business class it has the static fields, which are the totalBusinesses and TAX_RATE. Then the BloxburgGame class contains the main method, which has the user interaction with the program.

  Next, when a user runs the program they are greeted with the option to start a new business or exit out of the program. For example, if the user chooses to implement their business information. They will first have to input the Business name, owner, fund, number of employees, employee name(s), role, and finally employee salary. After, you finish inputting business information the program with display all of the information, With how many business were created. Finally, the user could choose whether to continue creating businesses or exit the program, Which will end the program.  
  

Where the Overloading method was implemented ---
  The Overloading was implemented in the business class. Which is used to overload the constructors of the class. 

How Static fields are used ---
  The static fields are used with the elements totalBusiness, TAX_RATES, getTotalBusinesses. The totalBusiness holds the total amount of business that were created before the user chose to exit the program. TAX_RATES which is used to provide a shared constant value that is the same for every business. And finally, getTotalBusinesses provides access to the total amount of business.
