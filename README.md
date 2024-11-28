**BANKING OPERATIONS - Functional Analysis**


1. **User Login and Authentication**
Objective:
Ensure that users can log in securely using their phone number and OTP.
Features:
Login:
Users log in using their registered phone number.
System sends an OTP to the provided phone number.
User enters the received OTP for authentication.
OTP Expiry & Retry Mechanism:
Multiple failed attempts lock the account temporarily for 48 hrs.

3. **Banking Operations**
   
A. Balance Check
Objective: Users should be able to check the balance of their account.
Steps:
After login, the user selects the "Balance Check" option.
The system fetches the current balance and displays it.

B. Fund Transfer (Send Amount to Another User)
Objective: Allow users to send money to another user using their phone number.
Steps:
User selects the "Transfer Funds" option.
The system asks for the recipient's phone number and amount to be transferred.
User enters the UPI PIN for authorization.
The system verifies the balance, and if sufficient, processes the transaction.

Transaction Failed
Insufficient balance (check balance)
Server down (server is down try again some time)
OTP wrong (wrong otp entered, check otp properly)

Available  balance
Display available balance if transaction is successful

C. Mini Statement (Last 5 Transactions)
Objective: Users can view the last 5 transactions in their account.
Steps:
User selects the "Mini Statement" option.
The system retrieves and displays the last 5 transactions, including amounts and dates.

D. Set or Change UPI Pin
Objective: Users can set or change their UPI PIN for secure transactions.
Steps:
User selects the "Set/Change UPI PIN" option.
User enters a new PIN and confirms it.
The system validates the PIN (e.g., checks if the PIN is 4 digits and doesn’t match any previous PIN).
The new PIN is saved and used for future transactions.

E. User Profile Updates (Change Email, Phone)
Objective: Users can update their email, phone number
Steps:
User selects the "Update Profile" option.

User can choose to update:
Email: User inputs new email. A verification email is sent for validation.
Phone Number: User inputs new phone number. An OTP is sent to the new phone number.
