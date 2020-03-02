<img src="https://www.soulve.nu/wp-content/uploads/2019/11/logo-soulve.png" width="200">

# Hospital Product Catalog Assignment #

## Goal ##

The goal of this assignment is to show your coding skills and what you value in software engineering. At SOULVE we value new ideas: next to the original requirement feel free to improve/add/extend.
Think of this exercise as a proof of concept that should be scalable, easy to maintain and well tested. Choose a .NET (stable) version that you feel comfortable with.
As this is a proof of concept, do not spend much time on complex data persistence implementation but instead make sure your project has the correct abstractions in place so it can be easily replaced with little or no effort at all.
Avoid unnecessary complexity such as implementing a queue system or messaging architecture in favor or a clean and SOLID n-layer architecture.

## The Assignment ## 

* Create a RESTful service that allows client applications to manage the hospital’s product catalog. It needs to expose endpoints to create, read, edit and delete products categories, such as implants and consumables, and also to manage products of these categories.
* For categories, we need to store their code (unique) and description. For products, we need to store their code (unique), description, list of barcodes (unique), quantity, unit of measurement (for example, pack, box and unit), expire date, and their respective categories.
* Handle products in stock, security, or/and any other functionality are nice to have, but not required.
* Make assumptions in the implementation explicit, choices are good but need to be communicated.

## Must haves ## 

* Solution written in C#;
* Internal logic shall be under unit test;
* Functionality shall be under integration test;
* Documentation in code;
* Clear and to the point readme on usage.

## Nice to haves ## 

* Suggestions for improvement

## Evaluation Criteria ##

* Project organization: Evaluates project structure, documentation and use of version control;
* Technological innovation: Evaluates the use of newer technologies, provided they are stable;
* Coherence: Evaluates whether requirements have been met;
* Good practices: Evaluates whether the project follows good development practices, including security and optimization;
* Quality Control: Evaluates whether the project has quality assured by unit tests.

> Happy coding. Good luck!
