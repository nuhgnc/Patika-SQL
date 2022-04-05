## patika.dev SQL dersi 11. ödev cevapları
###### 1. actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
```sql
(
	SELECT first_name FROM actor
)
UNION ALL
(
	SELECT first_name FROM customer
)
``` 

###### 2. actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
```sql
(
	SELECT first_name FROM actor
)
INTERSECT
(
	SELECT first_name FROM customer
)
```

###### 3.  actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
```sql
(
	SELECT first_name FROM actor
)
EXCEPT
(
	SELECT first_name FROM customer
)
```
