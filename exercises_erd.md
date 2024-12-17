For all exercises implement an ER-diagram for the domain description.

Dessa övningar är tänkta att representera G på tentan.

## **Exercise 1: University Enrollment System**

**Scenario:**

A university wants to develop a system to manage information about its students, courses, and enrollments. Each student has a unique identification number, a name, and a declared major. The university offers various courses, each identified by a unique course number, along with a title and the department that offers it. Students can enroll in multiple courses, and for each enrollment, they receive a grade. Each student only have one grade in each course.

---

## **Exercise 2: Company Project Management**

**Scenario:**

A company needs a system to keep track of its employees, the departments they belong to, and the projects they are working on. Each employee has a unique ID, a name, and a job title. Employees are assigned to one department, which has its own unique ID, name and budget. Employees can work on multiple projects, and each project can have several employees assigned to it. For every project an employee works on, the company wants to record how many hours per week the employee dedicates to that project.


---

## **Exercise 3: Academic Publications**

**Scenario:**

A research institution wants to create a database to manage information about professors and their publications. Each professor has a unique ID, a name, and a department they belong to. Professors can write multiple publications, and each publication can have multiple professor authors. Publications have a unique ID, a title, and the year they were published.

---

## **Exercise 4: Online Retail System**

**Scenario:**

An online retailer wants to set up a database to manage customers, orders, and products. Each customer has a unique ID, a name, and an address. Customers place orders, each identified by a unique order ID and the date the order was placed. Each order is associated with the customer who placed it. The retailer sells various products, each with a unique product ID, a name, and a price. An order can include multiple products, and for each product in an order, the quantity ordered is recorded. You can assume that a product has the same price in all orders. 

---

## **Exercise 5: Book Publishing**

**Scenario:**

A publishing company needs a database to manage information about books, authors, and publishers. Each book has an ISBN number, a title, the year it was published, and the publisher who published it. Each publisher has a unique ID, a name, and an address. Authors have a unique ID and a name. Books can have multiple authors, and authors can write multiple books.

Advanced exercises är tänkt att representera en VG-fråga på tentan.
## Advanced exercise 1
Andra frågan är mer än VG.
https://opentextbc.ca/dbdesign01/back-matter/appendix-b-erd-exercises/

## Advanced exercise 2
The University of Bristol Hoverboard Society (HovSoc) wants to create a database to manage its membership and events. Each member has a name, an optional student number, a contact e-mail address and a hoverboard riding skill level (represented as an integer, minimum 0). We assume that e-mail addresses are unique among members.

The committee consists of some of the members, each of which has a unique committee role. We assume that committee roles do not change during the year and that each committee role must be filled every year.

An event has a date, a name, a location, an optional description and an organiser who must be a society member (not necessarily a committee member). An event is attended by a set of members. There is never more than one event at the same location on the same date but event names are not unique.


## Advanced exercise 3
Your task is to make an ER-diagram for the database of a gym company, managing their
facilities and their customer records.

The database should contain a set of current and past customers. Each customer has a name
and an email-address. Not every customer is a current member, and the database should keep
track of which customers are currently members, and when their membership expires.

Each gym facility has a city, an address and a name. Two facilities can have the same name,
but only if they are in different cities. Gym facilities can be established in any city across the
world (but you can assume cities have unique names).

The database should also keep a record of times when each customer has accessed any gym
facility. This may include multiple accesses from the same customer to the same facility at
different times.

## Advanced exercise 4
A company needs help designing a database for managing the inventory and sale prices of
a chain of stores.
The description of the domain is as follows:
- The chain contains multiple stores, each identified by its address.
- Every product sold by the chain has its own name.
- Every store has an inventory of products in the store, that is, how many items of
each product they currently have in stock.
- Products are sold in packages of different sizes. Different products are packaged in
different sizes, for example one product could be sold in 5-packs and 10-packs, and
another product only in single packs (size 1).
- Each package size of a product has its price, so a 5-pack of a product could cost 20
and a 10-pack of the same product cost 35. The price is the same in all stores.
- Discounts could be applied to particular size packages of a product, for example the
5-packs of a certain product could have a discount but not all other size packages for
that product. Each discount should have a reduction and a description such as 25%
and “Christmas sale”. There cannot be multiple discounts on the same pack size
of a product but different size packages of the some product could have their own
discount.
- Some products have one other product as “best bought together with” that clients
are recommended to also buy, for example when the client wants to buy a particular
model of a Mac then he/she is recommended to also buy a certain external screen
to maximise the experience. In these cases, even an extra discount for the second
product is offered.


