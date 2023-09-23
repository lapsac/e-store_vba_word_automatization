# e-store_vba_word_automatization
The code for Task 1 creates user names and passwords for clients based on the given conditions:

    Usernames are the first 4 characters of the last name (Column I).
    Passwords start with the uppercase letter "P" followed by their postal code (Column J).

The code for Task 2 creates a CSV file named "users.csv" with client information in the format: username;password. It does this every time the program is run.

The code for Task 3 calculates the age of each client in Column K using the YEARFRAC function and applies discounts based on the following conditions:

    Clients receive a 10% discount for their entire birth month.
    Clients can also receive a 25% discount for milestone birthdays (20, 30, 40, or 50 years old).

Clients eligible for the 25% discount are highlighted in red, while those eligible for the 10% discount are highlighted in green.

The code for Task 4 prepares a personalized email list for the IT department, including the following client information:

    Full name (formatted as first name, space, last name)
    First name
    Email address
    Client's age
    Client's birthday
    Client's birth month

This list is intended for sending personalized emails to offer the discounts mentioned in Task 3.
