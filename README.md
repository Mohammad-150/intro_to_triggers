# intro_to_triggers
In this example, we created a trigger that automatically updates a "last_updated" timestamp column whenever a row in the "employees" table is updated.
First, we create a table named "employees" with columns for id, first_name, last_name, and last_updated. Then, we create a trigger function named "update_last_updated" using PL/pgSQL, which sets the "last_updated" timestamp to the current time whenever a row is updated. Finally, we create a trigger named "update_employee_last_updated" that fires before an update operation on the "employees" table and executes the "update_last_updated" function.
Now, whenever you perform an update on a row in the "employees" table, the "last_updated" column will be automatically updated with the current timestamp.
