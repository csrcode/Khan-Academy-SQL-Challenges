Challenge Book List Database
/** bmmbook list :
Deep Work (4)
Alchemist (4)
Atomic Habits (5)
Time zone (3)
**/

CREATE TABLE bmmbooks (id INTEGER PRIMARY KEY, name TEXT, rating INTEGER);

INSERT INTO bmmbooks VALUES (22, "Deep work", 4);
INSERT INTO bmmbooks VALUES (23, "Alchemist", 4);
INSERT INTO bmmbooks VALUES (24, "Atomic Habits", 5);
INSERT INTO bmmbooks VALUES (25, "Time zone", 3);
SELECT * FROM bmmbooks;
