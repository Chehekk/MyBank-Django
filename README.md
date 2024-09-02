Here's a summary of the project:

Project: Customer Experience with Bank Accounts  
Technologies: Python, Django, Eclipse IDE, Tomcat 9 Server, MySQL Server, MySQL Workbench

Admin Roles:
- Admins have their details stored in the database.
- They can log in with a username and password.
- Admins can register customers with details like full name, address, mobile number, email, account type (Saving/Current), initial balance (min 1000), date of birth, and ID proof.
- Upon registration, an account number and temporary password are generated for the customer.
- Admins can add, delete, modify, and view customer details, but cannot see passwords or balances.

Customer Roles:
- Registration is done by the admin. The account number and temporary password are provided to the customer.
- Customers can set up a new password and log in with their account number and new password.
- They can log out, view their dashboard (showing account details and balance), view the last 10 transactions, deposit or withdraw funds, and close their account (only if the balance is zero).
- The customer can download a PDF of their last 10 transactions.

Bonus Functionality:
- Customers can download a PDF of the last 10 transactions from the mini statement.

Instructions:
- Focus on completing end-to-end functionality; UI is secondary.
- After initial analysis, consult with mentors to clarify requirements.
- Prepare a Bill of Materials (BOM) listing software and hardware used.
- Design and implement well-modularized code and a normalized database schema.
- Ensure that only authenticated users can access the application.
