# Expense-Tracker
 
Android mobile application using Android Studio and java that allows  the users to keep track of their income and outcome simply by entering their initial balance

<h2> Introduction:</h2>
<h3>Inflow and Outflow record of our daily and monthly expended money can be easily kept
with the help of expense tracker ,It helps to manage our finances. 
this application is an android mobile application to track the expenses/incomes of the user. 
After filling his initial balance, a user will be able to view and to track his incomes and 
outcomes. The type, category, amount, and date of one operation will be automatically 
extracted from the bank SMS received by the user’s phone. Then, these details of 
expenses (incomes/outcomes) will be summarized and illustrated using pie/bar 
charts on period/category basis. </h3>

<img src="https://user-images.githubusercontent.com/114349246/232674630-ac972062-82df-4a86-849a-d0ac0be40fa4.png" alt="Alt text" title="App">




<h2> The first activity:</h2>
<p>○ A text field that captures the user initial balance value.</p>
<p>○ A Submit button: when it is pressed, the system saves this information using shared prefs
, and opens the budget reporting criteria.
<p>○ A data validation mechanism where an error message should appear if 
the user enters an invalid value.</p>

<h2>The second activity:</h2>
<p>○ A text field that displays the current balance.</p>
○ All criteria to view the expenses variation: Type (income/ outcome), 
balance amount, category of income (salary/transfer) or outcome 
(purchases, transfers, investment, monthly redemption payments, 
insurance and taxes, entertainment, etc.), period (custom or day/month).</p>
<p>○ A data validation mechanism where an error message should appear if 
the user enters invalid choices.</p>
<p>○ A Generate button: when it is pressed, it connects with the local database 
to check the validity of the entered criteria. In case of success, it opens
the Statistics activity. In case of failure, the system should display an error
message to the user.</p>

<h2>The third activity (Statistics): </h2>
<p>○ It includes Information about the expenses in form of charts. 
Examples of plots : balance amount by period, outcome/income.</p>
