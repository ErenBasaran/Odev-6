Soru 1 Cevap :
select avg(rental_rate) from film <br>
Soru 2 Cevap :
select count(*) from film
where title like 'C%' <br>
Soru 3 Cevap :
select max(length) from film
where rental_rate =0.99 <br>
Soru 4 Cevap :
select count(distinct replacement_cost) from film
where length >150
