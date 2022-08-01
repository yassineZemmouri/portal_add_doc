# Admin

<img src="./assets/drop_down_list_admin.png">

### Portal:

- The admin can see the list of all users which contains their (last name, first name, email, Role, isActive, isDeleted, Actions).
plus the possibility of downloading the list by clicking on the Dowload CSV button.

<img src="./assets/portal_overview.png">

- Admin can click on a specific user's row for the option to Edit, Desactivate, delete, or reset his password

<img src="./assets/user_detail.png">

- Admin can add a new user by clicking on the Add User button in top-right

<img src="./assets/add_user.png">


### Permission:

<img src="./assets/role_table.png">

- The admin can see the list of roles already created.

- Admin can click on a specific role and add a list of permissions allowed for it (Ex: ONBOARDING role)

<img src="./assets/role_fonct_ex.png">

- The admin can modify the description or the list of permissions of each role by clicking on the Edit button in top-right.

<img src="./assets/edit_role.png">

### Asset Managers

<img src="./assets/asset_managers.png">

- The admin can view the list of PAM (personal asset manager) users or search for a PAM by name.

- The admin can see the list of clients (investors) assigned to a specific PAM user.
the liste contains (Full name, Email, Phone number, Client type, Risque grade, Verified).

- The admin can search for a Client by his Fulle Name or Email.

- The admin can assign other client to PAM by clicking on the Assign Clients button in top-right.

<img src="./assets/clients_list.png">

### Email Templates

<img src="./assets/email_template.png">

- The admin can view the list of Email templates already created or create a new one by clicking on the New Template button in top-right.

<img src="./assets/create_email_template.png">

# Client

<img src="./assets/drop_down_list_client.png">

### Onboarding

<img src="./assets/onboarding_overview.png">

- The admin can see the list of all registered clients  and in which ombording step they are, the list contains the following information (First name, Last, name, Created at, Gender, Email, City, Step, Status, Type , Email Verified, Passport, Proof of Address, Assessment, Wealth, KYC).

- The admin can download the list by clicking the Download CSV button.
- Admin can add a new user manually by clicking the Add Client button at the top of the page
  
<img src="./assets/profile_summary.png">

- The admin can see the profile summary of a specific client which contains the above information.

<img src="./assets/onboarding_steps.png">

- In the Client Onboarding section:
   1. Onboarding Steps
    * The admin can see the status of each onboarding step along with the option to edit the step if it is invalid by clicking the Change Onboarding Step button at right.
   
   2. Profile
    * Contains account information plus personal information of the client
   
   3. ID Verification
     * Compare the personal information extracted from the customer's passport with the information on the Omboarding.
     * Display the Passport image of the client
  
   4. Wealth
    <img src="./assets/wealth.png">

   5. Risk Assessment
     * The information required to analyze a client's investment risk. (Personal Score, Experience Score, wealth Score, Objectives Score, Total Score, Risk Level, Age, Number of dependents, Liquid Net, FinaMaze Portion, Investments Familiarity, Finance Experience, Net Annual Income, Crisis Loss, Net Wealth, TakeProfile / StopLoss).
   6. TAX/PEP
   
   7. Validatoin
       <img src="./assets/validation_client_onboardin.png">
 The admin can validate the necessary steps to verify the identity of the client.
   8. Client Files
   * contains client documents (ex: Proof Of Address, Proof of wealth, Social media).
  
- In the Client Dashboard section:
  1. Bank Account
   * liste of bank acount used by client
  
  2. Investments
   * Liste of client's investments contains(Inception date, Exit date, Account id, First name, Last name, Smartfolio, Layer, class, Risk Solution, Take Profit, Stop Loss, Residual, Inception[invested, Rebalanced], Live[NAV, Performance]).
   * The investments can be filtred by they status.
   * Admin can see more details (investment info, Holding tickers, Zag orders) about each investment by clicking on his line.
  
  3. Cash
   <img src="./assets/Cash_client_dashboard.png">
  
  4. Holdings
   <img src="./assets/holdings_client_dashboard.png">
    * List of all Tickers invested by the client with their respective quantity.
  
  5. Cash Transactions
  
  6. Statements

- In the Admin Actions section:
  1. Control Panel
   <img src="./assets/control_panel_admin_action.png">
   * Admin can block / Activate client
   * Add client to CRM (Customer relationship management)
   * Upload client files
   * Reset client password
   * Delet client
  
  2. Send Email
   Admin can choose a specific email template previously created in Admin/Email_Templates to send an email to client.
  
  3. Email History
    List of emails sent to the client.
  
  4. Onboarding History
    <img src="./assets/onboarding_steps_history.png">

### Active

 <img src="./assets/active_clients.png">
    display the liste of activated client.
    active client: the client who finish the onboarding process and validate the Compliance check list.

### Rejected/Deleted

<img src="./assets/deleted_client_list.png">
