# Lab3
Server which accepts client connections and serves client,
First We run Server and then client and client will take username and notes and
then send to server and then it displays entered data at server side.
# Approach
Approach I used is this 
I created 3 classes
 1. Notes
 2. Lab3
 3. desearlization
Notes is the base class and will contain the names of user and there respective notes.\
Then Lab3 which is client class and desearlization is server class, they both have imports of
Notes so that notes object can be used in both classes.
Username are the string arrays having ability of storing multiple users 
Notes can store multiple strings and i used a logic i.e.
Username and there notes index is same.
For say if user[0] is rehan
then his notes will be at notes[0].
And if rehan updates its notes then i append his notes at index 0.
