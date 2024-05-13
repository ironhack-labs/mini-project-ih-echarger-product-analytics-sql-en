![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Mini Project | IronHack eCharger Product Analytics SQL

## Assignment

The purpose of this assignment is to assess your SQL knowledge. It is not focused on getting to the highest technical level, but to see if you know the main techniques and have minimum experience. The test is designed to be solved in SQLite, but if you do not know the specific syntax of some functions, do not worry. The main goal of these tests is to understand how you think and how you write queries from a high-level overview. Feel free to use StackOverflow or any other source to find out the equivalent of a function in SQLite. If you do not find it right away, just type the query in your preferred SQL language or even follow a no-code structure trying to show your thinking process.

### Files

- **sql_test.db**

Database with the following tables and columns:

- **Users** (id, name, surname)
- **Chargers** (id, label, type)
- **Sessions** (id, user_id, charger_id, start_time, end_time)

To open this file, we recommend using SQLite Studio, a SQLite Client that will help you explore the database and write queries on the fly. You can download it from [here](https://sqlitestudio.pl/).

![ai-eng/ironhack_echargers-1](https://education-team-2020.s3.eu-west-1.amazonaws.com/ai-eng/ironhack_echargers-1.png)

- **SQL_assignment_questions_sqlite.sql**

In this script, you have 14 SQL questions to retrieve some specific data from the `sql_test.sqlite` database.

### Assessment and Deliverables

Please fill the file `SQL_assignment_questions_sqlite.sql` with your answers and rename it to `SQL_assignment_my_solution_MYNAME_YYYYDDMM_HHMM.sql`. For example, if you fill your file on 2022-10-01 at 18:02, give the file the name `SQL_assignment_my_solution_20221001_1802.sql`. Upload the file to the same Drive folder you downloaded the files from or send it back to the email address you received all the files from.

We appreciate you taking the time to do this test and we would like to ask you to avoid spending more than 90 minutes on writing your solutions. Again, do not worry about leaving some questions blank or incomplete. We just want an overview of your knowledge and do not need the whole test to be completed. We will focus on your solution from a high-level perspective, inferring your line of thought and how you tackle problems. Feel free to add any external files or comments you would like to support your submission.

There are 5 levels of questions according to their complexity. Please make sure you have at least answered or explained the thinking process of one question from each level.

### SQLite Studio Guidelines

SQLite Studio does not require any installation. You can uncompress the folder ‘SQLiteStudio’ and click on the SQLiteStudio file that will open the client (same in Mac, Windows, or Ubuntu). Once opened, create a connection to a New DB and select the file `sql_test.db` attached to this test. You can check the database and tables on the left and write and execute queries on the right. Copy and paste the content of `SQL_assignment_questions_sqlite.sql` on a new SQL Script and you will be ready to start writing and testing your queries.

![ai-eng/ironhack_echargers-2](https://education-team-2020.s3.eu-west-1.amazonaws.com/ai-eng/ironhack_echargers-2.png)

You can download SQLite Studio from [here](https://sqlitestudio.pl/).