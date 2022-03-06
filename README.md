# SQL_project8

## 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.  

CREATE TABLE employee (
	 id INTEGER PRIMARY KEY, 
	name VARCHAR(50) NOT NULL, 
	birthday DATE, 
	email VARCHAR(100));
  
## 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Gar Morillas', null, 'gmorillas0@dropbox.com');  
insert into employee (id, name, birthday, email) values (2, 'Ricki Isaksson', '1997-05-21', 'risaksson1@mozilla.com');  
insert into employee (id, name, birthday, email) values (3, 'Arabelle Weeds', '1988-12-13', null);  
insert into employee (id, name, birthday, email) values (4, 'Bamby Fisbburne', '2004-04-25', 'bfisbburne3@seesaa.net');  
insert into employee (id, name, birthday, email) values (5, 'Modestia Fulstow', '1998-06-26', null);  
insert into employee (id, name, birthday, email) values (6, 'Westbrook Goozee', '1952-03-28', 'wgoozee5@fda.gov');  
insert into employee (id, name, birthday, email) values (7, 'Valentijn Dean', '1971-11-19', null);  
insert into employee (id, name, birthday, email) values (8, 'Hilde Lyall', '2006-12-07', 'hlyall7@cnn.com');  
insert into employee (id, name, birthday, email) values (9, 'Kermy Ciccetti', '1953-10-16', 'kciccetti8@ted.com');  
insert into employee (id, name, birthday, email) values (10, 'Abbie Blackbrough', null, 'ablackbrough9@nps.gov');  
insert into employee (id, name, birthday, email) values (11, 'Donia Tsarovic', '2014-07-31', 'dtsarovica@themeforest.net');  
insert into employee (id, name, birthday, email) values (12, 'Cristina Grishinov', '1952-09-22', 'cgrishinovb@bizjournals.com');  
insert into employee (id, name, birthday, email) values (13, 'Farleigh Chatwood', '2020-03-16', 'fchatwoodc@shutterfly.com');  
insert into employee (id, name, birthday, email) values (14, 'Frieda Canape', '1997-04-22', 'fcanaped@uiuc.edu');  
insert into employee (id, name, birthday, email) values (15, 'Cherey Askie', '1975-12-16', 'caskiee@nps.gov');  
insert into employee (id, name, birthday, email) values (16, 'Billie Serridge', null, 'bserridgef@google.cn');  
insert into employee (id, name, birthday, email) values (17, 'Kaila Kilius', '1966-03-15', null);  
insert into employee (id, name, birthday, email) values (18, 'Saxon Falls', '1997-05-12', 'sfallsh@mozilla.com');  
insert into employee (id, name, birthday, email) values (19, 'Deidre Murrigan', '1978-10-17', 'dmurrigani@de.vu');  
insert into employee (id, name, birthday, email) values (20, 'Bax Gosz', '1983-09-11', 'bgoszj@smh.com.au');  
insert into employee (id, name, birthday, email) values (21, 'Aura Harken', null, 'aharkenk@hc360.com');  
insert into employee (id, name, birthday, email) values (22, 'Courtenay Clout', '1962-05-30', null);  
insert into employee (id, name, birthday, email) values (23, 'Mildred Wigzell', null, 'mwigzellm@stanford.edu');  
insert into employee (id, name, birthday, email) values (24, 'Lorens Macias', '1984-01-17', 'lmaciasn@biglobe.ne.jp');  
insert into employee (id, name, birthday, email) values (25, 'Gawen Cundey', '1970-12-23', 'gcundeyo@jalbum.net');  
insert into employee (id, name, birthday, email) values (26, 'Denyse Massel', '1953-12-16', null);  
insert into employee (id, name, birthday, email) values (27, 'Shannah Turford', '1960-06-22', null);  
insert into employee (id, name, birthday, email) values (28, 'Allister Koba', '1974-04-02', 'akobar@nbcnews.com');  
insert into employee (id, name, birthday, email) values (29, 'Britni Gagg', '1994-05-12', 'bgaggs@amazon.co.uk');  
insert into employee (id, name, birthday, email) values (30, 'Vanessa Kliemann', '1956-10-08', null);  
insert into employee (id, name, birthday, email) values (31, 'Vita Koppelmann', '1970-02-14', 'vkoppelmannu@kickstarter.com');  
insert into employee (id, name, birthday, email) values (32, 'Nancie Oliva', '1967-06-08', 'nolivav@unc.edu');  
insert into employee (id, name, birthday, email) values (33, 'Siana Barcroft', null, 'sbarcroftw@live.com');  
insert into employee (id, name, birthday, email) values (34, 'Sinclare Cardenoza', '2006-11-04', 'scardenozax@mozilla.org');  
insert into employee (id, name, birthday, email) values (35, 'Ethel Tosdevin', null, 'etosdeviny@earthlink.net');  
insert into employee (id, name, birthday, email) values (36, 'Rickard Gallimore', '2001-07-16', 'rgallimorez@uiuc.edu');  
insert into employee (id, name, birthday, email) values (37, 'Rosaleen Scouler', '2001-01-13', 'rscouler10@nasa.gov');  
insert into employee (id, name, birthday, email) values (38, 'Wyatt Chastel', '2017-05-24', null);  
insert into employee (id, name, birthday, email) values (39, 'Carolus Hamill', '1981-12-09', null);  
insert into employee (id, name, birthday, email) values (40, 'Bathsheba Ryde', '2015-05-15', 'bryde13@simplemachines.org');  
insert into employee (id, name, birthday, email) values (41, 'Axel Coneley', '2008-09-10', 'aconeley14@arstechnica.com');  
insert into employee (id, name, birthday, email) values (42, 'Ailyn Smallwood', '1957-04-20', 'asmallwood15@phoca.cz');  
insert into employee (id, name, birthday, email) values (43, 'Harwilll Kinlock', null, null);  
insert into employee (id, name, birthday, email) values (44, 'Mimi Foden', '1999-08-15', 'mfoden17@un.org');  
insert into employee (id, name, birthday, email) values (45, 'Geno Philipeaux', null, 'gphilipeaux18@cdbaby.com');  
insert into employee (id, name, birthday, email) values (46, 'Ray Brackstone', null, 'rbrackstone19@mysql.com');  
insert into employee (id, name, birthday, email) values (47, 'Rivi Doble', '2003-11-16', 'rdoble1a@usatoday.com');  
insert into employee (id, name, birthday, email) values (48, 'Ravi Shire', '1965-09-26', 'rshire1b@kickstarter.com');  
insert into employee (id, name, birthday, email) values (49, 'Nils Simonato', '2002-09-27', null);  
insert into employee (id, name, birthday, email) values (50, 'Emmalynn Gianiello', '2009-06-15', 'egianiello1d@yale.edu');  


## 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.  

UPDATE employee
SET name = 'alex'
WHERE id =1
RETURNING *;

UPDATE employee
SET birthday = '2022-03-06'
WHERE id =2
RETURNING *;

UPDATE employee
SET name = 'Ronaldo Edu',
email = 'ronaldo@edu.com'
WHERE id =3
RETURNING *;

UPDATE employee
SET email = 'ornek@ornek.com'
WHERE id =4
RETURNING *;

UPDATE employee
SET birthday = '1999-08-17'
WHERE id =5
RETURNING *;

## 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id=9
RETURNING *;

DELETE FROM employee
WHERE name ='Ronaldo Edu'
RETURNING*;

DELETE FROM employee
WHERE id=1
RETURNING*;

DELETE FROM employee
WHERE email = 'ornek@ornek.com'
RETURNING*;


DELETE FROM employee
WHERE birthday = '1999-08-17'
RETURNING*;
