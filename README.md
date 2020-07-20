# email-datatype-PostgreSQL
 creating a user-defined email datatype in PostgreSQL using C programming.
 
## Goal
We wish to define a new base type EmailAddr to represent RFC822-style email addresses (actually a subset of RFC822). We also aim to define a useful set of operations on values of type EmailAddr and wish to be able to create indexes on EmailAddr attributes. 

## Operations performed on the user-defined Datatype
1. Email1 = Email2 ... two email addresses are equivalent
2. Email1 > Email2 ... the first email address is greater than the second
3. Email1 ~ Email2 ... Email addresses have the same Domain 
4. Other operations: <>, >=, <, <=, !~


