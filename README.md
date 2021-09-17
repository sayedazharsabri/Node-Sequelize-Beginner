This is a NodeJS project. I created this project in my workshop to demonstrate CRUD operation using NodeJS and Sequelize(With MySQL)

Video Link: https://www.youtube.com/channel/UC0WKTSptW8OoMePQjGAubBQ?sub_confirmation=1

Playlist: NodeJS Workshops[Hindi]

Please create db "workshop"

#Use below query to create table
CREATE TABLE `workshop`.`users` ( `id` INT(11) NOT NULL AUTO_INCREMENT , `name` VARCHAR(255) NOT NULL , `email` VARCHAR(255) NOT NULL , `password` VARCHAR(255) NOT NULL , `remark` VARCHAR(255),  PRIMARY KEY(`id`) );

and alter and add below columns or add in create query

ALTER TABLE `users` ADD `createdAt` TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP AFTER `remark`, ADD `updatedAt` TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP AFTER `createdAt`;


I used XAMPP PHPMyAdmin panel, you may use any other,

#After clone please run

npm install

#it help, in installing dependencies

In this project you will find
- app.js
- node express server
- body parser
- routers
- controllers
- model
- util 
- Sequelize package
- Implementation of sequelize in NodeJS
- databse connection details ( in proper development we naver keep configuration and credential details in file, here I just started the workshop so its for practice purpose)
- in sql folder, there is a file with query



