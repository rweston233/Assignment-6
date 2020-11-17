# Assignment-6

## Assignment 6 Learning Objectives
> Related Project and Lab Recap:
> - Create two SQL views, and one stored procedure, using the Assignment 5 files for Assignment 6. Also update the NodeJS code to execute one of the views, and use the stored procedures. The specifics are as follows:

### Part I
> SQL Views

- Create two SQL views that work with the Assignment 5 alumni database. *Both views must start with the `vw_` prefix*.

  1. View #1: Create a simple view that returns data from one of the tables. Export the SQL to create this view to a file called `cit381-assign06-view1.sql`.

  2. View #2: Create a view that returns data from two tables using a JOIN statement. Export the SQL to create this view to a file called `cit381-assign06-view2.sql`.

- Add a new GET route to the NodeJS code to use the second view (the view with the JOIN statement). Remember to ensure the new route is not the same as any other GET route.

### Part II
> Stored procedures

- Create a stored procedure that deletes a row from one of the tables. The stored procedure must take an appropriate primary key parameter to determine which row to delete. The stored procedure name must start with the `sp_` prefix.
  - Export the SQL to create this stored procedure to a file called  `cit381-assign06-sp.sql`.

- Add a new DELETE route to the NodeJS code to use the stored procedure to delete a row. Adjust the SQL to call the stored procedure, and supply the primary key as an argument to the stored procedure. Ensure the new route is not the same as any other DELETE route.

**Deliverables**
[assign06.zip]()


>> Back to home page:
[Home](https://rweston233.github.io/)
