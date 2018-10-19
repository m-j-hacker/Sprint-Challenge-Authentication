<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?

Sessions are used as a way to persist data across requests, such as authentication information.

2. What does bcrypt do to help us store passwords in a secure manner.

bcrypt hashes passwords for us using automatic salting and accumulative hashing rounds

3. What does bcrypt do to slow down attackers?

In order to solve the password hash, an attacker would have to have to have the hash, know the algorithm used, and how many rounds were used.

4. What are the three parts of the JSON Web Token?

Header, payload, and signature
