# AggieSTEM Digital Library System

## Server starting guide

1. Install all packages
2. Change datatables js hrc
3. Change any PW information for emails
4. Change any PW information for amazon text messaging
5. Change IP of server.
6. Run the command: python3 run_server.py

## Previous work

Draft V1.1

- Create a data base that stores user data and profiles for quick and easy access through a user media interface. Allow users to create new mediafiles and insert into data base. Admin message system (similar to code maroon

![AggieSTEM_DL.png](https://i.loli.net/2020/02/22/XpHRZwrmGs1a23F.png)

| MVC | Representation | Function overview |
| :-- | :--- | :------- |
| Model | Pink diagrams | Create tables in MongoDB/MySQL to organize and query user profiles and data |
| Viewer | Blue diagrams | Front end environment for login, viewing, searching, and sharing data with other users. |
| Controller | Beige diagrams | Process the HTTP request from the viewers. |