# sql--tehtavat
SQL-tehtavat

https://imgur.com/a/82fh9at - kuva käyttäjän raportista moodlen sivuilta.

https://imgur.com/a/qs1vbtb - kuva yleis raportista moodlen sivuilta.

Viikko 1
Relaatiotietokannan peruskäsitteiden harjoitukset

1:
https://imgur.com/a/EgMR6e9
Kaikki tehtävät tehty. (ei sisältänyt kirjoitettuja SQL kyselyitä joten en ottanut kuvaa kysymyksistä.)

Viikko 2

1 
Imgur albumi palautus sisältää "Yhteen tauluun kohdistuvien kyselyiden harjoitukset" liittyvät kuvat ja toteutukset: 

https://imgur.com/a/QgwMtRn 
Kaikki paitsi 7 tehty.

Tehtävä 1:
SELECT * from goal;

Tehtävä 2:

SELECT name from airport where iso_country = 'FI';

tehtävä 3:

SELECT name from airport where iso_country = 'FI'
order by name asc

Tehtävä 4:
select name, type from airport where iso_country = 'FI'
order by type, name

Tehtävä 5:
select name from country where name like 'F%';

Tehtävä 6:
select name from country where name like '%F%';

Tehtävä 8:
select distinct co2_budget from game where co2_budget = 10000;

--------------------------------------------------------------------
Where-osan liitosehto harjoitukset

Tehtävät 1,2,8,9 tehty.

Imgur albumi palautus sisältää liittyvät kuvat ja toteutukset:

https://imgur.com/a/AyRvFAp

tehtävä 1:
SELECT 'Iceland' as 'country_name', name as 'airport_name' from airport where iso-country = "IS";

tehtävä 2:
SELECT name as 'airport_name from airport where iso_country = "FR" and type = "large_airport";

tehtävä 8:
select name from goal where name in ('10DEG', 'CLOUDS');

tehtävä 9:
SELECT name from airport where ident = 'EGKK';
