Mineground Database Interface
=================
This repository contains the MySQL database interface as used by [Las Venturas Mineground](http://mineground.com/), also known as Mineground.

Mineground's database interface provides a clean, portable and asynchronous interface to a MySQL database. The connection with the database will be established on a separate thread, which is also where queries will be executed.

For ease of programming, a query's results will be delivered using a Promise. These are similar to Java's Futures, but with slightly different semantics.