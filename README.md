# Bad Passwords and the NIST Guidelines
## Description
In June 2017 the National Institute of Standards and Technology (NIST) published [publication 800-63B](https://pages.nist.gov/800-63-3/sp800-63b.html) titled Digital Identity Guidelines: Authentication and Lifecycle Management. This publication doesn't tell you what is a good password, but it does have specific rules for what is a bad password.

In this project, we will take a list of user passwords and, using publication 800-63B, we will write code that automatically detects and flags the bad passwords.
## Contents
1. **The NIST Special Publication 800-63B:** Load in and inspect the usernames and passwords of the fictional users.
2. **Passwords should not be too short:** Flag the passwords that are too short.
3. **Common passwords people use:** Load in the list with the 10,000 most common passwords.
4. **Passwords should not be common passwords:** Flag the `user` passwords that are among the top 10,000 used passwords.
5. **Passwords should not be common words:** Flag the passwords that are among the 10,000 most common English words.
6. **Passwords should not be your name:** Flag passwords that are the same as the users first or last name.
7. **Passwords should not be repetitive:**
8. **All together now!:**
9. **Otherwise, the password should be up to the user:**