# PL-SQL_TRIGGER

#### Question 1: (use schemas des02 with script 7clearwater)
We need to know WHO, and WHEN the table CUSTOMER is modified.
<br>Create table, sequence, and trigger to record the needed information.
<br>Test your trigger!
#### Question 2:
Table ORDER_LINE is subject to INSERT, UPDATE, and DELETE, create a trigger to record who, when, and the action performed on the table order_line in a table called order_line_audit.
<br>(hint: use UPDATING, INSERTING, DELETING to verify for action performed. 
<br>For example: IF UPDATING THEN …)
<br>Test your trigger!
#### Question 3: (use script 7clearwater)
Create a table called order_line_row_audit to record who, when, and the OLD value of ol_quantity every time the data of table ORDER_LINE is updated.
<br>Test your trigger!
