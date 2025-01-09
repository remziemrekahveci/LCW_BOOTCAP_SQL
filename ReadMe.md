# Employee Database SQL Scripts

This repository contains SQL scripts for creating and managing an `employee` table in a database. The table includes details such as employee ID, name, birthday, and email.

## Table Structure

The `employee` table is created using the following SQL script:

```sql
CREATE TABLE employee (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name VARCHAR(50),
    birthday DATE,
    email VARCHAR(100)
);


## Insert Statements

Below are 50 `INSERT` statements used to add data to the `employee` table.

``sql
INSERT INTO employee (name, birthday, email) VALUES ('Jane Smith', '1990-07-20', 'jane.smith@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('John Doe', '1985-05-15', 'john.doe@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Emily Johnson', '1993-11-22', 'emily.johnson@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Michael Brown', '1988-03-30', 'michael.brown@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Sarah Davis', '1995-08-14', 'sarah.davis@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('David Wilson', '1982-12-19', 'david.wilson@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Laura Martinez', '1991-01-25', 'laura.martinez@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('James Taylor', '1987-06-17', 'james.taylor@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Sophia Anderson', '1994-09-10', 'sophia.anderson@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Chris Thomas', '1980-04-05', 'chris.thomas@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Emma Harris', '1996-07-23', 'emma.harris@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Daniel Moore', '1992-10-28', 'daniel.moore@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Olivia Clark', '1989-03-07', 'olivia.clark@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Matthew Lewis', '1984-11-13', 'matthew.lewis@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Isabella Walker', '1997-02-19', 'isabella.walker@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Andrew Hall', '1983-06-03', 'andrew.hall@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Mia Young', '1990-09-25', 'mia.young@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Joshua Allen', '1986-12-08', 'joshua.allen@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Ava King', '1998-05-12', 'ava.king@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Ethan Wright', '1981-07-30', 'ethan.wright@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Sophia Scott', '1993-03-18', 'sophia.scott@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Logan Green', '1989-08-29', 'logan.green@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Madison Baker', '1992-11-04', 'madison.baker@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Benjamin Adams', '1985-02-15', 'benjamin.adams@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Ella Gonzalez', '1996-01-09', 'ella.gonzalez@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Alexander Nelson', '1984-06-21', 'alexander.nelson@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Chloe Carter', '1994-12-02', 'chloe.carter@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Mason Mitchell', '1982-10-13', 'mason.mitchell@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Zoe Perez', '1997-03-26', 'zoe.perez@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Lucas Roberts', '1983-05-19', 'lucas.roberts@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Grace Turner', '1995-08-31', 'grace.turner@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Liam Phillips', '1986-11-07', 'liam.phillips@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Charlotte Campbell', '1991-02-28', 'charlotte.campbell@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Noah Parker', '1987-07-15', 'noah.parker@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Ella Evans', '1990-01-11', 'ella.evans@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Oliver Edwards', '1992-06-29', 'oliver.edwards@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Amelia Collins', '1998-09-08', 'amelia.collins@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('William Stewart', '1984-03-16', 'william.stewart@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Avery Sanchez', '1996-10-12', 'avery.sanchez@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('James Morris', '1981-12-25', 'james.morris@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Mia Rogers', '1995-04-03', 'mia.rogers@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Ethan Reed', '1989-08-22', 'ethan.reed@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Aria Cook', '1997-01-18', 'aria.cook@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Jackson Bell', '1985-11-29', 'jackson.bell@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Lily Bennett', '1994-07-06', 'lily.bennett@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Henry Rivera', '1988-02-23', 'henry.rivera@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Aubrey Foster', '1991-09-12', 'aubrey.foster@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Harper Morgan', '1993-05-04', 'harper.morgan@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Sebastian Hayes', '1987-10-18', 'sebastian.hayes@example.com');
INSERT INTO employee (name, birthday, email) VALUES ('Layla James', '1999-03-27', 'layla.james@example.com');


## Update Statements
'''sql
UPDATE employee
SET email = 'updated_email@example.com'
WHERE name = 'John Doe';

UPDATE employee
SET name = 'Updated Name'
WHERE birthday = '1990-07-20';

UPDATE employee
SET birthday = '2000-01-01'
WHERE email = 'jane.smith@example.com';

UPDATE employee
SET name = 'Name Updated By ID'
WHERE id = 1;

UPDATE employee
SET email = 'multi_update@example.com', birthday = '1999-12-31'
WHERE name = 'Jane Smith' AND id = 2;

## Delete Statements
''sql
DELETE FROM employee
WHERE name = 'John Doe';

DELETE FROM employee
WHERE birthday = '1990-07-20';

DELETE FROM employee
WHERE email = 'jane.smith@example.com';

DELETE FROM employee
WHERE id = 3;

DELETE FROM employee
WHERE name = 'Jane Smith' AND birthday = '2000-01-01';
