#Banck Management 

##Features

Open Account: Allows users to create a new account by entering an account number and password. The balance is initialized to zero.

Add Cash: Enables users to deposit cash by entering their account number. The balance is updated accordingly.

Withdraw Cash: Authenticates the user with account number and password before allowing withdrawals. It checks for sufficient balance before processing the transaction.

File Handling: Uses ifstream and ofstream for reading/writing account data securely via a temporary file system.

Basic Security: Password authentication is implemented for withdrawal operations.

System Pause & Clear: Utilizes Sleep() and system("cls") for user-friendly interface transitions.
