# Khan-Academy-SQL-Creating-A-Table
Introduction to SQL (Khan Academy)
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
Challenge Box Office
CREATE TABLE movies (id INTEGER PRIMARY KEY, name TEXT, release_year INTEGER);
INSERT INTO movies VALUES (1, "Avatar", 2009);
INSERT INTO movies VALUES (2, "Titanic", 1997);
INSERT INTO movies VALUES (3, "Star Wars: Episode IV - A New Hope", 1977);
INSERT INTO movies VALUES (4, "Shrek 2", 2004);
INSERT INTO movies VALUES (5, "The Lion King", 1994);
INSERT INTO movies VALUES (6, "Disney's Up", 2009);

Select * FROM movies;

Select * FROM movies WHERE release_year >= 2000
ORDER BY release_year;

/** likethecafe list :
Project Design a store data base:

/** likethecafe list :
coffee (25)
Tea (20)
pan cake (35)
choco (40)
ice cream (15)
candy (10)
sandwitch (25)
burger (45)
taco (47)
cookies (5)
soft drink (80)
shakes (60)
muffins (65)
cup cakes (70)
ice candy (28)
**/

CREATE TABLE likethecafe (id INTEGER PRIMARY KEY, items TEXT, price INTEGER);
SELECT * FROM likethecafe;
SELECT * FROM likethecafe;
SELECT * FROM likethecafe;
SELECT * FROM likethecafe;
SELECT * FROM likethecafe;
SELECT * FROM likethecafe;
INSERT INTO likethecafe VALUES (1, "coffee", 25);
INSERT INTO likethecafe VALUES (2, "tea", 20);
INSERT INTO likethecafe VALUES (3, "pan cake",35);
INSERT INTO likethecafe VALUES (4, "choco", 40);
INSERT INTO likethecafe VALUES (5, "ice cream", 15);
INSERT INTO likethecafe VALUES (6, "candy", 10);
INSERT INTO likethecafe VALUES (7, "sand witch", 25);
INSERT INTO likethecafe VALUES (8, "burger", 45);
INSERT INTO likethecafe VALUES (9, "taco", 47);
INSERT INTO likethecafe VALUES (10, "cookies", 5);
INSERT INTO likethecafe VALUES (11, "soft drink", 80);
INSERT INTO likethecafe VALUES (12, "shakes", 60);
INSERT INTO likethecafe VALUES (13, "muffins", 65);
INSERT INTO likethecafe VALUES (14, "cup cakes", 70);
INSERT INTO likethecafe VALUES (15, "ice candy", 28);
SELECT * FROM likethecafe;
SELECT * FROM likethecafe WHERE price < 70;
SELECT SUM(price) FROM likethecafe
