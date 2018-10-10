/* select * from artist; */

/* select FirstName,LastName,Country from employee; */

/* select Name,Composer,Milliseconds from track
where Milliseconds>299000; */

/* select count() from track
where Milliseconds>299000; */

/* select avg(Milliseconds) from track; */

/* select count() from invoice
where BillingCountry= 'USA'; */

/* select FirstName from customer
where FirstName like '%a%'; */

/* select Name from track
order by Milliseconds desc
limit 10 ; */

/* select Name from track
order by Milliseconds
limit 20 ; */

/* select * from customer
where State ='CA'
or State='WA'; */

/* select * from customer
where State in ('CA','WA','UT','FL','AZ'); */

/* insert into artist(Name)
values('Ke$ha') */

/* insert into customer(FirstName,LastName,Company,City,State,Country,Email)
values('Emmanuel','Bravo','DevMtn','Dallas','TX','USA','eebravo1@gmail.com'); */

/* select * from playlist
where Name like 'Classical%'; */