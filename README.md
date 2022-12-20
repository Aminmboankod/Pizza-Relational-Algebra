# Pizza-Relational-Algebra
------
Course: Databases 
Unit: Introduction to the relational model
------

1.  Consider a database with the following schema:

Person | Frequents | Eats | Serves 
-------| --------- | ---- | ------
name   | name      | name | pizzeria
age    | pizzeria  | pizza| pizza
gender |           |      | price

------

Write relational algebra expressions for the following nine queries. (Warning: some of the later queries are a bit challenging.)
Verify your answers: [RelaX Calculator](https://dbis-uibk.github.io/relax/landing)

a) Find all pizzerias frequented by at least one person under the age of 18.

```

```
(Straw Hat, New York Pizza, Pizza Hut)

b) Find the names of all females who eat either mushroom or pepperoni pizza (or both).

```

```
(Amy, Fay)


c) Find the names of all females who eat both mushroom and pepperoni pizza.

```

```
(Amy)


d) Find all pizzerias that serve at least one pizza that Amy eats for less than $10.00.

```

```
(Little Caesars, Straw Hat, New York Pizza)


e) Find all pizzerias that are frequented by only females or only males.

```

```
(Little Caesars, Chicago Pizza, New York Pizza)


f) For each person, find all pizzas the person eats that are not served by any pizzeria the person frequents. Return all such person (name) / pizza pairs.

```

```
(Amy: mushroom, Dan: mushroom, Gus: mushroom)


g) Find the names of all people who frequent only pizzerias serving at least one pizza they eat.

```

```
(Amy, Ben, Dan, Eli, Fay, Gus, Hil)


h) Find the names of all people who frequent every pizzeria serving at least one pizza they eat.


```

```
(Fay)

i) Find the pizzeria serving the cheapest pepperoni pizza. In the case of ties, return all of the cheapest-pepperoni pizzerias.


```

```
(Straw Hat, New York Pizza)

