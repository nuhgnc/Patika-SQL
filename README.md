## patika.dev SQL dersi 8. ödev cevapları
###### 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

    create table employee (
	id serial primary key,
	name varchar(50),
	birthday date,
	email varchar(100)
	)
    
###### 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

    insert into employee (id, name, birthday, email) values (1, 'Raine', '1999-01-20', 'rroadknight0@oracle.com');
    insert into employee (id, name, birthday, email) values (2, 'Nat', '2020-10-21', 'nkirsopp1@usda.gov');
    insert into employee (id, name, birthday, email) values (3, 'Fawne', '2006-05-21', 'fcoryndon2@usatoday.com');
    insert into employee (id, name, birthday, email) values (4, 'Morton', '1999-10-30', 'mkenyam3@shareasale.com');
    insert into employee (id, name, birthday, email) values (5, 'Ravid', '2000-01-21', 'rmonroe4@alexa.com');
    insert into employee (id, name, birthday, email) values (6, 'Nariko', '2002-05-17', 'ndunwoody5@nymag.com');
    insert into employee (id, name, birthday, email) values (7, 'Kelbee', '2002-09-20', 'klovelace6@merriam-webster.com');
    insert into employee (id, name, birthday, email) values (8, 'Austen', '1999-01-07', 'astatersfield7@bloglines.com');
    insert into employee (id, name, birthday, email) values (9, 'Effie', '2004-09-20', 'ekeeri8@salon.com');
    insert into employee (id, name, birthday, email) values (10, 'Candide', '2012-09-16', 'cboltwood9@newsvine.com');
    insert into employee (id, name, birthday, email) values (11, 'Colas', '2013-02-11', 'cheadinghama@163.com');
    insert into employee (id, name, birthday, email) values (12, 'Janey', '2003-06-03', 'jarnowitzb@home.pl');
    insert into employee (id, name, birthday, email) values (13, 'Danya', '2017-01-22', 'ddelabarrec@newsvine.com');
    insert into employee (id, name, birthday, email) values (14, 'Corilla', '2021-06-15', 'cjorczykd@free.fr');
    insert into employee (id, name, birthday, email) values (15, 'Bradford', '2018-12-16', 'btownsende@mapy.cz');
    insert into employee (id, name, birthday, email) values (16, 'Alexa', '2021-11-24', 'aolandaf@mayoclinic.com');
    insert into employee (id, name, birthday, email) values (17, 'Angele', '2006-11-17', 'agullamg@barnesandnoble.com');
    insert into employee (id, name, birthday, email) values (18, 'Starla', '2003-09-20', 'sthurgoodh@rediff.com');
    insert into employee (id, name, birthday, email) values (19, 'Harv', '2005-05-28', 'hfantinii@cmu.edu');
    insert into employee (id, name, birthday, email) values (20, 'Layney', '1999-08-10', 'ldetocquevillej@prlog.org');
    insert into employee (id, name, birthday, email) values (21, 'Clifford', '2012-06-14', 'cpullmank@so-net.ne.jp');
    insert into employee (id, name, birthday, email) values (22, 'Kristin', '2007-12-04', 'kvigursl@dailymail.co.uk');
    insert into employee (id, name, birthday, email) values (23, 'Phyllida', '2001-06-14', 'plamzedm@accuweather.com');
    insert into employee (id, name, birthday, email) values (24, 'Alic', '2017-06-17', 'adecrusen@businesswire.com');
    insert into employee (id, name, birthday, email) values (25, 'Emmerich', '2010-11-06', 'etulliso@ftc.gov');
    insert into employee (id, name, birthday, email) values (26, 'Arlyne', '2003-05-28', 'apasticznykp@pcworld.com');
    insert into employee (id, name, birthday, email) values (27, 'Jermaine', '2014-09-05', 'jbrimmingq@guardian.co.uk');
    insert into employee (id, name, birthday, email) values (28, 'Coral', '2020-06-05', 'cfaussettr@sina.com.cn');
    insert into employee (id, name, birthday, email) values (29, 'Edythe', '2021-11-20', 'ebonifazios@craigslist.org');
    insert into employee (id, name, birthday, email) values (30, 'Hazlett', '2000-12-28', 'hlightowlert@youku.com');
    insert into employee (id, name, birthday, email) values (31, 'Alidia', '2018-06-25', 'agepheartu@jigsy.com');
    insert into employee (id, name, birthday, email) values (32, 'Tommy', '2000-06-07', 'thackfordv@wikia.com');
    insert into employee (id, name, birthday, email) values (33, 'Edsel', '1999-04-13', 'eseamarkew@elegantthemes.com');
    insert into employee (id, name, birthday, email) values (34, 'Ethelred', '2012-07-26', 'emcreynoldsx@soundcloud.com');
    insert into employee (id, name, birthday, email) values (35, 'Dore', '2011-01-04', null);
    insert into employee (id, name, birthday, email) values (36, 'Rutter', '2021-12-28', 'rstodez@sun.com');
    insert into employee (id, name, birthday, email) values (37, 'Kania', '2013-01-29', 'kdumphy10@msu.edu');
    insert into employee (id, name, birthday, email) values (38, 'Gretta', '2016-12-18', 'gwyer11@toplist.cz');
    insert into employee (id, name, birthday, email) values (39, 'Harcourt', '2013-08-25', 'hhubber12@google.es');
    insert into employee (id, name, birthday, email) values (40, 'Jorey', '2019-08-18', 'jwayne13@netvibes.com');
    insert into employee (id, name, birthday, email) values (41, 'Jeffy', '2019-09-25', 'jeate14@google.fr');
    insert into employee (id, name, birthday, email) values (42, 'Audie', '2000-09-20', null);
    insert into employee (id, name, birthday, email) values (43, 'Fraser', '2015-06-06', 'fveque16@admin.ch');
    insert into employee (id, name, birthday, email) values (44, 'Matty', '2010-04-02', 'mcromleholme17@geocities.jp');
    insert into employee (id, name, birthday, email) values (45, 'Neale', '2001-05-03', 'nmcgaw18@a8.net');
    insert into employee (id, name, birthday, email) values (46, 'Kristian', '2000-04-08', 'kelman19@issuu.com');
    insert into employee (id, name, birthday, email) values (47, 'Athene', '2007-09-14', 'acirlos1a@chicagotribune.com');
    insert into employee (id, name, birthday, email) values (48, 'Fredia', '2010-03-16', 'fbiggans1b@behance.net');
    insert into employee (id, name, birthday, email) values (49, 'Carlyle', '2019-06-27', 'cudy1c@apple.com');
    insert into employee (id, name, birthday, email) values (50, 'Eustace', '2005-11-21', 'egiovanitti1d@cmu.edu');

###### 3.  Sütunların her birine göre diğer sütunları güncelleyecek 4 adet UPDATE işlemi yapalım.

    UPDATE employee 
	SET id = 51,
	    name = 'Dora',
	    birthday = '2001-01-04',
	    email = 'dorasmail@gmail.com'
    WHERE id = 35
    RETURNING *;
    
###### 4. Sütunların her birine göre ilgili satırı silecek 4 adet DELETE işlemi yapalım.

    DELETE FROM employee 
    WHERE id = 51
    RETURNING *

