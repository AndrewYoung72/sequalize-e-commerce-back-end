# sequalize-e-commerce-back-end
GitHub Link: https://github.com/AndrewYoung72/sequalize-e-commerce-back-end


## Purpose
The purpose of this challenge was to get us familiar with the fundamental architecture of e-commerce platforms. We were to configure a working Express.js API using Sequalize to interact with our MySQL databse.
## Description
The appliction is linked to mysql database using the environment variable file. The schema and seed files were provided in the starter code so I sourced the schema in mysql and ran the  seeds/index.js command in my node.js to seed the database. When the node server.js, or npm start, command is entered in the terminal the user is presented with a prompt stating that the app is now listening. Then the user can go to insomnia and test the routes. I have the routes divided into three categories with five routes in each category. Each category has a get all, get by id, post to create, update, and delete by id route. If requested category, product, or tag does not exist then the user receives a message stating so. 
## Lessons
This challenge has made me much more comfortable with routes. We have been working with them for awhile now but I feel like this project brought a lot of things together for me that were a little cloudy before. I do need to study the starter code provided in the product POST and PUT routes a little more so I can understand exactly what each step is doing. And I also need to find a clearer  source of information for me as to entering commands in the insomnia routes. My product update is not working quite right but I think the problem is how I enter the multiple id's in the Insomnia browser. 